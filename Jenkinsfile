 pipeline { 
     agent any 
  
     stages { 
         stage('Dev') { 
             steps { 
                 echo 'I am in dev' 
                 sh 'docker --version' 
             } 
         } 
         stage('Staging') { 
             steps { 
                 echo 'I am in staging' 
                 sh 'git --version' 
                 sh 'php --version' 
                 sh 'mvn -v' 
                 sh 'java --version' 
             } 
         } 
         stage('Prod') { 
             steps { 
                 echo 'I am in prod' 
                 sh 'docker --version' 
             } 
         } 
     } 
 }
