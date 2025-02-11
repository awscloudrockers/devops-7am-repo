node {
    stage "1. clone the repo"
    echo "this is the 1st stage cloning the repo"
    sh "yum install -y git"
    sh "rm -rf jenkins-cicd-docker"
    sh "git clone https://github.com/awscloudrockers/jenkins-cicd-docker.git "
    
    stage "2. build the job"
    echo "build job"
    sh "mkdir -p myfolder"
    
    stage "3 testing stage"
    echo "testing phase stage"
    sh "cd jenkins-cicd-docker"
    
    stage "4.deploying stage"
    echo "deployment"
    sh "ls -al"
    sh "date"
    sh "uptime"
    sh "date"
}
