pipeline{
    agent {
        node { label 'agent1'}
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