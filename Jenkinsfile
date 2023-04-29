pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
        ansiblePlaybook credentialsId: '44eb377f-0271-40f6-9457-249a881ea435', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
