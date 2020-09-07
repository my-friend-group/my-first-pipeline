pipeline {
    agent any

    stages {
        stage('run when feature') {
            when {
          branch 'feature'
            }
            steps {
                echo 'this runs only on feature branch'
            }
        }
        stage('run when master') {
            when {
                branch 'master'
            }
            steps {
                echo 'this runs only on master branch'
            }
        }
    }
}
