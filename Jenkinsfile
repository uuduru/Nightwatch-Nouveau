pipeline {
     agent {
        docker {
            image 'node:latest'
            args '-p 3000:3000'
        }
    }

   tools {nodejs 'NodeJs'}

    stages {
        stage('Build') {
            steps {
                // Run Maven on a Unix agent.
                //sh 'npm i @cucumber/cucumber --save-dev --force'
                sh "npx nightwatch"
            }
        }
    }
}
