pipeline {
    agent any
    stages {
        stage("Create important files") {
            steps {
                sh """
                    touch importantfile1
                    touch importantfile2
                    touch importantfile3
                """
            }//steps
        }//stage
        stage("Run hellowrld") {
            steps {
                sh """
                    python helloworld.py
                    """
            }//steps
        }//stage
        stage("Run game.py") {
            steps {
                sh """
                    pyton game.py
                """    
            }//steps
        } //stage
    }//stages
}//pipeline