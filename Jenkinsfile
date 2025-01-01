node{
  stage('Build'){
    echo 'bulding'
    currentBuild.result = 'SUCCESS'
  }
  stage('Test'){
    echo 'Testing'
  }

  if(currentBuild.result == 'SUCCESS'){
    echo 'Looks Good'
  }else{
    echo 'Failed'
  }
}

