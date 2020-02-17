node {
   stage('Preparation') {
      git 'https://github.com/dmitrykos/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}