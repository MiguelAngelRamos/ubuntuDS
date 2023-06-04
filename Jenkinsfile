pipeline {
    agent any

    tools {
        gradle "gradlejenkins"
    }

    stages {
        stage("tareas de limpieza") {
            steps {
                git 'https://github.com/MiguelAngelRamos/SeleniumDriver.git'
                sh 'gradle clean'
            }
        }
        stage("imprimo") {
            steps {
                echo "stage"
            }
        }
    }
}