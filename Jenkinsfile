node {
   stage('Preparation') {
      git "https://github.com/dmitrykos/SimpleWebApp.git"
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
   stage('Deploy') {
      git "push https://git.heroku.com/lit-wave-60289.git master"
   }
}