pipeline{
libraries{
lib 'shlib5'
}

agent any
stages{

  stage('Jira_create_project')
  {    
    steps
    {
            jira_create_project()
            jira_log_con(" project created")
            }
            post{
                failure{
                 jira_log_con("Project not created")
                }
            }
         
    }
  
  stage('Jira_collect_issue')  
  {
    steps 
    {            
             jira_collect_issue()
            jira_log_col("issue collected")
            }
            post{
                failure{
                 jira_log_col("Issue not collected")
                }
            }
    }
  
  
        
      }
}
