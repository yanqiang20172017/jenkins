pipeline {
   agent {
        node {
            label 'k8s-node2'
            customWorkspace "${env.JOB_NAME}/${env.BUILD_NUMBER}"
        }
   }
   stages {
       stage ('Build') {
           steps {
              sh "pwd"  //这个是Linux的执行
           }
       }
 
       stage ('Test') {
           steps {
              sh "echo hello"  //这个是Linux的执行
           }
       }
 
   }
}
