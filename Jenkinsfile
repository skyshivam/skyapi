pipeline {
  agent any
  stages {

     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleVersion=4.4.0 -Dusername=aniket_apisero15 -Dpassword=Aniket@15_apisero -DapplicationName=cicdAniketPractice -Denvironment=Sandbox -Dworkers=1 -DworkerType=Micro -DmuleDeploy"
            echo "deploy success"           
      }
    }
}
}