node {
   stage('Preparation') {
      git 'https://github.com/coopcuk2/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}