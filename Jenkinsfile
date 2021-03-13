pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "compile java code"
        sh "javac HelloWorld.java"
        echo "Compiled Successfully"
        sh "java HelloWorld"
      }
    }
  }
}
