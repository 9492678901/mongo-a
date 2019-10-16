pipeline{
  stages{
  
    
    stage("checkout"){
        git 'https://github.com/9492678901/mongo-a'
    }
    stage("mongo run"){
        sh "/usr/local/bin/ansible-playbook -i dev.inventory mongo.yml"
    }
  }
}
