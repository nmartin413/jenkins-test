pipeline {
    agent any

    triggers {
        pollSCM('H/5 * * * *')
    }

    stages {
        stage('say hi') {
                echo "hi"
            }
        }
    }
}
