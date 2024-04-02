// Jenkinsfile (Declarative Pipeline)

// pipeline {
//    agent { node { label 'workstation' } }
//      options {
//            ansiColor('xterm')
//        }
//     stages {
//         stage('Hello') {
//             steps {
//                 echo 'Hello Pavan'
//             }
//         }
//     }
// }

pipeline {
   agent { node { label 'workstation' } }
     options {
           ansiColor('xterm')
       }
    stages {
        stage('Hello') {
        when {
                branch 'production'
              }
            steps {
                echo 'Hello Pavan'
            }
        }
    }

    stages {
            stage('pavan') {

                steps {
                    echo 'Hello Pavan'
                }
            }
        }

        stages {
                stage('balubadi') {
                    steps {
                        echo 'Hello Pavan'
                    }
                }
            }
}



