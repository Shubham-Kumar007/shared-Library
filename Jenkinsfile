@Library('sharedlib-demo')_

pipeline {
    agent any

    stages {
        stage('Demo') {
            steps {
                welcome("Shubham Kumar")
                script{
                 calculator.add(10,50)
                }
   
            }
        }
    }
}
