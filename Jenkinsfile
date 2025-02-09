pipeline {
    agent any
    
    stages {
        stage('Copy file') {
            steps{
                script {
                    def sourceFile = "${WORKSPACE}\\myapp.py"
                    def desktopDir = "C:\\Users\\nemanja\\Desktop"  
                    
                    bat "copy ${sourceFile} ${desktopDir}"
                }
            }
        }
    }
}
