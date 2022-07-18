pipeline{
  agent { label 'linux' }
    stages{
      stage("git checkout")
      {
        steps{
           git url: 'https://github.com/akhilesh-007/jaipur123.git', branch: 'main'
        }
      }
      stage("docker pull")
      {
        steps{
        sh 'docker pull centos'
        }
      }
    }
}
  
