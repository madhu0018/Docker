pipeline {
   agent any
   stages {
    stage ('vcs') {
        step {
            git branch: 'master' ,
            url:
       }
    }
    stage ('package'){
        step{
            sh 'docker image bulid -t ntr:1.0 .'
        }
    }
 }


}