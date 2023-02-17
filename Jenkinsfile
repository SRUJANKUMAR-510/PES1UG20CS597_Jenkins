pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                sh 'g++ -c PES1UG20CSFDSFS597.cpp'
                sh 'g++ -o PES1UG20CS597 PES1UG20CS5SD97.cpp'
                echo 'build stage successfull'
            }
        }
        stage('Test'){
            steps{
                sh './PES1UG20CS597'
                echo 'Test stage executed successfully'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deployed has been Successfully'
            }
        }
    }
    post{
        failure{
            echo 'Pipeline has been Failed'
        }
    }
}
