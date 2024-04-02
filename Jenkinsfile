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
        stage('pavan') {
                    steps {
                        echo 'Hello Pavan'
                    }
                }
        stage('kumar') {
                       steps {
                            echo 'Hello Pavan'
                        }
    }


}



