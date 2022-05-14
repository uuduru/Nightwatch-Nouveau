pipeline {
    agent any

   tools {nodejs 'NodeJs'}

    stages {
        stage('Build') {
            steps {
                // Run Maven on a Unix agent.
                sh "npx nightwatch"
            }
        }
    }
}
