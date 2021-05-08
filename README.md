# Kubernetes  

## IMPACTA MBA ENGENHARIA DE SOFTWARE  
## ESD21 - Infrastructure and Cloud Computing 
---------------------------------------------------------------------------------------------------------------

## Exercício Aula 04

## Aluno: Edson João da Rocha

## Objetivo: Subir dois pods, nginx e mysql, mapeando a porta 80 do nginx para acesso externo ao cluster e permitir que o contêiner do nginx tenha comunicação de rede no contêiner mysql pela porta 3306. A atividade pode ser feita localmente (minikube), AKS (Azure), EKS (AWS) ou no GKE (GCP). Se quiser criar o cluster nuvem Kubernetes com Terraform é opcional. 

Para criar os pods e o service:  
    1 - Executar o comando "kubectl apply -f pods"  
    2 - Executar o comando "kubectl apply -f services"

*Obrigatório ter o Kubernetes configurado em ambiente de nuvem.  

Para acessar o pod nginx:   
IP: [IP_PUBLICO_NO_SEU_PORTAL_AZURE] Porta: 80  

Obs: Os testes foram feitos utilizando o minikube para windows
