pipeline {
    agent any

   tools {nodejs 'nodejs'}

    stages {
        stage('Build') {
            steps {
                // Run Maven on a Unix agent.
                sh "npx nightwatch"
            }
        }
    }
}
