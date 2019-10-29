pipeline {
    agent any

    stages {
        stage('Create') {
            steps {
                echo 'Create..'
            }
        }
        stage('read') {
            steps {
                echo 'Read..'
            }
        }
        stage('Delete') {
            steps {
                echo 'Delete....'
            }
        }
    }
}
