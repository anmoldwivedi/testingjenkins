pipeline {
  agent any
  stages {
    stage('execution') {
      steps {
        cmakeBuild(cleanBuild: true, installation: '/usr/bin', buildDir: 'build')
      }
    }

  }
}