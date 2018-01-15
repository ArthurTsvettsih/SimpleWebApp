node {
   stage('Preparation') {
      git 'https://github.com/ArthurTsvettsih/SimpleWebApp.git'
   }
   stage('Clean'){
      echo "I am cleaning"
      sh "./gradlew clean"
   }
   stage('Build') {
      echo "I am building"
      sh "./gradlew jar"
   }
   stage('Test') {
      echo "I am testing"
      sh "./gradlew test"
   }
}