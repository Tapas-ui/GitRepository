node{
  stage('SCM checkout')
    git'https://github.com/Tapas-ui/GitRepository'
  }
  stage('compile-package')
    sh 'mvn package'
}
