node {
    stage('checkout') {
        git 'https://github.com/demonicmc/maven-hello-world/edit/master'
    }
        
    stage('build') {
        sh 'mvn clean install'
    }
}
