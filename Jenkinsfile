pipeline {
    agent any
    stages {
        stage ("Start") {
            steps {
                echo "Starting a multi-branch pipeline job"
            }
        }
        stage ("Git Clone") {
            steps {
                echo "Fetching code from Git repository"
            }
        }
        stage ("Deliver Siebel Workspace") {
            steps {
                echo "Delivering Siebel Workspace changes"
            }
        }
        stage ("Git Clone") {
            steps {
                echo "Triggering test automation"
            }
        }
        stage ("Done") {
            steps {
                echo "Finishing the job"
            }
        }
    }
}
