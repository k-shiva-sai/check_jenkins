pipeline {
    agent any
    parameters {
        string (name: 'name', defaultValue: 'shiva', description: 'this is the name field')
        string (name: 'age', defaultValue: '10', description: 'Please give youe age')
    }
    stages {
        stage ("first") {
            steps {
                script {
                    a=1
                    b=2
                    c = a+b
                    def s = "Shiva SAi konda"
                    def a = s.split(" ")
                    def l = s.tokenize(" ")
                    println a
                    println s
                    println l
                    for (i in a) {
                        println "The element is ${i}"
                    }
                    println "the age is " params.age+10
                    if (c==3) {
                        println(c)
                        println(env.BUILD_ID)
                    }
                }
            }
        }
    }
}
