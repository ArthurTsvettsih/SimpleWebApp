node {
   stage('Preparation') {
      git 'https://github.com/ArthurTsvettsih/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}