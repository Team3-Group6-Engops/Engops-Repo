pipeline{
    agent any
    stages{
        stage('1-my name'){
            steps{
                echo "My name is Abayomi"
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
                sh 'sudo chmod +x yomi.sh'
                sh 'bash -x yomi.sh'
            }   
           
        }
    }
}