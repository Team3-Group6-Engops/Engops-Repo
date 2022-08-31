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
        stage('2-second name'){
            steps{
                echo "My name is Claudi-ann"
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
                sh 'sudo chmod +x claudi.sh'
                sh 'bash -x claudi.sh'
            }
        }
    }
}