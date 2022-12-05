pipeline {
   agent any
   stages {
    stage ('vcs') {
        step {
            git branch: 'master' ,
            url: "https://github.com/madhu0018/Docker.git"
       }
    }
    stage ('package'){
        step{
            sh 'docker image bulid -t ntr:1.0 .'
        }
    }
 }


}