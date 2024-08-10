pileline {
    agent any

    tools {
        maven "maven3.9.6"
    }
    
    stages {
        stage ('Git clone') {
            steps {
                git branch: 'master', url: 'https://github.com/Ibrahim-Sahabi/EcommerceApp.git'
            }
            
        }
    }
}