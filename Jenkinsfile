pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                echo 'Hello World- Development'
                bat 'git clone "https://github.com/SampatKandukuri10/basic-banking-system.git"'
            }
        }
        stage('QA') {
            steps {
                echo 'Hello World-QA'
            }
        }
        stage('UAT') {
            steps {
                echo 'Hello World-UAT'
            }
        }
        stage('PreProd') {
            steps {
                echo 'Hello World-PreProd'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello World-prod'
            }
        }
        
    }
}
