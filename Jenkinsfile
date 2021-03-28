pipeline {
    agent any
    stages {
        stage ("Deploy") {
            steps {
                echo "Deploy in progress by Jenkins"
            }
            post {
                always {
                    jiraSendDeploymentInfo site: 'siebeldevops.atlassian.net', environmentId: 'au-dev-1', environmentName: 'au-dev-1', environmentType: 'development'
                }
            }            
        }
    }
}
