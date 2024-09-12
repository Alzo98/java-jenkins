node {
    stage('Clone') {
        git branch: 'main', url: 'https://github.com/Alzo98/java-jenkins.git'

    }
    stage('Build') {
        sh '''
            javac Main.java
        '''
    }
    stage('Run') {
        sh '''
            java Main
        '''
    }
}
