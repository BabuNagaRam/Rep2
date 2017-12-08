

properties([
   [$class: 'GithubProjectProperty',
   displayName: '',
   projectUrlStr: 'https://github.com/BabuNagaRam/Rep2/'],
    pipelineTriggers([
   
   upstream(
     threshold: 'SUCCESS',
     upstreamProjects: 'https://github.com/BabuNagaRam/Rep1/.git')
   ])
])
   pipeline {
   agent any 

   stages {
       stage('Build') {
           steps {
               sh 'pwd'
           }
       }
       stage('Test'){
           steps {
               sh 'java -version'
               
           }
       }
       stage('Deploy') {
           steps {
               sh 'ls'
               sh 'pwd'
           }
       }
   }
}
