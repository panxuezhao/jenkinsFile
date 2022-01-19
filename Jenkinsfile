pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('world') {
            steps {
                echo 'zhangsan is lisi gege'
            }
        }
        stage('123') {
            steps {
                echo 'niuniuniu'
            }
        }
        stage('touch txt') {
            steps {
                sh '''
            touch txt1
            if [[ $? -eq 0 ]];then
               echo "ok"
            else
              echo "error"
            fi'''
            }
        }
    }
}
