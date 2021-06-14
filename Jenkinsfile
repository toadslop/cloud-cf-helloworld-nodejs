@Library('piper-lib-os') _
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelienEnvironment script:this
    }

    stage('build') {
        mtaBuild script:this
    }
}