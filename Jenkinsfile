pipeline {
    agent any
    triggers {
        githubPush()  // מופעל אוטומטית בכל Push
    }
    stages {
        stage('Print Message') {
            steps {
                echo "A change was pushed to the repository!"
                sh 'echo Build triggered by Webhook'
            }
        }
    }
}
