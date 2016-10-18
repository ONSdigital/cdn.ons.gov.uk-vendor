#!groovy

node {
    stage('Checkout') {
        checkout scm
    }

    stage('Bundle') {
        sh "aws s3 sync --acl public-read vendor s3://${env.S3_CDN_BUCKET}/vendor/"
    }
}
