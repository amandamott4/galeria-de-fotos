# CSS-galeria-de-fotos

Claro, aqui está a documentação organizada por tópicos em português, com títulos em maiúsculas e separados por linha:

---

### META TAGS

Uma meta tag é um elemento HTML usado para fornecer metadados sobre uma página da web. Esses metadados são informações que não são exibidas diretamente na página, mas podem ser utilizadas pelos navegadores, mecanismos de busca e outros serviços web para entender melhor o conteúdo e o comportamento da página.

**Exemplos comuns de meta tags:**

**Definir a codificação de caracteres:**

```html
<meta charset="UTF-8">
```

**Configurar a viewport para sites responsivos:** Configurar a viewport é uma parte essencial do desenvolvimento de sites responsivos. A viewport é a área visível de uma página da web em um dispositivo, e sua configuração adequada garante que o site seja exibido corretamente em diferentes tamanhos de tela, como em dispositivos móveis, tablets e desktops.

A meta tag viewport é usada para controlar as dimensões e a escala da viewport.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

**Fornecer uma descrição da página para os mecanismos de busca:**

```html
<meta name="description" content="Esta é uma descrição da minha página da web.">
```

**Especificar palavras-chave para os mecanismos de busca:**

```html
<meta name="keywords" content="HTML, CSS, JavaScript, desenvolvimento web">
```

**Definir o autor da página:**

```html
<meta name="author" content="Nome do Autor">
```

**Configurar a tag de revisão (revisit-after):**

```html
<meta name="revisit-after" content="7 days">
```

---

### HEADER

A `<header>` é uma tag que representa uma seção de cabeçalho para um documento ou uma seção dele. Um cabeçalho normalmente contém informações introdutórias ou de navegação. Pode incluir elementos como logotipos, títulos, menus de navegação, entre outros.

**Diferença entre head e header:**

**`<head>`:** Contém metadados e elementos que não são exibidos diretamente ao usuário, mas são importantes para o funcionamento e configuração do documento HTML. Inclui elementos como `<title>`, `<meta>`, `<link>`, `<style>`, `<script>`, etc.

**`<header>`:** Contém elementos de cabeçalho que são exibidos diretamente ao usuário, como títulos, logotipos e menus de navegação.

---

### DIV

A tag `<div>` em HTML é uma abreviação de "division" e é usada para agrupar e organizar blocos de conteúdo. Serve como um contêiner genérico, útil para aplicar estilos e layouts com CSS, ou manipular conteúdo com JavaScript.

**Estrutura da Página:** Criar a estrutura de uma página web, dividindo-a em várias seções, como cabeçalho, conteúdo principal, barra lateral, rodapé, etc.

**Agrupamento de Elementos:** Usar `<div>` para agrupar elementos relacionados, como seções de texto, imagens e outros conteúdos, facilitando o gerenciamento e a estilização.

---

### IMG

A tag `<img>` em HTML é um exemplo de uma tag que não requer um elemento de fechamento. Ela é chamada de "self-closing tag" ou "void element." A tag `<img>` é usada para incorporar imagens em uma página web, e seus atributos fornecem informações adicionais necessárias para exibir a imagem corretamente.

**Lista das tags "self-closing" (ou "void elements") em HTML:**

- `<br>`: Insere uma quebra de linha.
- `<hr>`: Insere uma linha horizontal.
- `<img>`: Insere uma imagem.
- `<input>`: Define um campo de entrada de dados em um formulário.
- `<meta>`: Define metadados sobre um documento HTML.
- `<link>`: Define uma relação entre o documento atual e um recurso externo (como folhas de estilo CSS).
- `<source>`: Especifica múltiplas fontes para elementos de mídia, como `<video>` ou `<audio>`.
- `<col>`: Especifica atributos para uma ou mais colunas em um `<colgroup>` de uma tabela.

---

### SELETORES

Img não precisa de ponto no início para ser um seletor. Isso acontece porque um seletor pode ser usado para estilizar elementos HTML diretamente pelo nome da tag, sem a necessidade de um ponto. O ponto (.) é utilizado para selecionar classes, e a cerquilha (#) é usada para selecionar IDs.

Quando você quer estilizar todas as instâncias de um determinado elemento HTML (como todas as imagens), você simplesmente usa o nome da tag como seletor. Isso é conhecido como seletor de elemento ou seletor de tipo.

**Lista das tags que não precisam de (.) para ser um seletor:**

- `<a>`: link
- `<abbr>`: abreviação
- `<address>`: endereço
- `<article>`: artigo
- `<aside>`: seção lateral
- `<audio>`: áudio
- `<b>`: negrito
- `<blockquote>`: citação em bloco
- `<body>`: corpo do documento
- `<button>`: botão
- `<canvas>`: área de desenho
- `<caption>`: legenda de tabela
- `<cite>`: citação
- `<code>`: código
- `<col>`: coluna de tabela
- `<colgroup>`: grupo de colunas de tabela
- `<data>`: dado
- `<datalist>`: lista de dados
- `<dd>`: definição de descrição
- `<details>`: detalhes
- `<dfn>`: definição
- `<dialog>`: diálogo
- `<div>`: divisão
- `<dl>`: lista de definições
- `<dt>`: termo de definição
- `<em>`: ênfase
- `<fieldset>`: conjunto de campos
- `<figcaption>`: legenda da figura
- `<figure>`: figura
- `<footer>`: rodapé
- `<form>`: formulário
- `<h1>` até `<h6>`: títulos de diferentes níveis
- `<header>`: cabeçalho
- `<hr>`: linha horizontal
- `<html>`: documento HTML
- `<i>`: itálico
- `<iframe>`: quadro inline
- `<img>`: imagem
- `<input>`: entrada de dados
- `<label>`: rótulo
- `<legend>`: legenda
- `<li>`: item de lista
- `<link>`: link para recurso externo
- `<main>`: conteúdo principal
- `<mark>`: marcação
- `<meta>`: metadados
- `<nav>`: navegação
- `<object>`: objeto incorporado
- `<ol>`: lista ordenada
- `<p>`: parágrafo
- `<picture>`: imagem responsiva
- `<pre>`: texto pré-formatado
- `<progress>`: progresso de uma tarefa
- `<q>`: citação curta
- `<s>`: texto tachado
