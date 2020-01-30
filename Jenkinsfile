pipeline{
libraries{
lib 'jira_connector'
}

agent any
stages{

  stage('Jira_create_project'){
      
    steps{
            jira_create_project()
}
}
   stage('Jira_collect_issue'){
 
            steps {
                
               jira_collect_issue()
            }
        }
        
}
}
