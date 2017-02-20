node {
  stage("Build") {
    git branch: "${BRANCH_NAME}", credentialsId: 'ssh github', url: 'git@github.com:org2jen/test2.git'
    sh "cat README.md"
  
  }
}
