pipeline {
    agent any
    stages {
        stage ("first") {
            steps {
                script {
                    a,b = [1,2]
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
