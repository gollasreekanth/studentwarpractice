node {
     stage('SCM CHECKOUT'){
     git ' https://github.com/gollasreekanth/studentwarpractice '
     }
     stage('Compile-Package'){
     tool name: 'maven-3.8.6', type: 'maven'
     sh 'mvn package'
     }
     }
