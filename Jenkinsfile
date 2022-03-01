pipeline {
    agent { label 'agent_node' }
    stages {
        stage('Build') {
            steps {
                sh 'touch /tmp/aa.txt'
                sh '''
                    echo "this is jenkin pipeline test with ci" >> /tmp/aa.txt
                    ls -lah
                    echo 'jkin pipeline' >> /tmp/pipeline_with_node.txt
                '''
            }
        }
    }
}
