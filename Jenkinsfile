node {

    stage('Checkout git repo') {
      git branch: 'master', url: 'https://github.com/james5101/dotnetcore-api'
    }
  stage('Clean') {
   steps {
    bat 'dotnet clean'
   }
  }
  stage('Build') {
   steps {
    bat 'dotnet build --configuration Release'
   }
  }
  
}