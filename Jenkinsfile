node {
     stage('SCM CHECKOUT'){
             git ' https://github.com/gollasreekanth/studentwarpractice '
     }
     stage('Compile-Package'){
            def mvnHOME =  tool name: 'maven-3.8.6', type: 'maven'
          sh "${mvnHOME}/bin/mvn package"
     }
     }
