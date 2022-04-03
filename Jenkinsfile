pipeline {
    agent any
    stages{
        stage('git clone'){
            steps{
                git branch: 'main', url: 'https://github.com/Sonu0803/demo1.git'
            }
        }
        
        stage('test'){
            steps{
                echo "Testing completed!!"
            }
        }
        
        stage('build'){
            steps{
                echo "hello this is buils stage!!"
            }
        }
    }
}
