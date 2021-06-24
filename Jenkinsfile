#!/usr/bin/env groovy

pipeline {


//     agent { label 'my-defined-label' }
        agent any
    stages {
        
        stage('Stage 1') {
            steps {
                echo 'Hello world!' 
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'npm test'
            }
        }
    }
        
//         agent none
//     stages {
//         stage('Example Build') {
//             steps {
//                 echo 'Hello World'
//             }
//         }
//         stage('Example Deploy') {
//             agent {
//                 label "some-label"
//             }
//             when {
//                 beforeAgent true
//                 branch 'master'
//             }
//             steps {
//                 echo 'Deploying'
//             }
//         }
//     }
        
        
//         agent any
//     stages {
//         stage('Example Build') {
//             steps {
//                 echo 'Hello World'
//             }
//         }
//         stage('Example Deploy') {
//             when {
//                 branch 'production'
//             }
//             steps {
//                 echo 'Deploying'
//             }
//         }
//     }
}
