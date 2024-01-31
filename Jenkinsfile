node{
  stage('buildImage'){
    openshiftBuild(buildConfig: 'openshifttest-git', showBuildLogs: 'true')
  }
  stage('deployApplication'){
    openshiftDeploy(deploymentConfig: 'openshifttest-git')
  }
}
