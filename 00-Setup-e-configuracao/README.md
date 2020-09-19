# Setup e Configuração de ambiente

1. Instale AWS CLI
2. Faça uma credencial na sua conta AWS designada e coloque no ~/.aws/credentials da sua máquina
3. Instale terraform
4. Instale serverless framework
   1. `npm install -g serverless`
5. Necessário Python3.6 ou superior
6. Instale ViertualEnv e utilize para todos os exercicios que envolvem python
   1. `pip3 install virtualenv`
   2. `virtualenv ~/venv`
   3. `source ~/venv/bin/activate`
7. Instale o aplicativo 'jq', caso esteja em um linux familia Debian o comando é:
   1. `sudo apt  install jq -y`
8. Instale o plugin que vamos utilizar para mexer com cloudformation:
   1. `npm install -g cfn-create-or-update`
9. Instale ansible, caso esteja em um linux familia Debian:
   ``` shell
      sudo apt-get update -y
      sudo apt-add-repository ppa:ansible/ansible
      sudo apt-get update -y
      sudo apt-get install ansible -y 
    ```