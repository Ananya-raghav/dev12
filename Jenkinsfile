pipeline{
 agent any
 stages{
   stage('Checkout'){
     steps{
        git branch: 'master', url:
'https://github.com/Ananya-raghav/dev12.git'
   }
  }
  stage('Hello'){
    steps{
      echo "hello from Jenkins Pipeline!"
     }
   }
  stage('Goodbye'){
    steps{
      echo "Pipeline finished sucessfully"
       }
     }
    }
   
