pipeline {
    agent any
    stages {
        stage ("Start") {
            steps {
                echo "Starting a multi-branch pipeline job"
            }
        }
        stage ("Fetch Code") {
            steps {
                echo "Fetching code from Git repository"
            }
        }
        stage ("Workspace Delivery") {
            steps {
                echo "Delivering Siebel Workspace changes"
            }
        }
        stage ("Test") {
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
