node {

    build 'hpl-11copy'


        parallel 'eleven':{
            node {
                stage('11'){
                    build 'hpl11Copied'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'twelve':{
            node {
                stage('12') {
                    build 'hpl12Copied'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'thirteen':{
            node {
                stage('13') {
                    build 'hpl13Copied'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'fourteen':{
            node {
                stage('14'){
                    build 'hpl14Copied'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'fifteen':{
            node {
                stage('15'){
                    build 'hpl15Copied'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }, 'sixteen':{
            node {
                stage('16'){
                    build 'hpl16Copied'
                    archiveArtifacts allowEmptyArchive: true, artifacts: '*.standardOutput, *.errorLog', excludes: null
                }
            }
        }
}