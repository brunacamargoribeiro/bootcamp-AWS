# Aula 1 - Introdução a AWS
<div align="justify">
A AWS é uma plataforma de nuvem que oferece mais de 200 serviços, sendo uma infraestrutura completa para aplicações em todo o mundo. 

A operação da AWS conta com uma extensa" rede Global de data centers denominados Regiões e  Zonas de disponibilidade. 

:earth_americas: **Regiões (Regions)**

São áreas geográficas onde os data centers ficam alocados. Cada região é independente das outras fisicamente, ou seja, tem infraestrutura com energia, rede e segurança separados, mas logicamente são interligadas através de sua rede global privada de alta velocidade, que permite que seja feito repique dos dados ou integração de serviços entre as regiões (o que não ocorre automaticamente, é necessário que seja habilitado pelo administrador da conta). 

:earth_americas: **Zonas de disponibilidade (Availability Zones)**

São zonas dentro de cada região com toda a infraestrutura de data centers, cujo objetivo é garantir que o sistema seja mais confiável, resistente a falhas e rápido, mesmo que aconteçam problemas físicos. Com isso, é interessante que as aplicações estejam em mais de uma AZ. 

O modelo de negócio da AWS é pagamento por uso, por isso é extremamente importante ter uma arquitetura que faça uso dos recursos da melhor maneira possível, desligando o que não está sendo requisitado para não gerar custos excessivos. 

### :cloud_with_lightning: **Modelos de Computação em Nuvem**

Existem 3 modelos principais: 

:small_blue_diamond: **IaaS – Infrastructure as a Service (Infraestrutura como Serviço)**

:black_small_square: A nuvem fornece recursos básicos de TI: servidores, rede, armazenamento.  
:black_small_square: Você gerencia quase tudo: sistema operacional, aplicações, configurações.  
:black_small_square: A cloud só entrega a “base” (como se fosse um datacenter virtual). 

:small_blue_diamond: **PaaS – Platform as a Service (Plataforma como Serviço)**

:black_small_square: A nuvem fornece infraestrutura + plataforma pronta (sistema operacional, banco de dados, middleware).  
:black_small_square: Você só se preocupa com seu código e dados.  
:black_small_square: Não precisa gerenciar servidor, patch de segurança ou rede. 

:small_blue_diamond: **SaaS – Software as a Service (Software como Serviço)**

:black_small_square: É o nível mais alto.  
:black_small_square: A nuvem fornece o software pronto para usar, via internet.  
:black_small_square: Você não gerencia nada além do uso. 
</div>
