# Maratona Explorer 1

![preview](./assets/preview.png)

> Maratona Explorer

Projeto construído na Maratona Explorer 1 da Rocketseat.

[🔗 Clique aqui para acessar ()]

## 🛠 Tecnologias Utilizadas

- HTML
- CSS
- Javascript
&nbsp;

## Explicando as Tecnologias Utilizadas na Maratona

> **O que é HTML?**

HTML ou Hyper Text Markup Languag,que em tradução livre quer dizer: **Linguagem de Marcação de Hipertexto**.

O HTML é um componente básico da web, ele posibilita inserir o conteúdo e estabelecer a estrutura básica de um website. O HTML é necessario para dar significado e organizar as informações de uma página web que serão lidas e exibidas pelo navegador web.  

Os hipertextos são elementos conectados, que podem ser palavras, imagens, vídeos, documentos, entre outros. 

> **Como funciona o HTML?**

Para um documento HTML ser valido e poder ser lido pelo navegador web, o documento precisa ter a extensão **.html**. O navagedor web faz a leitura do arquivo e renderiza seu conteúdo para que o usuário final possa visualizá-lo. Os arquivos **.html** podem ser lido por qualquer navegador web (como: Goolgle Chrome, Safari, Mozilla ou Opera).

> **Estrutura básica de um documento HTML**

A estrutura básica do documento HTML é composta pelas tags:

`<!DOCTYPE html>`

Essa tag informa ao navegador que o HTML a ser lido é a sua versão 5 

`<html>`

A tag **`<html>`** é a tag root ou a tag raiz do documento HTML e precisa ser fechada.

`<head>`

É tag que receberá as informações básicas do documento HTML, como título do documento, links externos, metadados, etc.

`<body>`

Essa tag é o corpo do documento HTML, onde ficarão os elementos que serão renderizados na tela pelo navegador, como imagem, vídeos, textos, listas entre outros.

Por fim, temos a estrutura básica de um documento HTML:

```
<!DOCTYPE html>
<html>
  <head>
    <title>Titulo da Página</title>
  </head>
  <body>
    <p>Aqui é o corpo</p>
  </body>
</html> 

```
---

> **O que é CSS?**

CSS é a sigla para o termo em inglês Cascading Style Sheets que, em tradução livre quer dizer Folha de Estilo em Cascata. O CSS é utilizado com o HTML e sua extensão de arquivo precisa ter o nome **.css**.

Básicamente o CSS separa o conteúdo do visual de uma página web ou site. De forma bem simple utilizando o CSS é possível alterar a cor do texto, mudar a cor de fundo, trocar o tipo de fonte e controlar espaçamento entre os elementos HTML.

Com o CSS também é possível ajustar imagens e colocar animações e trasições em elementos HTML.

>**Como funciona o CSS?**

O CSS usa uma sintaxe simples que é baseada em inglês aplicado ao um conjuto de regras especifico para o css.

Um comando CSS básico é composto por seletor e declarações que contém propriedade e valor.

**SELETOR {PROPRIEDADE:VALOR}**

O **seletor** seleciona quais elemetos em HTML receberão a propriedade. A **propriedade** pode ser a cor, o tamanho do texto ou sua cor de fundo, e por ultimo sera passado o **valor**, que vai determinar o valor da **propriedade**.

Digamos que seu objetivo é mudar o tamanho da fonte de uma tag `<p>` que é utilizada para representar um parágrafo. Para isso podemos fazer da seguinte forma p {font-size: 20px;}.

- p é o **seletor**. Nesse caso ele seleciona a tag `<p>`
- font-size - é a declarção que contém a **propriedade** (font-size) e seu **valor** é 20px e devemos finalizar com ponto e virgula.


> **Formas de Inserir o CSS**

O CSS pode ser inserido no HTML de três formas diferentes, podemos ter o CSS inserido de forma  **Interno**, de forma **Externo** e **Inline**.

> **CSS Inline**

Para inseir o CSS de forma inline, ele pode ser inserido usando a tag `<style>` dentro de uma tag HTML.

**Exemplo:**

`<p style="color: red;">Meu texto</p>`

O elemento `<p>` recebera a cor vermelha.

> **CSS Interno**

Para inserir o CSS de forma Interno, é necessário colocar a tag `<style>` dentro da tag `<head>`.

**Exemplo:**

```
<head>
  <style>
    p {
      color: red;
    }
  </style>
</head>
<body>
  <p>Meu texto</p>
</body>
```
Todos os elementos `<p>` receberão a cor vermelha.

> **CSS Externo**

E por fim o CSS pode ser inserido de forma externo, apartir de um arquivo **.css**. Isso possibilita escrever o css em um arquivo separado e aplicar os estilos CSS a qualquer página desejada, além de mantendo a organização do código.

```
<head>
 <link rel="stylesheet" href="./css/style.css">
</head>
```
---
> **O que é Javascript**

Javascript básicamente é o que torna as páginas web mais interativas e dinamicas, podendo controlar imagens, animações, múltimídia, fazer validações de formulário, calculos e muitas outras coisas legais. Javascript é uma linguagem de programação interpretada e muito poderosa.

>**Como inserir o Javascript no HTML**

O javascript pode ser inserido no documento HTML apartir da tag `<script>`.

Javascript pode também ser incorporado a partir de um arquivo externo com a extesão **.js**.

**Exemplo**

```
<head>
  <script src"./JS/revelarDestino.js"></script>
</head>
```
> **Exemplo de código Javascript**

`alert("Olá, Tudo bem ai?)`

Esse comando exibira um pop-up com a mensagem: Olá, tudo bem ai?

---



***Por fim esse foi um resumo de tudo que aprendi nessa Maratona Incrível da Rocketseat***

## ✉️ Contato

dienens.00@outlook.com
