pipeline {
   agent any
   stages {
       stage ('Build') {
           bat "dir" // 如果jenkins安装在windows并执行这部分代码
           sh "pwd"  //这个是Linux的执行
       }
 
       stage ('Test') {
           bat "dir" // 如果jenkins安装在windows并执行这部分代码
           sh "echo ${JAVA_HOME}"  //这个是Linux的执行
       }
 
   }
}
