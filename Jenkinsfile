node {
   stage('Preparation') {
      git 'https://github.com/coopcuk2/SimpleWebApp'
   }
   stage('Build') {
      bat "./gradlew clean test"
   }
}