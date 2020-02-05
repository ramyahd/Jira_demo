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
      jira_create_json(JSON)
    log_function("Project created",JSON)
    }
    post
    {
    failure
    {
      log_function("Project not created",JSON)
    }
    }
   }
  
  
/*  stage('Jira_create_project')
  {    
    steps
    {
            jira_create_project()
  
    }
           
         
    }
  */
   stage('Jira_create_issue')
  {    
    steps
    {
            jira_create_issue_json(JSON)
          log_function("Issue created",JSON)
    }
    post
    {
        failure
    {
      log_function("Project not created",JSON)
    }    
    }    
    }
  
  
 
  
      stage('Jira_create_subtask')
  {    
    steps
    {
            jira_create_subtask_json(JSON)
            log_function("Subtask created",JSON)
    }
    post
    {
         failure
    {
      log_function("subtask not created",JSON)
    }       
    }    
    }

 /*   stage('Jira_delete_project')
  {    
    steps
    {
            jira_delete_project(JSON)
  
    }
           
         
    
  }*/
  
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
