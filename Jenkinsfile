pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh '''echo "hello world"
'''
        git(url: 'https://gitee.com/yang-xiao/iosched.git', branch: 'master', credentialsId: 'git')
      }
    }

    stage('step2') {
      steps {
        sh 'echo "step 2"'
      }
    }

  }
}