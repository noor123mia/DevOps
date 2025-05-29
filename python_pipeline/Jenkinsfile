pipeline {
    agent any
    environment {
        PATH = "C:\Users\PMYLS\anaconda3\Library\bin:$PATH"  // Adjust based on your system
    }
    stages {
        stage('Run Python with Conda') {
            steps {
                echo 'Running Python with Conda...'
                sh '''
                    source C:\Users\PMYLS\anaconda3\etc\profile.d\conda.sh
                    conda activate base
                    python script.py
                '''
            }
        }
    }
}
