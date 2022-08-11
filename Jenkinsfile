pipeline
{
  agent any
  stages {
   stage('Build carona  app'){
   steps {
         bat 'mvn clean install'
         }}
         
         
    stage('Deploy carona app into CloudHub'){
   steps {
         bat 'mvn package deploy -DmuleDeploy -Dusername=Legend2'
         }}
         
         
         
         
  }
}