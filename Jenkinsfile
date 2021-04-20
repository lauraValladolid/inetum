//Pipeline Declarativo (siempre comienza por pileline)
pipeline {
    // Ejecutar en cualquier agente (nodo)
    agent any
    
    // Fases del trabajo
    stages {
        // Fase individual (contendor logico)
        stage('Build') {
            //Pasos de la fase
            steps {
                echo 'Building GIT....'
            }
        }
        
        stage('Test') {
            //Pasos de la fase
            steps {
                echo 'Testing GIT...'                
            }
        }
        
         stage('Deploy') {
            //Pasos de la fase
            steps {
                echo 'Deploying GIT...'
            }
        }
    }
}
