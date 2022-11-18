pipeline {
    agent any
parameters {
  choice choices: ['vivek', 'vinay', 'vijay'], description: 'choose your name', name: 'name'
}
    stages {
        stage ('parameter') {
            steps {
                echo "Hi ${name}, Welcome to Jenkins"
           }
        }
    }
}
