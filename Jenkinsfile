pipeline {
     agent any

   tools {nodejs 'NodeJs'}

    stages {
        stage('Build') {
            steps {
                // Run Maven on a Unix agent.
                //sh 'npm run node_modules\cucumber\bin\cucumber-js update'
                sh "npx nightwatch"
            }
        }
    }
}
