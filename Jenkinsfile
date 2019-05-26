node {

    stage('Checkout git repo') {
      git branch: 'master', url: 'https://github.com/james5101/dotnetcore-api'
    }
  stage('Clean') {
   
    bat 'dotnet clean'
   
  }
  stage('Build') {
   
    bat 'dotnet build --configuration Release'
   
  }

  stage('Tests'){
    bat 'dotnet test'
  }
  
}