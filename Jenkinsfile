pipeline {
  agent {
    docker {
      image 'docker.io/androidsdk/android-30'
    }

  }
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