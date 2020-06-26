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
              bat 'dir && copy /Y .\\jenkins.xml C:\\Program Files (x86)\\Jenkins\\jenkins.xml'
              bat 'cd C:\\Program Files (x86)\\Jenkins\\ && dir'
          }
      }
  }
}