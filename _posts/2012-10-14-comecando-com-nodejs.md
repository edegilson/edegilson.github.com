---
layout: post 
title: "Começando com Node.js"
---

Olá pessoal, tudo bem?

Hoje começo a falar de algo que tem me chamado muita atenção: <a href="http://nodejs.org/" alt="Node.js" target="_blank">Node.js</a>.

Mas o que é node.js?
------------------------

Node.js é, _basicamente_, um ambiente de execução que permite usar javascript fora do navegador. É, isso mesmo! Por que não usar no server, a mesma linguagem que é usada no client? <br>
Pra isso, ele _incorpora_ o <a href="http://code.google.com/p/v8/" alt="V8 Javascript engine" target="_blank">V8 Javascript engine</a>, um interpretador de scripts poderoso, desenvolvido pela Google, e utilizado no Chrome.

Outra característica importante é que ele é baseado em <a href="http://en.wikipedia.org/wiki/Event-driven_programming" alt="event-driven" target="_blank">event-driven</a>, ou seja, tudo é orientado à eventos e callbacks.<br>
Node também usa o conceito de <a href="http://en.wikipedia.org/wiki/Asynchronous_I/O" alt="non-blocking I/O" target="_blank">non-blocking I/O</a>. Ele não possui um gerenciador de threads. Usando uma única thread, ele é capaz de criar _processos_ conforme a necessidade, garantido que nunca haverá _bloqueio_ entre chamadas pois tudo é assíncrono.

Essas características fazem com que node seja altamente escalável e performático. Ideal para desenvolver aplicações real-time, ou que necessitam de grande acesso de requisições.

Apresentado, _superficialmente_, esses conceitos, vamos criar um simples servidor HTTP usando node.

_(Aqui, conto que você já tenha seu ambiente node instalado e configurado.)_

Criando um simples servidor HTTP
--------------------------------

Abaixo, explico passo a passo como fazer isso..

Primeiro, _requisitamos_ o módulo _http_, que é <a href="https://github.com/joyent/node/wiki/Modules" alt="distribuido" target="_blank">distribuído</a> junto com o node.js..

{% highlight js %}

var http = require('http');

{% endhighlight %}

Depois, criamos nosso _server_, passando uma função de callback a ser executada no término da operação. Essa função irá responder uma mensagem de texto "Hello World" e encerrar o response.

{% highlight js %}

var server = http.createServer(function (request, response) {
	response.writeHead(200, {'Content-Type': 'text/plain'});
	response.write('Hello World');
	response.end();
});

{% endhighlight %}

Por fim, configuramos nosso _server_ pra responder as requisições na porta 3000 do nosso localhost.

{% highlight js %}

server.listen(3000);

{% endhighlight %}

Basta salvar esse código em um arquivo "server.js" e executar no prompt de comando:

{% highlight bash %}

node server.js

{% endhighlight %}

Ao abrir o navegador no endereço "http://localhost:3000" você receberá a mensagem "Hello World" em resposta a sua requisição.

Concluindo..
------------

Essa é só uma simples amostra da facilidade de se criar um servidor HTTP com node, usando javascript. <br>
Confesso que estou bastante empolgado com node, e com a forma que ele trabalha. <br>
Pretendo me aprofundar mais na <a href="http://nodejs.org/api/all.html" alt="distribuido" target="_blank">api</a> dele, integrando com diversos módulos pra demonstrar um pouco da sua capacidade.

Bom, é isso.