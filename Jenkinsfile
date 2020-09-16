node {
    stage('Checkout') {
       git credentialsId: 'github', url: 'https://github.com/saiteja4167/webapp.git' 
    }
    stage('BUILD') {
    echo "mvn"
    }
    stage('unit-test') {
    echo "u it-test"
    }
    stage('int-test') {
    echo "int-test"
    }
    stage('deploy') {
    echo "deploy"
    }
}
