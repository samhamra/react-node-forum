node {
    def app
    checkout scm
    stage('Build') { 
      app = docker.build("nodejs-test:${env.BUILD_ID}", "-f Dockerfile.test") 
    }
}
