pipeline {
    agent any
    
    parameters {
     string defaultValue: 'Vivek\nVinay\nVijay\nSandeep\nDarshan', description: 'Choose your name', name: 'name'
    }
    stages {
        stage ('parameter') {
            steps {
                echo "Hi ${name} . Welcome to Jenkins"
            }
        }
    }
}
