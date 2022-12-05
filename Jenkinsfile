pipeline {
   agent any
   stages {
    stage ('vcs') {
        step {
            git branch: 'main' ,
            url: "https://github.com/madhu0018/Docker.git"
       }
    }
    stage ('package'){
        step{
            sh 'docker image build -t ntr:1.0 .'
        }
    }
 }


}