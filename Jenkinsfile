@Library('piper-lib-os@master')
node() {
    stage('prepare') {
        checkout scm
        setupCommonPipelineEnvironment script:this
    }
    stage('build') {
    mtaBuild script: this
}
}
