
Este desafio tem o objetivo de avaliar conhecimentos e habilidades em teste de software.

# Desafio | Analista de Qualidade de Software Júnior #

## 👀Visão Geral👀 ##
Esse desafio foi proposto pela empresa **Beedoo AI Learning**, o objetivo é avaliar conhecimentos e habilidades em teste de software.
![Ligiabe Basques](https://img.shields.io/badge/Respons%C3%A1vel%3ALigiane%20Basques%20-%20%09%2332CD32)

![Site da Beedoo](https://imgur.com/6dFHsSi.png)

 ## 🔨Começando o desafio🔨 ##

 O site escolhido para realizar o desafio foi o Beedoo QA Chalenge que é uma plataforma de aprendizado com uma ampla variedade de cursos online/presencial, o qual pode-se: criar, excluir e listar diversos cursos. O site é https://creative-sherbet-a51eac.netlify.app/new-course

 ## 🔎Funcionalidade: Cadastrar Curso🔎 ## 

 ![Página cadastrar curso](https://imgur.com/xN6ERyC.png)

 ## 💡Como foram as decisões tomadas para criar user story💡 ## 
 Antes de criarnos a user story, algumas decisões importantes foram levadas em consideração para que fossem criadas a saber: 
 - [x] 1- É a forma de escrevermos uma funcionalidade a ser desenvolvida;
 - [x] 2- Essa forma de escrevermos, todos os integrantes do time ou qualquer pessoa que pegar essa tarefa a ser desenvolvida, terá o entendimento do que deve ser desenvolvido;
 - [x] 3- Para quem for desenvolver, é importante ter a  empatia do porque o usuário necessita desta demanda, e isso é importante para a integração do time com o cliente. 
 

 ### 🎯User Story (US)🎯 ###

 <p> <b>Eu</b> como um usuário da plataforma Beedoo QA Chalenge </p> 
<p> <b>Gostaria</b> de realizar, cadastro de cursos na plataforma Beedoo QA Chalenge </p>
<p> <b>Para</b> que os cursos cadastrados sejam exibidos na página principal</p>

### 📋Regras de Negócios (RN)📋 ### 
| ID | Regras |
| ------------- | ------------- |
| RN-01 | Possuir um campo de input com uma arial label escrito: "Nome do curso"
| RN-02 | Possuir um campo de input de texto com uma arial label escrito: "Descrição do curso"
| RN-03 | Possuir um campo de input com uma arial label escrito: "Instrutor"
| RN-04 | Possuir um campo de input com uma arial label escrito: "URL da imagem da capa"
| RN-05 | Possuir um campo de input com arial label escrito: "Data de início" com formato padrão de data brasileiro "dd/mm/aaaa" e com a opção de seleção por calendário. 
| RN-06 | Possuir um campo de input com arial label escrito: "Data de fim" com formato padrão de data brasileiro "dd/mm/aaaa" e com a opção de seleção por calendário.
| RN-07 | Possuir um campo de input com arial label escrito: "Número de vagas" e um campo seletor númerico
| RN-08 | Possuir um campo de input com arial label escrito: "Tipo de curso" e um campo seletor com duas opções de escolha de tipo de curso: "Presencial" ou "Online"
| RN-09 | Se a escolha do tipo de curso for: "Presencial", possuir um campo de input arial label escrito: "Endereço"
| RN-10 | Se a escolha do tipo de curso for: "Online", possuir um campo de input arial label escrito: "Link de inscrição"
| RN-11 | Possuir um botão clicavel na cor amarela escrito ao centro a palavra: "CADASTRAR CURSO" escrito tudo em caixa alta e na cor branca

### ✅Critérios de aceite (CA)✅ ####
| ID | Critérios de aceite |
| ------------- | ------------- |
| CA-01 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input: "Nome do curso" </p> <p> <b>Então</b> consigo digitar o nome do curso</p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-02 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input de texto: "Descrição do curso" </p> <p> <b>Então</b> consigo digitar uma descrição completa do curso</p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-03 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Instrutor" </p> <p> <b>Então</b> consigo digitar o nome completo do instrutor do curso</p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-04 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "URL da imagem da capa" </p> <p> <b>Então</b> consigo inserir o link da imagem da capa</p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-05 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Data de início" </p> <p> <b>Então</b> consigo digitar ou selecionar a data de incio em padrão brasileiro</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> com a opção de seleção por calendário</p>
| CA-06 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Data de fim" </p> <p> <b>Então</b> consigo digitar ou selecionar a data de fim em padrão brasileiro</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> com a opção de seleção por calendário</p>
| CA-07 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Número de vagas" </p> <p> <b>Então</b> consigo digitar ou selecionar  o número de vagas</p> <p> <b>E</b> o mesmo possui um arial label</p> <b>E</b> um campo seletor númerico</p>
| CA-08 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Tipo de curso" </p> <p> <b>Então</b> consigo selecionar o tipo de curso: "Presencial" ou "Online" </p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-09 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Endereço" </p> <p> <b>Então</b> consigo digitar o endereço onde o curso será ministrado </p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-10 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> visualizo o campo input : "Link de inscrição" </p> <p> <b>Então</b> consigo inserir o link de inscrição do curso </p> <p> <b>E</b> o mesmo possui um arial label</p>
| CA-11 | <p> <b>Dado</b> que estou na página de cadastrar curso </p> <p> <b>Quando</b> clico no botão : "CADASTRAR CURSO" </p> <p> <b>Então</b> consigo cadastrar cursos  </p> <p> <b>E</b> o mesmo é da cor amarelo </p> <b>E</b> com letras em caixa alta da cor branca </p>

## 📝Casos de testes (CTs)📝 ##
### ✔️Casos de testes de sucesso✔️ ###




 


