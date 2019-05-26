node {
    stage('Checkout git repo') {
      git branch: 'master', url: 'https://github.com/james5101/dotnetcore-api'
    }
    stage('build and publish') {
        bat "dotnet publish dotnetcoreapi.sln -c Release "
    }
}
