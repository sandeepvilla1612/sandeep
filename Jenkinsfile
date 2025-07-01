pipeline {
    agent any

    stages {
        stage('Clone HTML Template') {
            steps {
                echo 'Cloning website files from GitHub...'
                git url: 'https://github.com/sandeepvilla1612/sandeep.git', branch: 'main'
            }
        }

        stage('Deploy to Apache') {
            steps {
                echo 'Copying files to Apache web folder...'
            }
        }
    }
}

