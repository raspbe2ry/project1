pipeline {
    agent any
    
    stages {
        stage('Copy file') {
            steps{
                script {
                    def sourceFile = "${WORKSPACE}\\myapp.py"
                    def desktopDir = "C:\\Users\\nemanja\\Desktop"  // Adjust path for your system
                    
                    // Copy the file using 'bat' step and 'copy' command
                    bat "copy ${sourceFile} ${desktopDir}"
                }
            }
        }
    }
}
