node {
    stage('Checkout git repo') {
      git branch: 'master', url: 'https://github.com/james5101/dotnetcore-api'
    }
    stage('build and publish') {
        sh(script: "dotnet publish dotnetcoreapi.sln -c Release ", returnStdout: true)
    }
}