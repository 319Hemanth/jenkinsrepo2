node {
    stage('Checkout') {
        // Checkout your source code from your version control system (e.g., Git)
        checkout scm
    }
    
    stage('Compile') {
        // Compile your Java code
        sh 'javac HelloWorld.java'
    }
    
    stage('Run') {
        // Run your Java program
        sh 'java HelloWorld'
    }
}

