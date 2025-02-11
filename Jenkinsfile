pipeline {
    agent any
    
    stages {
        stage ("1.update the system") {
            steps {
                sh "sudo mkdir -p tree"
                sh "touch abc.txt"
            }
        }
        
        stage ("2. creating folder") {
            steps {
                sh "mkdir -p incoming"
                sh "mkdir -p outgoing"
                echo "files"
            }
        }
        
        stage ("3.verify the files") {
            steps {
                sh "ls -al"
                sh "date"
                sh "cal 2025"
                sh "last"
            }
        }
    }
}
