# Aula 2 - Fundamentos essenciais
<div align="justify">

Os principais conceitos e serviços da AWS são:



:purple_circle: **1. Regiões e Zonas de Disponibilidade** 

Onde os recursos ficam fisicamente. As regiões são independentes e as zonas de disponibilidade dão redundância e alta disponibiliade.


:purple_circle: **2. Modelos de Computação em Nuvem**

IaaS, PaaS, SaaS → Tipo de solução de acordo com a necessidade.  
Exemplo: EC2 (IaaS), RDS (PaaS), WorkMail (SaaS). 

:purple_circle: **3. Computação**  
EC2: máquinas virtuais.  
Lambda: serverless (roda código sob demanda).  
ECS/Fargate: containers.  
Computação está relacionado a força de processamento. 

:purple_circle: **4. Armazenamento**  
S3: objetos (data lake, arquivos).   
EBS: blocos (discos para EC2).  
EFS: sistema de arquivos compartilhado.  
Gravar e acessar dados é central em quase todo sistema. 

:purple_circle: **5. Bancos de Dados**  
RDS: relacional (SQL).  
DynamoDB: NoSQL.   
Redshift: data warehouse.   
Para cada tipo de dado é utilizado um serviço diferente. 

:purple_circle: **6. Rede**  
VPC (Virtual Private Cloud): rede virtual.  
Subnets, roteadores, gateways: conceitos básicos de como os recursos se conectam.   
Fundamental para segurança e comunicação. 

:purple_circle: **7. Segurança**  
IAM: identidade e permissões.  
MFA, roles, policies: quem pode acessar o quê.   


:purple_circle: **8. Monitoramento e Custos**  
CloudWatch: métricas e logs.   
CloudTrail: auditoria (quem fez o quê).  
Cost Explorer: controle de gastos.   
Saber monitorar é tão importante quanto saber criar recursos. 


:purple_circle: **9. Arquitetura de Alta Disponibilidade**  
Uso de múltiplas AZs e balanceadores de carga (ELB).   
Auto Scaling para crescer ou reduzir capacidade automaticamente.   
Resiliência e escalabilidade são fundamentos da nuvem. 
</div>