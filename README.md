<h1 align="center">
  <br>
  <img src="img/database.1.png" alt="mulher atualizando banco de dados" width="316">
  <br>
    <br>
    <p align="center">Aula 12 - Banco de Dados<p>
</h1>

-------

## *Tipos de Dados*
  Três tipos de dados mais utilizados:
  
   1- Conjunto de dados Estruturados: Representados por dados tabulados que contém dados organizados com esquema bem definido. Ex.: Banco de dados relacionais.

   2- Conjunto de dados semi-estruturados: Dados que não possuem um modelo formal organizado. Ex.: arquivo xml.

   3- Conjunto de dados não estruturados: Arquivos que não possuem dados organizados, podem ser processados em tempo real. São estruturados quando do processamento/definição dos esquemas. Ex.: log de servidores, comentários de redes sociais, arquivos de texto.

## *Banco de dados NoSQL*

 Visto os tipos de dados mais usados, vamos falar sobre o banco de dados não Relacional ou NoSQL.

 Os bancos de dados não relacionais oferecem uma arquitetura muito mais escalável e eficiente que os banco de dados relacionais. e facilitam consultas noSQL de dados semi-estruturados ou não estruturados.
 ### Categorias de banco de Dados NoSQL  
 
 - [x] Graph database - Geralmente aderente a Cenários de rede social online;
 - [x] Document database - Permite o armazenamento de milhões de documentos. _(MongoDB)_
 - [x] Key-values stores - Dados armazenados no formato de chave e valor e os valores são identificados pelas chaves.
 - [x] Columm family stores - Dados orientados a coluna organizados em grupos de colunas e armazenados.

 ## Banco de DADOS

 <h1 align="center">
  <br>
  <img src="img/mongoDB.png" alt="MongoDB" width="316">
  <br>
    <br>
    <p align="center">Aula 12 - Banco de Dados<p>
</h1>
 ![mongoDB](./img/mongoDB.png)

 Um dos líderes de Banco de Dados, o MongoDB é orientado a documento, substitue o conceito de "ilha" como em banco de dados relacionais por um modelo mais flexível, o "documento".  
 Foi desenvolvido em linguagem ``C++`` e é um opens source.

 ### Características:

 - Indexação: Suporta índices secundários, permitindo a construção de queries mais velozes;
  - agregação: Permite a construção de agregações complexas de dados otimizando o desempenho;
  - tipos de dados especiais: Suporta coleções time-to-live para dados que expiram em um determinado tempo, como sessões por exemplo;
  - Armazenamento: Suporta armazenamento de grande quantidades de dados.

  _Importante_- Alguns tipos de Joins e transações multi-linha nãoe stão presentes no MongoDB, características de Banco de Dados Relacionais.


