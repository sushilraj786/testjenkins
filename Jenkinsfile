pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        script {
          sh "javac HelloWorld.java"
          echo "Compiled Successfully"
          sh "java HelloWorld"
        }
      }
    }
  }
}
