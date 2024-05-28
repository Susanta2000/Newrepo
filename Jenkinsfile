pipeline {
  agent any
  stages {
    stage("build") {
      echo 'Project building....'
    }
    stage("test") {
      echo 'Project testing....'
    }
    stage("deploy") {
      echo 'Project deploying.....'
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
