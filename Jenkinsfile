pipeline {
  agent any
  stages {
    stage('build test') {
      parallel {
        stage('build test') {
          steps {
            echo 'hello build'
            echo 'hello build'
          }
        }
        stage('test username') {
          steps {
            sh '''#/usr/bin/bash

whoami
date ; hostname

sh /var/lib/jenkins/workspace/print.sh'''
          }
        }
      }
    }
  }
}