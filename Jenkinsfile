pipeline {
    agent any
    stages {
        stage('Example Build') {
            
            steps {
                echo 'Hello,this is a build step'
                
            }
        }
        stage('Example build') {
            
            steps {
                catchError(buildResult: 'SUCCESS', stageResult: 'FAILURE'){
                echo 'Hello,this is build step'
                sh 'exit 1'
                }
            }
        }
        stage('Example deploy') {
            
            steps {
                echo 'Hello,this is deploy step'
    }
}
}
}
