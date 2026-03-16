https://github.com/dhanush00018/dev1.git

pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git url: 'https://github.com/dhanush00018/dev1.git',
                    branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                sh 'chmod +x script.sh'
                sh './script.sh'
            }
        }
    }
}
