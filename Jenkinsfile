pipeline {
     agent any

   tools {nodejs 'NodeJs'}

    stages {
        stage('Build') {
            steps {
                // Run Maven on a Unix agent.
                sh 'npm install'
                sh "npx nightwatch"
            }
        }
    }
}
