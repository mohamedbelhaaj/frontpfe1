pipeline {

    agent { node { label 'prod' } }
    
    stages {


        stage('Build image Ms Note') {
            
            steps { 
            dir ('ProjetBack') {
                 sh ' docker build -t front/sysinfo  . && docker run -d -it -p 80:80/tcp --name sysinfo front/sysinfo:latest'
               
                         }
                      

			   
     
            }
        }
}


   
   
}