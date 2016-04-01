---
layout: post
title: "Como instalar o Octopresss"
date: 2016-04-01 14:47:58 -0300
comments: true
categories: 
---
<h4>Para instalarmos o Octopress precisaremos de:</h4>
<ul>
<li><a href="https://git-scm.com/">Instalar o Git.</a></li>
<li>Instalar o Ruby 1.9.3 ou superior usando <a href="http://octopress.org/docs/setup/rbenv/">rbven</a> ou <a href="http://octopress.org/docs/setup/rvm/">RMV</a>.</li>
<li>Instalar um dos <a href="https://github.com/sstephenson/execjs">ExecJS</a> suportados tempos de execução de JavaScript.</li>
</ul>
<h3>Setup Octopress</h3>
<table>
<tbody>
<tr>
<pre>
<div>git git clone: ​​octopress //github.com/imathis/octopress.git
cd octopress
</div>
</pre>
</tr>
</tbody>
</table>
<h4>Em seguida, instalar as dependências.</h4>
<table>
<tbody>
<tr>
<pre>
<div>gem install bundler
rbenv rehash     # Se você usar rbenv, refazer(rehash) para ser capaz de executar o comando pacote
bundle install</div>
</pre>
</tr>
</tbody>
<h4>Instale o tema padrão do Octopress.</h4>
<pre>
<div>rake install</div>
</pre>
<h3>Proximos passos:</h3>
<ul>
<li><a href="http://octopress.org/docs/deploying" target="_blank">Configurar a implantação</a></li>
<li><a href="http://octopress.org/docs/configuring" target="_blank">Configurar o seu blog</a></li>
<li><a href="http://octopress.org/docs/blogging" target="_blank">Começar a blogar com Octopress</a></li>
</ul>
<strong>Referencia: </strong>http://octopress.org/
