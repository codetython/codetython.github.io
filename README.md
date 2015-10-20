## Codetython

### Como contribuir

1. [Install Jekyll](http://jekyllrb.com)
2. Fork o [Codetython](https://github.com/codetython/codetython.github.io/fork)
3. Clone o repositório que você forkou.
4. Editar o `_config.yml` e adicionar suas informações iguais as que já existem.
5. Olhe como é a estrutura de posts em `_posts`, copie e faça igual. 
6. Leia a documentação abaixo para saber mais sobre como contribuir.
7. **Lembre sempre de compilar os assets com Gulp.**


### Criando posts.

Quando você criar um novo post, você precisa preencher as informações do post, siga o exemplo abaixo:

```
---
layout: post
title: "Como usar"
date: 2015-10-14 03:32:44
image: '/assets/img/'
description: 'Sobre o post.'
author: pablo
tags:
- php 
- ruby 
categories:
- Rails
twitter_text: 'Como escrever posts.'
---
```

### Múltiplos contribuidores

Você pode escrever um post em conjunto com mais alguém, basta ter seus dados e os dados da pessoa que está contribuindo no arquivo `_config.yml` e adicionar o seguinte nas informações do post:
```
---
layout: post
title: "Como usar"
date: 2015-10-14 03:32:44
image: '/assets/img/'
description: 'Sobre o post.'
contributors:
- pablo
- ralph
- iago
tags:
- php 
- ruby 
categories:
- Rails
twitter_text: 'Como escrever posts.'
---
```

### Executando o blog localmente.

Compile os assets dessa forma:

- Instalar o [NodeJS](https://nodejs.org/)
- Execute `npm install` 
- Execute `gulp`
