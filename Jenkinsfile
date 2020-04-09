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
                sh 'docker build -t myimage:latest -f Dockerfile.dev .'            
            }
        }
        
        stage('Docker Test'){
            steps{
                sh 'docker run -i -p 3000:3000 myimage:latest'            
            }
        }

    }
}
        
        //docker build -t MYIMAGE -f Dockerfile.dev .
        //dockerfile{
        //    filename 'Dockerfile.dev'
         //   additionalBuildArgs '-t MYIMAGE'
       // }
