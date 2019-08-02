node{
  stage('SCM heckout'){
git 'https://github.com/mnahid1/pipeline_git_maven.git'
  }
stage('Compile-Package'){
def mvnHome = tool name: 'Maven', type: 'maven'
sh "${mvnHome}/bin/mvn package"
}
}
