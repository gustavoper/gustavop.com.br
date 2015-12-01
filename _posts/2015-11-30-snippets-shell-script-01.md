---
layout: post
title: Snippets - Shell Script (01)
description: ""
modified: 2015-11-30
tags: [linux, osx, git, push, shell]
image:
  feature: gogogo-demo.png
  credit: Captura de tela (Gustavo)
  creditlink: http://www.google.com.br
---

Git para preguiçosos (como eu)
===


Essa dica vai para quem precisa sair voando do trabalho e precisa fazer o ciclo add / commit / push bem rápido. 

Coloque esse trecho de código no seu `.bash_profile` (ou `.bashrc`, se estiver usando o linux):


    function gogogo() 
    { 
    	git add .
    	git commit -a -m "$1"
    	git push
    }


Pronto! Reinicie o shell e seu snippet está valendo. Para utilizá-lo, é bem simples: 


![](/images/gogogo-demo.png)

Basicamente, o snippet adiciona os arquivos ao branch, faz o commit e em seguida o "push" no repositório. Mais simples que isso, só se vc programar uma tarefa no cron para *commitar* na hora da saida...

Opa, até que não é uma má idéia ;-)