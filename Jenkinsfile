

/* pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:2-alpine' 
                }
            }
            steps {
                sh 'python -m py_compile sources/add2vals.py sources/calc.py' 
                stash(name: 'compiled-results', includes: 'sources/*.py*') 
            }
        }
    }
}
 */

node {

    stage ('python') {
        sh 'sudo apt-get install python'

        echo 'installation'

        sh 'python --version'
    }







}
