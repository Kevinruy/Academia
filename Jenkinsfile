pipeline {
    agent any
    stages {
        stage('download') {
            steps {
                sh '''
                ls
                echo "hola, ¿Cómo estás amigo?"

                '''
            }
        }
        stage('compilar') {
            steps {
                sh '''
                pwd
                echo "hola mundo"
                '''
            }
        }
        stage('Testing'){
            steps{
                sh '''
                echo "Tareas de testing"
                '''
                }
         }
                
        stage('deployar') {
            steps {
                sh '''
                echo "hola mundo"
                '''
            }
        }
    }
}
