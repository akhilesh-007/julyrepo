pipeline{
  agent any
    stages{
      stage("git checkout")
      {
        steps{
           git 'https://github.com/akhilesh-007/jaipur123.git'
        }
      }
      stage("docker pull")
      {
        steps{
          docker 'docker pull centos'
        }
      }
    }
}
  
