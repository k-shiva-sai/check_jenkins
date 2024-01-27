pipeline {
    agent any
    stages {
        stage ("first") {
            steps {
                script {
                    a=1
                    b=2
                    c = a+b
                    def s = "Shiva SAi konda"
                    def a = s.split(" ")
                    println a
                    println s
                    for (i in a) {
                        println "The element is ${i}"
                    }
                    if (c==3) {
                        println(c)
                        println(env.BUILD_ID)
                    }
                }
            }
        }
    }
}
