pipeline {
  agent any
  stages {
    stage('') {
      steps {
        git(url: 'params.git_repo', branch: 'master')
      }
    }
  }
  environment {
    docker_repository = 'azure-devops/spin-kub-demo'
    registry_url = 'https://t4vncyhb7qmjg.azurecr.io'
    git_repo = 'https://github.com/kranthiB/spin-kub-demo'
  }
}