pipeline{
  agent any
  stages{
    stage("checkout"){
      steps{
        git 'https://github.com/9492678901/mongo-a'
      }
    }
    stage("mongo run"){
      steps{
        sh "/usr/local/bin/ansible-playbook -i dev.inventory mongo.yml"
      }
    }
  }
}
