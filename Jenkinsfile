node {
  stage('GIT checkout'){
     git 'https://github.com/manishk35165/myapp'
  }
  stage('Package') {
    sh 'mvn package'
  }
}
