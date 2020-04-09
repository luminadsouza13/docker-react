pipeline{
    agent{
        //docker build -t MYIMAGE -f Dockerfile.dev .
        dockerfile{
            filename 'Dockerfile.dev'
            additionalBuildArgs '-t MYIMAGE'
        }
    }
}
