node{
  stage('git'){
   git 'https://github.com/aangsiety/mavenaug04'
  }
  stage('Mvn Building'){
   def mvnHome = tool name: 'maven', type: 'maven'
    sh "${mvnHome}/bin/mvn compile"
  }
}
