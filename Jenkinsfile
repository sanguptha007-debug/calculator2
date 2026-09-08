pipeline {
    agent any

    options {
        skipDefaultCheckout(true)
    }

    stages {

        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                bat '"C:\\Users\\sanph\\AppData\\Local\\Python\\bin\\python.exe" calculator2.py'
            }
        }
    }
}
