pipeline{
libraries{
lib 'shlib5'
}

agent any
stages{
  
  stage(jira)
  {
    steps
    {
        jira_delete_issue_json(JSON)
        
    }
    steps
    {
       jira_delete_project(JSON)
    }
      
  } 
  
  
  
/*  stage('Jira_create_project')
  {    
    steps
    {
      jira_create_json(JSON)
    log_function("Project created")
    }
    post
    {
    failure
    {
      log_function("Project not created")
    }
    }
   }
  
  
   stage('Jira_create_issue')
  {    
    steps
    {
            jira_create_issue_json(JSON)
          log_function("Issue created")
    }
    post
    {
        failure
    {
      log_function("Project not created")
    }    
    }    
    }
  
  
 
  
      stage('Jira_create_subtask')
  {    
    steps
    {
            jira_create_subtask_json(JSON)
            log_function("Subtask created")
    }
    post
    {
         failure
    {
      log_function("subtask not created")
    }       
    }    
    }
    

      stage('Jira_add_comment')
  {    
    steps
    {
            jira_add_comment1(JSON)
            log_function("Comment added")
    }
    post
    {
         failure
    {
      log_function("Comment not addedd")
    }       
    }    
    }
    
  
  stage('Jira_collect_issue')  
  {
    steps 
    {            
             jira_collect_issue(JSON)
          log_function("project issues collected")
      
    }
    
     post
    {
         failure
    {
      log_function("project issues not collected")
    }
    }
    
  }
  
  
   stage('Jira_collect_particular_issue')  
  {
    steps 
    {            
             jira_collect_particular_issue(JSON)
             log_function("Issue collected")
    }
     post
    {
         failure
    {
      log_function("Issue not collected")
    }
  }
  }
    
   stage('Jira_collect_summary_of_project')  
  {
    steps 
    {            
             jira_summary_of_project(JSON)
          log_function("project summary collected")
      
    }
    
     post
    {
         failure
    {
      log_function("project summary not collected")
    }
    }
    
  }
  
 
  
     stage('jira_get_all_comments_of_issue')  
  {
    steps 
    {            
             jira_get_comments_of_issue(JSON)
             log_function("All comments collected")
    }
     post
    {
         failure
    {
      log_function("Comments not collected")
    }
  }
  }*/
    
 /*        stage('Jira_delete_issue')
  {    
    steps
    {
            jira_delete_issue_json(JSON)
            log_function("Issue deleted")
    }
    post
    {
         failure
    {
      log_function("Issue not deleted")
    }       
    }    
    }

  stage('Jira_delete_project')
  {    
    steps
    {
            jira_delete_project(JSON)
            log_function("project deleted")
    }
    post
    {
         failure
    {
      log_function("project not deleted")
    }       
    }
           
  }  */   
    
  }
}
  
        
      

