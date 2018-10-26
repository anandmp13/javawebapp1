pipeline { 
 agent {dockerfile true }    
   stages {
        stage('DEV') { 
            steps { 
                echo 'DEV' 
		sh 'docker build -t javatestapp:v1 .'
            }
        }
        stage('Test'){
            steps {
           echo 'QA'     
            }
        }
        stage('Deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
