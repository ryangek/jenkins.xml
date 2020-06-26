pipeline {
  agent any
 
  tools {
      nodejs "node"
  }
  
  stages {
      stage('Console Hello World') {
          steps {
            input message: 'Are you approve to continue ?', submitter: 'kimjaeha'
          }
      }
      stage('cmd'){
          steps{
              bat 'dir'
            //   bat 'copy .\\jenkins.xml C:\\Program Files (x86)\\Jenkins\\jenkins.xml'
          }
      }
  }
}