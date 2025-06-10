pipeline {
    agent any

    tools{
        maven 'maven'
    }

    stages {
        stage("clean") {
            steps {
                echo "clean done"
            }
        }

        stage("validate") {
            steps {
                echo "validate done"
            }
        }

        stage("compile") {
            steps {
                echo "compile done"
            }
        }

        stage("test") {
            steps {
                echo "test"
            }
        }

        stage("package") {
            steps {
                echo "package"
            }
        }
    }
}
