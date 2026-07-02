pipeline {
    agent any

    stages {
        stage('Deploy to Nginx') {
            steps {
                sh '''
                cp -r contact.html css fonts img index.html js /var/www/html/
                '''
            }
        }
    }
}
