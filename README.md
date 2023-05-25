<h1> Documentação da Boilerplate </h1>

Mostraremos aqui a estrutura das pastas:

![image](https://github.com/NobreREAL/BoilerplateConcept/assets/79422432/840428a9-f956-4ece-8d4a-b30583583582)

> #### Estrutura de pastas:
> - Frontend
> - public
> - src
> 
> **São as pastas principais do projeto**

Mostraremos aqui a estrutura dos arquivos do projeto:

![image](https://github.com/NobreREAL/BoilerplateConcept/assets/79422432/4dc3979f-f249-4866-86a3-4168f9bc00a6)


> #### Arquivos além das pastas:
> - router.js
> - server.js
> - webpack.config.js

Iniciaremos falando agora sobre o server.js, pois é o arquivo principal do boilberplate.


#Server.js

O **env** tem relação com dados, ambiente de desenvolvimento privado, dados pessoais.
Na produção, é criado o env para esconder essas informações.

O **mongoose** tem relação com a modelagem do banco de dados. No boilerplate criamos um connect com os dados do env, a partir disso, acessamos a promisse com o then e catch, tratando ali e emitindo um sinal com emit, caso de certo.




