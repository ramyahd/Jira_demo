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
    

      stage('Jira_add_comment')
  {    
    steps
    {
            jira_add_comment1(JSON)
            log_function("Comment added",JSON)
    }
    post
    {
         failure
    {
      log_function("Comment not addedd",JSON)
    }       
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
      /* stage('Jira_delete_issue')
  {    
    steps
    {
            jira_delete_issue_json(JSON)
            log_function("Issue deleted",JSON)
    }
    post
    {
         failure
    {
      log_function("Issue not deleted",JSON)
    }       
    }    
    }*/

 /*  stage('Jira_delete_project')
  {    
    steps
    {
            jira_delete_project(JSON)
            log_function("project deleted",JSON)
    }
    post
    {
         failure
    {
      log_function("project not deleted",JSON)
    }       
    }
           
         
    
  }*/
  
        
      }
}
