    pipeline {

    agent any

    stages {
        stage('index') {
            steps {
	        sh 'cp -r index.html /var/www/html'
                sh 'cp -r dev.html /var/www/html'
                sh 'cp -r qa.html /var/www/html'
	        sh 'chmod -R 777 /var/www/html'

}
}

                
  

    }
}
