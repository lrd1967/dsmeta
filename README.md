# repositório dsmeta  

## Projeto do Curso da Semana Spring React DevSuperior  

Projeto do Prof. Nélio Alves da escola DevSuperior para a Semana Spring React.  
O projeto consiste em uma tela renderizada por um frontend React, hospedada no Netfily,  
que acessa uma API em Spring Boot hospedada no Heroku (at[e 28/11/2022 quando deixa de permitir serviços grátis).  
O sistema ainda consta com envio de SMS através da plataforma Twilio.  
A base de dados é fixa no banco H2.


### Configuração

## GIT

Obs: como já havia uma configuração global para o meu usuário/email do ambiente da empresa em que trabalho  
foi necessário criar credenciais locais no diretório dos arquivos do curso:  
(<https://stackoverflow.com/questions/42318673/changing-the-git-user-inside-visual-studio-code>)  

> git config  user.name lrd1967  
> git config user.email lrdesiderio@gmail.com  

o repositório foi adicionado via linha de comando e depois atualizado no vscode porque ao tentar fazer tudo pelo vscode ele tentou criar o repositório com o nome do workspace (que não era dsmeta).

## SPRING BOOT vs VSCODE

A parte de backend no Spring Boot foi desenvolvida e testada no VsCode e não na IDE do Eclipse.  
Fazia um tempo que eu estava querendo testar o desenvolvimento Java com VsCode mas não queria migrar
os projetos da empresa para não ficar com um ambiente diferente dos colegas de trabalho.
Este projeto do DevSuperior foi uma boa oportunidade para testar. Embora o Eclipse esteja há anos
na frente, não tive problemas para rodar o projeto em Spring Boot.  
Vou ter que tentar o JBoss/WildFly para ver qual o desempenho.
