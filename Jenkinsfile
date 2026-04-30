node {
    stage('Preparation') { 
        git branch: 'main', url: 'https://github.com/spring-projects/spring-petclinic.git'
    }
    stage('Build') {
        sh 'mvn package'
    }
}
