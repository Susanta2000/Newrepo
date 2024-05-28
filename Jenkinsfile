pipeline {
  agent any
  stages {
    stage("build") {
      steps{
         echo 'Project building....' 
      }
    }
    stage("test") {
      steps{
          echo 'Project testing....' 
      }
    }
    stage("deploy") {
      steps{
         echo 'Project deploying.....' 
      }
    }
    
  }
  post{
  always {
    echo "Pipeline completed"
  }
  success {
    echo 'Pipeline successfully completed :)'
  }
  faliure{
    echo "Pipeline failed"
  }
  
}
}
