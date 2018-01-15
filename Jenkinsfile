node {
   stage('Preparation') {
      git 'https://github.com/ArthurTsvettsih/SimpleWebApp.git'
   }
   stage('Build') {
      echo "I am building"
   }
   stage('Test') {
      echo "I am testing"
      sh "./gradlew clean test"
   }
}