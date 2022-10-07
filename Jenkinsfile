pipeline{
  agent any
  
  stages{
    stage('stage-1'){
      steps{
        echo 'this is stage1'
    }
  }
    stage('stage-2'){
      steps{
        echo 'this is stage2'
    }
  }
    stage('parallel execution'){
    parallel{
      stage('stage-3'){
        steps{
          echo 'this is stage3'
        }
      }
      stage('stage-4'){
        steps{
          echo 'this is stage4'
        }
      }
      stage('stage-5'){
        steps{
          echo 'this is stage5'
        }
      }
    }
    }  
  }
}
