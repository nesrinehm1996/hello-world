node{
   stage('SCM Checkout'){
      git 'https://github.com/nesrinehm1996/Application-test'
   }
   stage('Compile-Package'){
      //get maven home path 
      def mvnHome = tool name: 'maven-3', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
}
