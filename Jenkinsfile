pipeline{
libraries{
lib 'shlib5'
}

agent any
stages{
  
  /*stage(jira)
  {
    steps
    {
        script
      {
        jira_collect_issue.issue(JSON)
         jira_collect_issue.create()
    }  }*/
        /*  jira_create_json(JSON)
          log_function("JIRA","Project created")
          jira_create_issue_json(JSON)
          log_function("JIRA","Issue created")
          jira_create_subtask_json(JSON)
          log_function("JIRA","Subtask created")
          jira_add_comment1(JSON)
          log_function("JIRA","Comment added")*/
          //jira_collect_issue(JSON)
        //  jira_collect_DONE(JSON)
          //Move_to_influx()
        //  log_function("JIRA","Issue collected")
        /*  jira_collect_particular_issue(JSON)
          log_function("JIRA","Issue collected")
          jira_summary_of_project(JSON)
          log_function("JIRA","Project summary collected")
          jira_get_comments_of_issue(JSON)
          log_function("JIRA","Comments collected")*/
          //jira_delete_issue_json(JSON)
          //jira_delete_project(JSON)  
    
  stage("DONE TASK")
    {
      
    steps
    {
      script
      {
    jira_collect_DONE.taskdone(JSON)
    jira_collect_DONE.create()
    }
    }
    }

  
  
  
  
  /*stage('Jira_create_project')
  {    
    steps
    {
      jira_create_json(JSON)
   // log_function("Project created")
    }
    
   }
  
  
   stage('Jira_create_issue')
  {    
    steps
    {
            jira_create_issue_json(JSON)
    //      log_function("Issue created")
    }
    }
  
  
 
  
      stage('Jira_create_subtask')
  {    
    steps
    {
            //jira_create_subtask_json(JSON)
            jira_create_subtask_file(JSON)
   //         log_function("Subtask created")
    }
   
    }
    

      stage('Jira_add_comment')
  {    
    steps
    {
            jira_add_comment1(JSON)
  //          log_function("Comment added")
    }
    
    }
    
  
  stage('Jira_collect_issue')  
  {
    steps 
    {            
             jira_collect_issue(JSON)
   //       log_function("project issues collected")
      
    }
    
  
  }
  
  
   stage('Jira_collect_particular_issue')  
  {
    steps 
    {            
             jira_collect_particular_issue(JSON)
  //           log_function("Issue collected")
    }
   
  }
    
   stage('Jira_collect_summary_of_project')  
  {
    steps 
    {            
             jira_summary_of_project(JSON)
   //       log_function("project summary collected")
      
    }
    
   
  }
  
 
  
     stage('jira_get_all_comments_of_issue')  
  {
    steps 
    {            
             jira_get_comments_of_issue(JSON)
   //          log_function("All comments collected")
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
  
        
      

