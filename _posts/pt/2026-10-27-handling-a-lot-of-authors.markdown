---
layout: post
title:  "Lidar com muitos autores ao ler artigos científicos"
date:   2026-10-27
categories: science article organization
lang: pt
---

Escrever um doutoramento (e muitos outros tipos the trabalhos científicos) requer muito tempo a encontrar, ler, e organizar artigos.
Para mim, a parte mais difícil foi acompanhar a quantidade de nomes de autores.
Cade artigo que li tinha quatro a seis autores e a área de efeitos parentais é relativamente grande; isto significa que não há muitas sobreposições e autores repetidos.
Foi difícil para mim distinguir os autores que têm trabalhado com efeitos parentais há muito tempo dos autores que estavam a contribuir temporariamente.
Perto do fim do doutoramento, encontrei o [Obsidian](https://obsidian.md/).

O Obsidian é uma app de tirar notas, mas sem muitos dos detalhes que outras apps tem (tipo OneNote e parecidos).
Em vez disso, cada nota corresponde a um único ficheiro de texto (com um nome tipo `TITULO.md`) que pode ser facilmente ser aberto com outros editores de texto.
No entanto, o detalhe importante do Obsidian para mim é a caracteristica de **"backlink"** (uma "ligação de volta").

Como nos formatos Markdown normais, dá para fazer ligações entre ficheiros com parenteses retos (`[assim]`).
No Obsidian, quando se faz uma ligação (com `[[parenteses duplos]]`) não se cria o alvo da ligação e ela fica sem destino.
Desta forma, ao escrever uma nota, pode-se criar ligações para ideias futuras sem ter de criar todos os ficheiros imediatamente.
Quando se cria finalmente uma destas novas notas, dá para ver quais das notas anteriores fez uma ligação para a nota nova; isto é o "backlink".
Alternativamente, pode-se criar todas as ligações imediatamente and, ao escrever novas notas, dá para reconhecer que termos é que já foram usados antes.
Por exemplo, ao escrever notas sobre `git`, pode-se incluir um link para `[[Linus Torvalds]]` sem pensar muito mais no assunto.
Depois, três meses depois, ao escrever notas sobre `linux` e incluir a mesma ligação (e ao criar a nota do Sr. Torvalds) podemos ficar surpreendidos que ele criou ambos os softwares.

![Exemplo de backlink no Obsidian](/assets/images/obsidian_backlink_example.png){:style="display:block; margin-left:auto; margin-right:auto"}

Este detalhe no Obsidian, juntamente com um plugin para importar detalhes dos artigos do [Zotero](https://www.zotero.org/), fez ler, notar, e organizar as minhas ideias bem mais fácil.
Ao criar uma nota para um artigo, passei uns segundos adicionais a criar as notas para cada um dos autores.
No futuro, de cada vez que adiciono um novo artigo, posso ver imediatamente que autores é que já tinha lido e quais eram novos.
Como demonstrado na imagem abaixo, isto torna o reconhecimento de nomes familiares mais fácil.
A nota para Simon Gladman já existia quando criei a nota para o artigo por isso aparece com uma cor mais clara!

![Exemplo de autores no Obsidian](/assets/images/obsidian_author_example.png)

Um detalhe interessante adicional sobre isto é que funciona através de todos os tipos de tópicos.
Se criar-mos notas sobre muitos tópicos diferentes, podemos ficar surpreendidos que as mesmas pessoas e detalhes podem estar presentes em todo o lado.
No meu caso, fiquei surpreendido ao descobrir que o autor de um livro de estoicismo que estava a ler, Massimo Pigliucci, era também o autor de um artigo de biologia evolutiva que li para o doutoramento.
Que mundo pequeno, provavelmente.
