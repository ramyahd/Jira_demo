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
  
    }
           
         
    }
  
   stage('Jira_create_issue')
  {    
    steps
    {
            jira_create_issue()
  
    }
           
         
    }
  

/*  stage('Jira_collect_issue')  
  {
    steps 
    {            
             jira_collect_issue()
      
    }
  }
  */
  
  
        
      }
}
