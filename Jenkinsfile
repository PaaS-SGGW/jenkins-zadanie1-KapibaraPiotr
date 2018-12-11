pipeline {
    agent any
    stages {
        stage('Heroku push') {
            steps {
                echo "Hello World!"
                bat "heroku git:remote -a paas-jenkins"
                ba1t "git push heroku HEAD:master"
                }
            }
        }
    }
}
