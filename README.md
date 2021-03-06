<h1 align="left">Angular CRUD</h1>

<h4 align="center">Iniciando o Projeto</h4>

<h5 align="left">Cria o package.json</h5>
<pre>npm init -y</pre>

<h5 align="left">Instala o server</h5>
<pre>npm i json-server</pre>

<hr />

<h5 align="left">O que é o Angular?</h5>

<p align="left">
    Um framework JavaScript desenvolvido pelo Google para criação de aplicações Web SPA baseada em componentes.
</p>

<hr />

<h5 align="left">Versões do Angular</h5>

<p align="left">
    1 <br />
    AngularJS <br />
    <br />
    2 <br />
    Novo Angular (Comp.) <br />
    <br />
    2 4 ... 9 <br />
    2 versões por ano!
</p>

<hr />

<h5 align="left">Command Line Interface</h5>

<pre>npm i -g @angular/cli</pre>
<pre>ng new minha-app</pre>

<hr />

<h5 align="left">TypeScript</h5>

<p align="left">
    Linguagem criada pela Microsoft. <br />
    O código escrito em TypeScript é compilado para JavaScript. <br />
    <br />
    Orientada a Objeto & Tipagem forte. <br />
    Superset do JavaScript.
</p>

<hr />

<h5 align="left">Árvore de Componentes</h5>

<p align="center">
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/arvoreDeComponentes.jpg"
        alt="Árvore de Componentes"
    >
</p>

<hr />

<h5 align="left">Conceitos Essenciais</h5>

<p align="center">
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/inicializacaoDaAPP.jpg"
        alt="Inicialização do APP"
    >
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/componenteAngular.jpg"
        alt="O que é um Componente?"
    >
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/TSHTMLCSS.jpg"
        alt="O que é um Componente?"
    >
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/organizacaoUsandoModulo1.jpg"
        alt="Organização Usando Módulo"
    >
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/organizacaoUsandoModulo2.jpg"
        alt="Organização Usando Módulo"
    >
    <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/anatomiaDoModulo.jpg"
        alt="Anatomia do Módulo"
    >
        <img 
        src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/backend/img/organizacaoUsandoModulo3.jpg"
        alt="Organização Usando Módulo"
    >
</p>

<h5 align="left">Criando APP com o Angular CLI</h5>

<pre>npm i -g @angular/cli</pre>
<pre>ng new frontend --minimal</pre>
<pre>npm start</pre>

<hr />

<h5 align="left">Instalação dos Componentes do Material</h5>

<pre>ng add @angular/material</pre>

<hr />

<h5 align="left">Componente Cabeçalho</h5>

<pre>ng g c components/template/header</pre>

<hr />

<h5 align="left">Componente Rodapé</h5>

<pre>ng g c components/template/footer</pre>

<hr />

<h5 align="left">Componente Navegação</h5>

<pre>ng g c components/template/nav</pre>

<p align="left">
    <a href="https://material.io/resources/icons/?style=baseline">Icons</a>
</p>

<hr />

<h5 align="left">Elementos do Angular</h5>

<p align="left">
    Attribute Directives <br />
    Altera a aparência e o comportamento de um elemento, componente ou outra diretiva.
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/attributeDirectivesDecorator.jpg" alt="Attribute Directives Decorator">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/attributeDirectives.jpg" alt="Attribute Directives appRed">
    <br />
    Structural Directives <br />
    Altera o layout adicionando e removendo elementos da DOM.
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/structuralDirectives.jpg" alt="Structural Directives">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/propertyBinding.jpg" alt="Property Binding">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/eventBinding.jpg" alt="Event Binding">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/oneWayDataBinding.jpg" alt="One Way Data Binding">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/twoWayDataBinding.jpg" alt="Two Way Data Binding">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/angularRouter.jpg" alt="Angular Router">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/angularRouteRouterOutlet.jpg" alt="Angular Router Router Outlet">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/angularRouteProdutos.jpg" alt="Angular Router Produtos">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/angularPipesComParametros.jpg" alt="Angular Pipes com Parametros">
    <img src="https://github.com/lucasrmagalhaes/angular-crud/blob/main/frontend/src/assets/img/angularPipesChaining.jpg" alt="Angular Pipes Chaining">
</p>

<hr />

<h5 align="left">Anotações:</h5>

<p align="left">
    Patch altera alguns atributos. <br />
    Put altera o objeto inteiro.
</p>