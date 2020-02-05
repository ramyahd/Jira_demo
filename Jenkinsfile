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
     /* sh """
      curl --request POST \
  --url http://ec2-18-191-16-16.us-east-2.compute.amazonaws.com:8080/rest/api/2/project \
  --header 'authorization: Basic cmlnOmRpZ2l0YWxyaWdAMTIz' \
  --header 'cache-control: no-cache' \
  --header 'content-type: application/json' \
  --header 'postman-token: 86ac9823-0baf-f77b-5fe9-23391b2a91a1' \
  --data '{\r\n          \r\n          "name": "EDN250",\r\n          "key":"EDN",\r\n          "projectTypeKey": "software",\r\n          "lead": "rig"\r\n}\r\n\r\n'"""
       */
      jira_create_json(JSON)
  
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
  
    }
           
         
    }
  
  
     stage('Jira_delete_project')
  {    
    steps
    {
            jira_delete_project(JSON)
  
    }
           
         
    
  }
  
  
      stage('Jira_create_subtask')
  {    
    steps
    {
            jira_create_subtask_json(JSON)
  
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
