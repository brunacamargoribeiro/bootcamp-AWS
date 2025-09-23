# Aula 4 - Primeiros passos

:pushpin: **Entendendo e conhecendo o IAM**

O **IAM (Identity and Acess Management)** é o serviço da AWS para gerenciamento de identidades (usuários, grupos, funções) e controle de acessos. 

Através dele é possível dar permissões específicas para quem pode ter acesso a que. A criação desses usuários pode ser feita sem o uso da conta root (deve-se usar a conta administrador criada anteriormente) e lhe são atribuídas políticas (regras) de acordo com a função a ser desempenhada. 

Só devem ser dados os acessos necessários a cada usuário (princípio do **menor privilégio**). 


:pushpin: **Formas de acesso**

* **Console AWS**

É a forma mais visual e simples (via navegador), boa para iniciantes. 
 

* **AWS CLI**

É o acesso através de linha de comando (instalada no computador), útil para automação, scripts e quem prefere fazer o uso do terminal. 

 
* **CloudShell** 

É como a AWS CLI, mas já embutida no navegador, sem a necessidade de instalação. Com o CloudShell pode-se executar os comandos diretamente, sem configurar o computador. 

:pushpin: **Criação de grupos no IAM**

Grupos são conjuntos de usuários que compartilham o mesmo perfil e permissões, sendo muito útil para a organização dos usuários e facilidade na administração. Através dos grupos, ao invés de dar as permissões a cada usuário individualmente, a atribuição é feita ao grupo e todos a herdam. 

**Exemplo prático**: 

Grupo **Desenvolvedores** → pode criar/editar EC2 e S3. 

Grupo **Analistas de Dados** → pode acessar S3 e rodar consultas no Athena. 

Grupo **Financeiro** → só pode ver relatórios de uso e billing. 


É possível fazer o cadastro de usuários em massa através de script. 