pipeline{
libraries{
lib 'jira_connector'
}

agent any
stages{

  stage('Jira_create_project')
  {    
    steps
    {
            jira_create_project()
            log_function(" project created")
            }
            post{
                failure{
                 log_function("Project not created")
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
