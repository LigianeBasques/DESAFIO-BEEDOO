
Este desafio tem o objetivo de avaliar conhecimentos e habilidades em teste de software.

# Desafio | Analista de Qualidade de Software Júnior #

## 👀Visão Geral👀 ##
Esse desafio foi proposto pela empresa **Beedoo AI Learning**, o objetivo é avaliar conhecimentos e habilidades em teste de software.
![Ligiabe Basques](https://img.shields.io/badge/Respons%C3%A1vel%3ALigiane%20Basques%20-%20%09%2332CD32)

![Site da Beedoo](https://imgur.com/6dFHsSi.png)

 ## 🔨Começando o desafio🔨 ##

 O site escolhido para realizar o desafio foi o Beedoo QA Chalenge que é uma plataforma de aprendizado com uma ampla variedade de cursos online/presencial, o qual pode-se: criar, excluir e listar diversos cursos. O site é https://creative-sherbet-a51eac.netlify.app/

 ## 🔎Funcionalidade: Cadastrar Curso🔎 ## 

 ![Página cadastrar curso](https://imgur.com/xN6ERyC.png)

 ## 💡Como foram as decisões tomadas para criar user story💡 ## 
 Antes de criarnos a user story, algumas decisões importantes foram levadas em consideração para que fossem criadas a saber: 
 - [x] 1- É a forma de escrevermos uma funcionalidade a ser desenvolvida;
 - [x] 2- Essa forma de escrevermos, todos os integrantes do time ou qualquer pessoa que pegar essa tarefa a ser desenvolvida, terá o entendimento do que deve ser desenvolvido;
 - [x] 3- Para quem for desenvolver, é importante ter a  empatia do porque o usuário necessita desta demanda, e isso é importante para a integração do time com o cliente. 
 

 ### 🎯User Story (US 01)🎯 ###

 <p> <b>Eu</b> como um usuário da plataforma Beedoo QA Chalenge </p> 
<p> <b>Gostaria</b> de realizar, cadastro de cursos na plataforma Beedoo QA Chalenge </p>
<p> <b>Para</b> que os cursos cadastrados sejam exibidos na página principal</p>

### 📋Regras de Negócios (RN)📋 ### 
| ID | Regras |
| ------------- | ------------- |
| RN-01 | Possuir um campo de input com uma arial label escrito: "Nome do curso" campo obrigatório
| RN-02 | Possuir um campo de input de texto com uma arial label escrito: "Descrição do curso" campo obrigatório
| RN-03 | Possuir um campo de input com uma arial label escrito: "Instrutor" campo obrigatório
| RN-04 | Possuir um campo de input com uma arial label escrito: "URL da imagem da capa"
| RN-05 | Possuir um campo de input com arial label escrito: "Data de início" com formato padrão de data brasileiro "dd/mm/aaaa" e com a opção de seleção por calendário.campo obrigatório 
| RN-06 | Possuir um campo de input com arial label escrito: "Data de fim" com formato padrão de data brasileiro "dd/mm/aaaa" e com a opção de seleção por calendário. campo obrigatório
| RN-07 | Possuir um campo de input com arial label escrito: "Número de vagas" e um campo seletor númerico campo obrigatório
| RN-08 | Possuir um campo de input com arial label escrito: "Tipo de curso" e um campo seletor com duas opções de escolha de tipo de curso: "Presencial" ou "Online" campo obrigatório
| RN-09 | Se a escolha do tipo de curso for: "Presencial", possuir um campo de input arial label escrito: "Endereço" campo obrigatório
| RN-10 | Se a escolha do tipo de curso for: "Online", possuir um campo de input arial label escrito: "Link de inscrição" campo obrigatório
| RN-11 | Possuir um botão clicavel na cor amarela escrito ao centro a palavra: "CADASTRAR CURSO" escrito tudo em caixa alta e na cor branca
| RN-12 | Após o cadastrar o curso irá aparecer uma mensagem: "Curso cadastrado com sucesso"

### ✅Critérios de aceite (CA)✅ ####
| ID | Critérios de aceite |
| ------------- | ------------- |
| CA-01 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input: "Nome do curso" </p> <p> <b>Então</b> consigo digitar o nome do curso</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-02 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input de texto: "Descrição do curso" </p> <p> <b>Então</b> consigo digitar uma descrição completa do curso</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-03 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Instrutor" </p> <p> <b>Então</b> consigo digitar o nome completo do instrutor do curso</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-04 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "URL da imagem da capa" </p> <p> <b>Então</b> consigo inserir o link da imagem da capa</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-05 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Data de início" </p> <p> <b>Então</b> consigo digitar ou selecionar a data de incio em padrão brasileiro</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> com a opção de seleção por calendário</p> <b>E</b> campo obrigatório</p>
| CA-06 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Data de fim" </p> <p> <b>Então</b> consigo digitar ou selecionar a data de fim em padrão brasileiro</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> com a opção de seleção por calendário</p> <b>E</b> campo obrigatório</p>
| CA-07 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Número de vagas" </p> <p> <b>Então</b> consigo digitar ou selecionar  o número de vagas</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> um campo seletor númerico</p> <b>E</b> campo obrigatório</p>
| CA-08 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Tipo de curso" </p> <p> <b>Então</b> consigo selecionar o tipo de curso: "Presencial" ou "Online" </p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-09 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Endereço" </p> <p> <b>Então</b> consigo digitar o endereço onde o curso será ministrado </p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-10 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Link de inscrição" </p> <p> <b>Então</b> consigo inserir o link de inscrição do curso </p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> campo obrigatório</p>
| CA-11 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> clico no botão : "CADASTRAR CURSO" </p> <p> <b>Então</b> consigo cadastrar cursos  </p> <p> <b>E</b> o mesmo é da cor amarelo </p> <b>E</b> com letras em caixa alta da cor branca </p>
| CA-12 | <p> <b>Dado</b> que preenchi todos os dados de cadastro do curso </p> <p> <b>Quando</b> clico no botão : "CADASTRAR CURSO" </p> <p> <b>Então</b> aparece uma mensagem: "Curso cadastrado com sucesso" </p> 

## 📝Cenários e Casos de testes (CTs)📝 ##
 ### 🔎Funcionalidade: Cadastrar Curso🔎 ### 
#### ✔️Casos de testes de sucesso✔️ ####

Segue o link abaixo do cenário e casos de testes da funcionalidade: Cadastrar curso
<li> <a href="https://docs.google.com/spreadsheets/d/1Mwl2F-swOfGMZjqZzgiyyh8Hue7fJuMvpn6GQ44I1EE/edit?usp=sharing" rel=nofollow>CENÁRIO E CASOS DE TESTE-SUCESSO</a><//li>

### 🤓Evidências dos cenário e casos de testes-sucesso🤓 ### 
Segue o link abaixo das evidências do cenário e casos de testes da funcionalidade: Cadastrar curso
<li> <a href="https://drive.google.com/drive/folders/1BlstsOAtzJOD4H7_2aZwtJHuUdBg-sBi?usp=sharing" rel=nofollow>EVIDÊNCIAS DOS CASOS DE TESTE-SUCESSO</a><//li>

### 🔎Funcionalidade: Cadastrar Curso🔎 ### 
#### ❌Casos de testes de erro❌ ####
Segue o link abaixo do cenário e casos de testes da funcionalidade: Cadastrar curso
<li> <a href="https://docs.google.com/spreadsheets/d/1Rg40PCLEh7OVkx4lnQ9UceKVNVKPlGctU993fINJ6tM/edit?usp=sharing" rel=nofollow>CENÁRIO E CASOS DE TESTE-ERRO</a><//li>

### 🤦‍♀️Evidências dos cenário e casos de testes-erro🤦‍♀️ ### 
Segue o link abaixo das evidências do cenário e casos de testes da funcionalidade: Cadastrar curso
<li> <a href="https://drive.google.com/drive/folders/1wvi3rU78zZVD36_5SFvtlF8kPn6HT01G?usp=sharing" rel=nofollow>EVIDÊNCIAS DOS CASOS DE TESTE-ERRO</a><//li>


## 👀Funcionalidade: Listar Cursos👀 ## 
![Página Listar curso](https://imgur.com/qCCkzU1.png)

## 💡Como foram as decisões tomadas para criar user story💡 ## 
 Antes de criarnos a user story, algumas decisões importantes foram levadas em consideração para que fossem criadas a saber: 
 - [x] 1- É a forma de escrevermos uma funcionalidade a ser desenvolvida;
 - [x] 2- Essa forma de escrevermos, todos os integrantes do time ou qualquer pessoa que pegar essa tarefa a ser desenvolvida, terá o entendimento do que deve ser desenvolvido;
 - [x] 3- Para quem for desenvolver, é importante ter a  empatia do porque o usuário necessita desta demanda, e isso é importante para a integração do time com o cliente.

 ### 🎯User Story (US 02)🎯 ###

 <p> <b>Eu</b> como um usuário da plataforma Beedoo QA Chalenge </p> 
<p> <b>Gostaria</b> de listar, todos os cursos cadastrados na plataforma Beedoo QA Chalenge </p>
<p> <b>Para</b> que possa visualizar todos os cursos cadastrados </p>

### 📋Regras de Negócios (RN)📋 ### 
| ID | Regras |
| ------------- | ------------- |
| RN-13 | Possuir header com as funcionalidades: Listar cursos e cadastrar curso
| RN-14 | Exibir as listas de cursos já cadastrados
| RN-15 | Exibir todas as informações dos cursos cadastrados completa
| RN-16 | Exibir um botão "EXCLUIR CURSO"
| RN-17 | Exibir um botão "EDITAR CURSO"
| RN-18 | Exibir o número de 4 cursos por página
| RN-19 | Exibir uma mensagem de alerta de exclusão de curso: "Curso excluido com sucesso"
| RN-20 | Exibir uma mensagem de alerta de edição de curso: "Curso editado com sucesso"

### ✅Critérios de aceite (CA)✅ ####
| ID | Critérios de aceite |
| ------------- | ------------- |
| CA-13 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> visualizo o header </p> <p> <b>Então</b> os botões: "LISTAR CURSOS" e "CADASTRAR CURSOS" são exibidos</p>
| CA-14 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> clico em "LISTAR CURSOS" </p> <p> <b>Então</b> os cursos cadastrados são exibidos</p>
| CA-15 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> listo os cursos </p> <p> <b>Então</b> são exibidas todas as informações cadastradas no curso</p>
| CA-16 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> clico no botão: "EXCLUIR CURSO" </p> <p> <b>Então</b> o curso é excluído</p>
| CA-17 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> clico no botão: "EDITAR CURSO" </p> <p> <b>Então</b> o curso é editado</p>
| CA-18 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> clico no botão: "EXCLUIR CURSO" </p> <p> <b>Então</b> é exibido uma mensagem:"Curso excluido com sucesso"</p>
| CA-19 | <p> <b>Dado</b> que estou na página de listar curso </p> <p> <b>Quando</b> clico no botão: "EDITAR CURSO" </p> <p> <b>Então</b> é exibido uma mensagem:"Curso editado com sucesso"</p>

## 📝Cenários e Casos de testes (CTs)📝 ##
 ### 👀Funcionalidade: Listar Curso👀 ### 
#### ✔️Casos de testes de sucesso✔️ ####

Segue o link abaixo do cenário e casos de testes da funcionalidade: Listar curso
<li> <a href="https://docs.google.com/spreadsheets/d/1kt-wL4MglfC1vBiTC5ffqUe7OmZ1pncY0qdowb6PExw/edit?usp=sharing" rel=nofollow>EVIDÊNCIAS DOS CASOS DE TESTE-SUCESSO</a><//li>

### 🤓Evidências dos cenário e casos de testes-sucesso🤓 ### 
Segue o link abaixo das evidências do cenário e casos de testes da funcionalidade: Listar curso

<li> <a href="https://drive.google.com/drive/folders/1iMYqR_R9_9hVMsljJ-kWZJkf6pWUT0j_?usp=sharing" rel=nofollow>EVIDÊNCIAS DOS CASOS DE TESTE-SUCESSO</a><//li>

### 👀Funcionalidade: Listar Curso👀 ### 
#### ❌Casos de testes de erro❌ ####
Segue o link abaixo do cenário e casos de testes da funcionalidade: Cadastrar curso
<li> <a href="https://docs.google.com/spreadsheets/d/1Rg40PCLEh7OVkx4lnQ9UceKVNVKPlGctU993fINJ6tM/edit?usp=sharing" rel=nofollow>CENÁRIO E CASOS DE TESTE-ERRO</a><//li>










 


