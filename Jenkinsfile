pipeline {
     agent any
     stages {
         stage('Upload to AWS') {
              steps {
                  withAWS(region:'ap-southeast-2',credentials:'aws-static') {
                  sh 'echo "Uploading content with AWS credentials"'
                      s3Upload(pathStyleAccessEnabled: true, payloadSigningEnabled: true, file:'index.html', bucket:'ud-nd-project-3')
                  }
              }
         }
     }
}
