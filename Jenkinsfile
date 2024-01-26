pipeline {
    agent any
    stages {
        stage ("first") {
            steps {
                script {
                    a=1
                    b=2
                    var c = a+b
                    if (c==3) {
                        println(c)
                        println(${env.BUILD_ID})
                    }
                }
            }
        }
    }
}
