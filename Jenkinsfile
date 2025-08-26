pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', 
                    url: 'https://github.com/yonre4444/terraform-infra-setup.git', 
                    credentialsId: 'terraform'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Webhook ishladi! 🚀'
            }
        }
    }
}
