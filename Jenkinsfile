// Pipeline declarativo
pipeline {
    
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases
    stages {
        stage("Fase 1 - Build") {
            // Pasos de la fase
            steps {
                echo "Fase 1 - Paso 1";
            }
        }
        stage("Fase 2 - Testing") {
            // Pasos de la fase
            steps {
                
                echo "Test Unitarios...";
                echo "Test Integración...";
                echo "Test Aceptación...";
                
            }
        }
        stage("Fase 3 - Deploy") {
            // Passos de la fase
            steps {
                echo "Desploying artifact!!!!";
            }
        }
    }
}
