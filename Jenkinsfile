@Library('piper_lib_os') _
pipeline {
    agent any
    stages{
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
  }
}
