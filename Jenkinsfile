
node {
  stage('Run Ansible'){
  ansiblePlaybook become: true, becomeUser: 'root', credentialsId: 'ansadmkey1', installation: 'MyAnsible', inventory: 'hosts', playbook: 'webinstall.yml'
  }
}
