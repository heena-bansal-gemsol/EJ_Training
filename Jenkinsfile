pipeline{
  agent any
  stages{
    stage('compile'){
      steps{
        echo "Compiled successfully"
      }
    }
    stage('JUnit'){
      steps{
        echo "JUnit passed successfully"
      }
    }
    stage('Quality gate'){
      steps{
        echo "Qulaity gate passed"
      }
    }
    stage('Deploy'){
      steps{
        echo Deployed successfully
      }
    }
  }
  post{
    always{
      echo "Always run"
    }
    success{
      echo "On success"
    }
    failure{
      echo "On failure"
    }
  }
}
