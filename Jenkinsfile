@Library('piper-lib-os@v1.34.0') _
pipeline {
    agent any
    stages{
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage(‘build’){
    steps{
        mtaBuild script: this,
        mtaBuildTool: 'cloudMbt'               
    }
    }
  }
}
