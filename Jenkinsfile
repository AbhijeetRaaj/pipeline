pipeline{
    agents any
  stages{
    stage('BUILD'){
      steps{
          sh ' echo "this is a build step" '
      }   
      stage('TEST'){
        steps{
          sh ' echo "this is a test step"'
        }
        stage('DEPLOY'){
          steps{
           sh ' echo "this is a deploy step"'
          }
        }
      }
    }
  }
}
