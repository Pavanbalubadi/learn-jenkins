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
  stages {
    stage('pavan') {
      when {
        branch 'production'
      }
      steps {
        echo 'Deploying'
      }
    }

    stage('kumar') {
      steps {
        echo 'Deploying'
      }
    }
    stage('balubadi') {
          steps {
            echo 'Deploying'
          }
        }

  }
}