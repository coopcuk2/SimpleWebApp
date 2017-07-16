node {
   stage('Preparation') {
      git 'https://github.com/coopcuk2/SimpleWebApp'
   }
   stage('Build') {
      if(isUnix()){
        sh "./gradlew clean test"
      }
      else{
        bat "./gradlew clean test"
      }
   }
}