node {

    stage('Checkout') {
        echo 'Checking out code from GitHub'
    }

    stage('Build') {
        echo 'Compiling Java Program'
        bat 'javac HelloWorld.java'
    }

    stage('Run') {
        echo 'Running Java Program'
        bat 'java HelloWorld'
    }

}
