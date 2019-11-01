pipeline {
    agent any
    stages {
        stage('first stage') {
            steps {
                build 'hello-world'
                echo "hello world completed";
            }
        }
        stage('second stage') {
            steps {
                build 'hello_2nd_project'
                echo "2nd project completed";
            }
        }
        stage('third stage') {
            steps {
             build 'hello_test_after_2nd'
            echo "third completed";   
            }
        }
    }
}
}