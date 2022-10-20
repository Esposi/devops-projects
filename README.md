# devops-projects
Estudos pessoais DevOps


  Este projeto são configurações basicas e resumidas de um ambiente basico utilizando ferramentas e conceitos DevOps. 
O objetivo é reproduzir um ambiente completo utilizando Docker, Kubernets, Jenkins, Terraform e outros. 
  A utilização do Kubernets envolve o 'kubectl' e o 'k3d' para usar clusters+pods+containers.

-RODANDO KUBERNETS+DOCKER

  1- Estando no diretorio '.\kubernets' executar o comando: 'kubectl apply -f .\deployment.yml'
  2- Utilizar 'kubectl get all' para conferir a criação dos containers+pods+clusters
  3- O acesso é feito pelo service configurado em 'deployment.yml'. Para acesso apontar em 'localhost:30000' conforme configurado.
