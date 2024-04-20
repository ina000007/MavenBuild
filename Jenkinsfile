// @Library(["sharedLib"]) _

// mavenBuild(
//   gitURL : "https://github.com/ina000007/MavenBuild",
//   productType : "maven",
//   pomfileName : "pom.xml"
// )

pipeline {
 agent any
 stages {
   stage('init') {
      scripts {
        library "sharedLib"
      }
   }
   stage('Build'){
     steps {
       echo "build stage"
     }
   }
 }
}
