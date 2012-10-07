---
layout: post 
title: "Blogando com Markdown, Jekyll e GitHub Pages"
---

Olá pessoal, tudo bem?

Depois de meses de ter começado com a ideia de ter um blog, finalmente resolvi fazê-lo.

*Motivo de tanta demora?* Não sei, mas acho que agora estou organizando melhor minhas ideias, o que venho estudando, e o que quero daqui pra frente.

Com isso, mostro abaixo os componentes que usei para criar o blog, e o porquê de cada um.

Antes, uma breve história..
--------

Ah, a Web 2.0.. conteúdos dinâmicos.. pessoas deixando de serem "consumidoras" de informação, para gerar seus próprios conteúdos e compartilhando-os, se tornando assim, "web autores". <br>
E que melhor forma de se adquirir conhecimento se não na troca de informações?

Para ajudar as pessoas na criação e compartilhamento de conteúdo, surgiram os CMS's (*Content Management Systems/Sistema de Gerenciamento de Conteúdo*). Uma plataforma completa para geração, publicação, e gerenciamento de sites, blogs, etc..

Mas o que me incomoda nesses CMS's? <br>
Gosto de ter "controle" sobre o que faço/escrevo. E testando alguns dos editores dessas *engines*, não me senti confortável com o resultado. Se utilizasse o modo texto, o html que era gerado não era dos melhores, e se utilizasse o modo html, o trabalho para se conseguir o resultado esperado era grande.
Além disso, não gostava da ideia de o conteúdo ter que ficar em banco de dados. <br>
Queria que meu blog fosse simples e rápido.

Foi ai que conheci o <a href="http://daringfireball.net/projects/markdown/" alt="Markdown" target="_blank">Markdown</a>

Markdown
--------
De forma simplificada, markdown é: uma "sintaxe de formatação de texto simples".<br>
Através da sintaxe markdown posso escrever meus posts de uma forma muito mais amigável que html, com textos *puros* e *simples*. E o resultado? Um html válido! =D

Ta, descobri uma forma de escrever meus posts, mas como vou hospedar isso sem um CMS?

Jekyll
------
O <a href="https://github.com/mojombo/jekyll/" alt="Jekyll" target="_blank">Jekyll</a> é uma ferramenta, escrita em Ruby, para geração de site estático. Trabalha com arquivos markdown ou <a href="http://www.textism.com/tools/textile/" alt="textile" target="_blank">textile</a>, também usa um sistema de templates chamado <a href="http://liquidmarkup.org/" alt="Liquid" target="_blank">Liquid</a>, e o resultado são arquivos estáticos com o conteúdo html.

Fantástico, não?

Já tenho uma sintaxe simples pra escrever meus posts, e uma ferramenta para gerar html disso.. mas ainda não resolvi o problema da hospedagem.

GitHub Pages
------------
Pra quem não conhece, <a href="https://github.com" alt="github" target="_blank">github</a> é um web hosting compartilhado, escrito em Ruby on Rails, para projetos que usam o controle de versionamento <a href="http://pt.wikipedia.org/wiki/Git" alt="git" target="_blank">git</a>.

Também possui características de uma rede "social coding", onde é possível seguir, trocar mensagens, e ajudar em projetos públicos, interagindo assim com outros desenvolvedores.

O Github possui um serviço chamado <a href="http://pages.github.com/" alt="github pages" target="_blank">GitHub Pages</a>, que transforma um repositório em um web site. Além disso, ele trabalha muito bem com markdown, e consegue subir um site usando jekyll.

Enfim...
--------
Com o GitHub Pages, tenho uma hospedagem free do meu blog, onde escrevo em markdown e o jekyll se encarrega de gerar seu html, totalmente válido e simples.

Me sinto muito mais confort?vel dessa forma, com um editor de texto (recomento o <a href="http://www.sublimetext.com/" alt="Sublime Text" target="_blank">Sublime Text</a>) e alguns comandos via Git Bash tudo está no meu repositório.

Aprendi bastante com essa experiência.

Meu blog e toda sua estrutura está no github e pode ser olhado, *forkado* e etc. <a href="https://github.com/Edegilson/edegilson.github.com" alt="github" target="_blank">https://github.com/Edegilson/edegilson.github.com</a> =D

Bom, é isso, abs, <br>
Edegilson Sousa.