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



> <h1>Server.js</h1>
> Iniciaremos falando agora sobre o server.js, pois é o arquivo principal do boilberplate.

O **env** tem relação com dados, ambiente de desenvolvimento privado, dados pessoais.
Na produção, é criado o env para esconder essas informações.

O **mongoose** tem relação com a modelagem do banco de dados. No boilerplate criamos um connect com os dados do env, a partir disso, acessamos a promisse com o then e catch, tratando ali e emitindo um sinal com emit, caso de certo.

O **session** identifica o navegador do cliente, salvando um cookie com ID no computador do cliente, toda vez que conecta no servidor, ele manda o cookie, ele verifica a ID e usa os dados ali.

O **MongoStore** configura para salvar as sessões vão ser salvas dentro da base de dados, por padrão (sem o MongoStore), ele salva no servidor, o que é perigoso.

O **flashMessages** são as mensagens autodestrutivas, mensagens que ao serem lidas, sejam destruidas, servem para mandar mensagens e feedback. Essas mensagens são salvas em sessões, por isso usamos o **session**.

O **routes** são as rotas da nossa sessão, /home, etc..

O **path** é usado para trabalhar com os caminhos

O **helmet** é recomendado pela equipe do Express.

O **csrf** cria token para todos os formulários da nossa aplicação, onde, nenhum aplicativo externo ou site, poste algo dentro da nossa aplicação. aumenta a segurança de nossa apicação. 

O **middlewareGlobal**, **checkCsrfError**, **csrfMiddleware** são middlewares criados por mim.  **Middlewares** são funções executadas na rota, como uma cadeia de comandos que são executados.

> <h1>routes.js</h1>
> Sobre o arquivo routes.js agora.

O arquivo routes ele decide qual controller vai ser utilizado, quem vai controlar aquela rota.

Criamos o controlador como por exemplo: homeController, cujo seu trabalho é: decidir o model que controla os dados ali. E o view que será usado na aplicação ali.

A rota escolhe o controller, que escolhe a rota, model e view.

> <h1>Essa aplicação trabalha com MVC.</h1>
> Model
> Views
> Controllers





