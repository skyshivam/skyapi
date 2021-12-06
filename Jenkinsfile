pipeline {
  agent any
  stages {

     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleVersion=4.4.0 -Dusername=skysky -Dpassword=SKY-a1888 -DapplicationName=cicd_api18 -Denvironment=Sandbox -Dworkers=1 -DworkerType=Micro -DmuleDeploy"
            echo "deploy success"           
      }
    }
}
}