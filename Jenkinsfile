pipeline{
    agent any 
    stages{
        stage('stage1'){
            steps{
                echo 'Stage1'               
            }
        }
        stage('Docker Build'){
            steps{
                sh 'docker-compose up --build'            
            }
        }
        
    }
}
        
        //docker build -t MYIMAGE -f Dockerfile.dev .
        //dockerfile{
        //    filename 'Dockerfile.dev'
         //   additionalBuildArgs '-t MYIMAGE'
       // }
