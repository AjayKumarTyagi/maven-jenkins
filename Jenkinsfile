pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('Test'){
          steps{
          shell('mvn clean')
          }
      }
          stage('deploy'){
          steps{
          shell('mvn deploy')
          }
          }
      }
    }

