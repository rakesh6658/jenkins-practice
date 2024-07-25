pipeline{
    agent {
        node { label 'agent1'}
    }
    options {
        ansiColor('xterm')
    }
     environment { 
        name = 'rakesh'
    
    }

stages{
    stage('build'){
        steps{
            echo 'welcome to jenkins'
            echo "my name is $name"
        }
    }

}
        stage('Example Username/Password') {
            environment {
                SERVICE_CREDS = credentials('ssh-auth')
            }
            steps {
                sh echo" $SERVICE_CREDS "
            }
        }

post{
    always{
        echo 'succcess or failure'
    }
    success {
        echo 'success  '
    }
}
}