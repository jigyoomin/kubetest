#!/usr/bin/groovy


def label = "docker"
podTemplate(label: label) {
    node(label) {
        stage('Run shell') {
            sh 'echo hello world'
            sh 'sleep 30'
            sh 'docker ps'
        }
    }
}