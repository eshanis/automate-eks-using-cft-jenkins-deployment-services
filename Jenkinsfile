pipeline {
    agent any
    stages {
        stage('Automate webapp') {
            steps {
            sh "aws eks --region us-east-1 update-kubeconfig --name eshani-EKS-node14"
              sh "kubectl apply -f deployment2.yml"
                sh "kubectl apply -f service2.yml"
              }
           
          
         }


     }
}
