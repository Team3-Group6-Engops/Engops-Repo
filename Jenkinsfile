pipeline{
    agent any
    stages{
        stage('cloning'){
            steps{
            checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'jenkinsgit', url: 'https://github.com/Team3-Group6-Engops/Engops-Repo.git']]])    
            
            }
        }
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

        stage('3-third name'){
            steps{
                echo "My name is abbey"
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
                sh 'sudo chmod +x abbey.sh'
                sh 'bash -x abbey.sh'
            }
        }
        stage('4-fourth name'){
            steps{
                echo "my name is Lateef"
                sh 'ps -ef'
                sh 'sudo systemctl status jenkins'
                sh 'sudo chmod +x lateef.sh'
                sh 'bash -x lateef.sh'
            }
        }
    }
}
