pipeline {
  agent any
  stages {
    stage('Building') {
      steps {
        echo 'Building Stage Running'
        echo "Running (env.DISPLAY_ID) $(env.DISPLAY_NAME) on $(env.NODE_NAME) and JOB $(env.JOB_NAME)"
      }
    }
    stage('Testing'){
      steps{
        echo 'Testing Stage Running'
      }
    }
    stage('Deployment'){
      steps{
        echo 'Deployment Stage Running'
      }
    }
  }
}
