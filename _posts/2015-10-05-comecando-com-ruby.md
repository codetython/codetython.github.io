---
layout: post
title: "Começando com Ruby"
date: 2015-10-10 01:00 PM
image: '/assets/img/'
description: 'Guia de iniciação da linguagem Ruby.'
author: pablo
tags:
- ruby
- iniciante
categories:
- Ruby
- Iniciantes
twitter_text: 'Começando com Ruby.'
---

## Introdução

### O que é Ruby?

Ruby é uma linguagem de programação criada nos anos 90 por <a href="https://github.com/matnn" target="_blank">Yukihiro Matsumoto</a> com o objetivo de ser uma linguagem fácil e poderosa,
com forte influência no <a href="https://www.smalltalk.org/main/" target="_blank">SmallTalk</a> e <a href="https://www.python.org/" target="_blank">Python</a>, Ruby se torna uma linguagem muito legal de trabalhar,
pois sua syntax é muito amigável, olhe o exemplo abaixo:
{% highlight ruby %}
print "Hello" unless 2 > 1
{% endhighlight %}

Sim, é um exemplo bem simples e não muito "real", mas só para nível de
entendimento, o que faz o código acima?  
Vamos ler:  
print (Imprima) "Hello" unless (a menos que) 2 > 1  

Viram como é simples?  
Esse é um dos objetivos do Ruby :)

### Instalação

#### MacOSX
No Mac o Ruby já vem instalado, basta abrir o Terminal e digitar `irb` que
abrirá o console iterativo do Ruby.

#### Linux
No Linux você pode rodar o comando:
(Para distribuições Debian/Ubuntu)
{% highlight ruby %}
sudo apt-get install ruby-full
{% endhighlight %}
(Para distribuições Fedora/CentOS)
{% highlight ruby %}
sudo yum install ruby
{% endhighlight %}

#### Windows
No Windows a melhor forma de instalar é baixando o <a href="http://rubyinstaller.org/" target="_blank">RubyInstaller</a>.

## O Básico

Em Ruby tudo é um objeto, e também ele tem uma tipagem fraca, ou seja, você não precisa dizer ao Ruby
que tipo de dado você quer armazenar em uma variável, simplesmente coloque o
dado, o Ruby sabe o que você quer :D.
Exemplo:
{% highlight ruby %}
name = "Pablo"
age = 20
skills = %w(ruby rails javascript)
{% endhighlight %}

Estou armazenando uma String na variável `name`, um Integer na variável `age` e
um Array na variável `skills`, experimente digitar o seguinte no irb:  
{% highlight ruby %}
name.class

# => String
{% endhighlight %}

O método `class` retorna o tipo do objeto da varíavel, pois como falamos em
Ruby tudo é um objeto.




