---
layout: post
title: "Blogando com Markdown, Jekyll e GitHub Pages"
description: "Um pouco sobre Markdown, Jekyll e GitHub Pages"
keywords: jekyll, gitHub, markdown
category: Jekyll, GitHub, Markdown
tags: [jekyll, github, markdown]
---

Ol� pessoal, tudo bem?

Depois de meses de ter come�ado com a ideia de ter um blog, finalmente resolvi faz�-lo.

*Motivo de tanta demora?* N�o sei, mas acho que agora estou organizando melhor minhas ideias, o que venho estudando, e o que quero daqui pra frente.

Com isso, mostro abaixo os componentes que usei para criar o blog, e o porqu� de cada um.

Antes, uma breve hist�ria..
--------

Ah, a Web 2.0.. conte�dos din�micos.. pessoas deixando de serem "consumidoras" de informa��o, para gerar seus pr�prios conte�dos e compartilhando-os, se tornando assim, "web autores". <br>
E que melhor forma de se adquirir conhecimento se n�o na troca de informa��es?

Para ajudar as pessoas na cria��o e compartilhamento de conte�do, surgiram os CMS's (*Content Management Systems/Sistema de Gerenciamento de Conte�do*). Uma plataforma completa para gera��o, publica��o, e gerenciamento de sites, blogs, etc..

Mas o que me incomoda nesses CMS's? <br>
Gosto de ter "controle" sobre o que fa�o/escrevo. E testando alguns dos editores dessas *engines*, n�o me senti confort�vel com o resultado. Se utilizasse o modo texto, o html que era gerado n�o era dos melhores, e se utilizasse o modo html, o trabalho para se conseguir o resultado esperado era grande.
Al�m disso, n�o gostava da ideia de o conte�do ter que ficar em banco de dados. <br>
Queria que meu blog fosse simples e r�pido.

Foi ai que conheci o <a href="http://daringfireball.net/projects/markdown/" alt="Markdown" target="_blank">Markdown</a>

Markdown
--------
De forma simplificada, markdown �: uma "sintaxe de formata��o de texto simples".<br>
Atrav�s da sintaxe markdown posso escrever meus posts de uma forma muito mais amig�vel que html, com textos *puros* e *simples*. E o resultado? Um html v�lido! =D

Ta, descobri uma forma de escrever meus posts, mas como vou hospedar isso sem um CMS?

Jekyll
------
O <a href="https://github.com/mojombo/jekyll/" alt="Jekyll" target="_blank">Jekyll</a> � uma ferramenta, escrita em Ruby, para gera��o de site est�tico. Trabalha com arquivos markdown ou <a href="http://www.textism.com/tools/textile/" alt="textile" target="_blank">textile</a>, tamb�m usa um sistema de templates chamado <a href="http://liquidmarkup.org/" alt="Liquid" target="_blank">Liquid</a>, e o resultado s�o arquivos est�ticos com o conte�do html.

Fant�stico, n�o?

J� tenho uma sintaxe simples pra escrever meus posts, e uma ferramenta para gerar html disso.. mas ainda n�o resolvi o problema da hospedagem.

GitHub Pages
------------
Pra quem n�o conhece, <a href="https://github.com" alt="github" target="_blank">github</a> � um web hosting compartilhado, escrito em Ruby on Rails, para projetos que usam o controle de versionamento <a href="http://pt.wikipedia.org/wiki/Git" alt="git" target="_blank">git</a>.

Tamb�m possui caracter�sticas de uma rede "social coding", onde � poss�vel seguir, trocar mensagens, e ajudar em projetos p�blicos, interagindo assim com outros desenvolvedores.

O Github possui um servi�o chamado <a href="http://pages.github.com/" alt="github pages" target="_blank">GitHub Pages</a>, que transforma um reposit�rio em um web site. Al�m disso, ele trabalha muito bem com markdown, e consegue subir um site usando jekyll.

Enfim...
--------
Com o GitHub Pages, tenho uma hospedagem free do meu blog, onde escrevo em markdown e o jekyll se encarrega de gerar seu html, totalmente v�lido e simples.

Me sinto muito mais confort�vel dessa forma, com um editor de texto (recomento o <a href="http://www.sublimetext.com/" alt="Sublime Text" target="_blank">Sublime Text</a>) e alguns comandos via Git Bash tudo est� no meu reposit�rio.

Aprendi bastante com essa experi�ncia.

Meu <a href="https://github.com/Edegilson/edegilson.github.com" alt="github" target="_blank">blog</a> e toda sua estrutura est� no github e pode ser olhado, *forkado* e etc. =D

Bom, � isso, abs, <br>
Edegilson Sousa.