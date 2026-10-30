---
layout: post
title:  "Fazer um website"
date:   2022-10-21
categories: jekyll update code site
lang: pt
---

Este post server maioritariamente para ficar mais confortável a postar online.
Também estou a usar este post para partilhar como construi esta página.

## Encontrar um sítio para colocar o website

Originalmente, procurei maneiras de "hospedar" um website em casa ou talvez "na nuvem".
Mas todas as opções que encontrei requeriam algum tipo de conhecimento em como gerir um website.
Depois, aprendi sobre [GitHub Pages][github-pages] que me pareceu uma boa opção para comecar e aprender como fazer isto.

## Como pôr isto online

Como foi descrito no link, é tão simples como criar um repositorio com o nosso *username*, e podemos comecar a trabalhar
Por exemplo, para fazer este website, criei o repositório *marioasmira/marioasmira.github.io* que está a ser publicado em [marioasmira.github.io][this].
Este website, no entanto, precisaria de ser escrito em HTML e CSS, e não sou super familiar com estas línguas...
Decidi então seguir a sugestão dada pelo link e usar [Jekyll][jekyll].

Jekyll é uma forma interessante de transformar ficheiros de texto [Markdown][markdown-wiki] num website estático, que é exatamente o que eu queria.
Depois de escolher onde e como publicar estas páginas, foi relativamente simples seguir os [guias][jekyll-guide].

## Coisas interessantes

Podemos importar imagens.
Por example, aqui está uma imagem de um ovo de *DRosophila melanogaster* sobre microscópio onde as camadas de cores ficaram desfasadas:

![ovo](/assets/images/1_ant_28_45.png)

Também podemos mostrar código de forma organizada.
Em C++:

``` c++
#include <iostream>
int main(){
  std::cout << "Hello world!" << std::endl;
  return 0;
}
```

E em Python:

``` python
print("Hello world!")
```

## Conclusão

Isto parece ser uma forma relativamente simples e barata de fazer um website, por isso acho que vou continuar a postar mais projetos que tenha feito e venha a fazer.
Mas sem promessas!

Até breve.

[this]: https://marioasmira.github.io/
[github-pages]: https://pages.github.com/
[jekyll]: https://jekyllrb.com/
[markdown-wiki]: https://en.wikipedia.org/wiki/Markdown
[jekyll-guide]: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
