pipeline { 
 agent {dockerfile true }    
   stages {
        stage('DEV') { 
            steps { 
                echo 'DEV' 
		sh 'sudo ocker build -t javatestapp:v1 .'
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
