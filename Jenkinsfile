pipeline {
    agent any
    parameters {
     string defaultValue: 'Vivek', description: 'Choose your name', name: 'name'
    }
    stages {
        stage ('parameter') {
            steps {
                echo "Hi ${name}, Welcome to Jenkins"
           }
        }
    }
}
