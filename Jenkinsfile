// pipeline{
//   agent { label 'Jenkins-Agent' }
//   tools {
//     jdk 'Java17'
//     maven 'Maven3'
//   }
//   stages{
//       stage("Cleanup Workspace"){
//         steps{
//           cleanWs()
//         }
//       }

//       stage("Checkout from SCM"){
//         steps {
//           git branch: 'main', credentialsId: 'github', url: 'https://github.com/God-Eurus/register-app'
//         }
//       }
//       stage("Build Application"){
//         steps{
//           sh "mvn clean package"
//         }
//       }
//       stage("Test Application"){
//         steps {
//           sh "mvn test"
//         }
//       }
//   }
// }

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building (but nothing real yet!)'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing (fake stage!)'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying (simulated)'
            }
        }
    }
}

