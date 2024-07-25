pipeline{
    agent {
        node { label 'agent1'}
    }
    options {
        ansiColor('xterm')
    }
     environment { 
        name = 'rakesh'
        sh '"$name"'
    }

stages{
    stage('build'){
        steps{
            echo 'welcome to jenkins'
        }
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