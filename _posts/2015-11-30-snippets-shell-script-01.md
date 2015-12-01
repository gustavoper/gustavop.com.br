---
layout: post
title: Snippets - Shell Script (01)
description: ""
modified: 2015-11-30
tags: [linux, osx, git, push, shell]
image:
  feature: 3953273590_704e3899d5_m.jpg
  credit: Google
  creditlink: http://www.google.com.br
---

Snippets para shell script: git para preguiçosos (como eu)
===


Essa dica vai para quem está atrasado para sair do trabalho e precisa fazer o ciclo add / commit / push bem rápido. 

Coloque esse trecho de código no seu .bash_profile (ou .bashrc, se estiver usando o linux):


    function gogogo() 
    { 
    	git add .
    	git commit -a -m "$1"
    	git push}


Pronto! Reinicie o shell e seu snippet está valendo. Para utilizá-lo, é bem simples: 



Basicamente, o snippet adiciona os arquivos ao branch, faz o commit e em seguida o "push" no repositório. 