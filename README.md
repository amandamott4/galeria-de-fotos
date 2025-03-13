# CSS-galeria-de-fotos

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
- `<samp>`: exemplo de código
- `<section>`: seção
- `<select>`: caixa de seleção
- `<small>`: texto pequeno
- `<source>`: fonte para elementos de mídia
- `<span>`: contêiner genérico
- `<strong>`: texto forte
- `<style>`: estilo interno
- `<sub>`: subscrito
- `<summary>`: resumo para `<details>`
- `<sup>`: sobrescrito
- `<table>`: tabela
- `<tbody>`: corpo da tabela
- `<td>`: célula da tabela
- `<template>`: modelo
- `<textarea>`: área de texto
- `<tfoot>`: rodapé da tabela
- `<th>`: cabeçalho de célula
- `<thead>`: cabeça da tabela
- `<time>`: tempo
- `<title>`: título do documento
- `<tr>`: linha da tabela
- `<track>`: faixa de texto para mídia
- `<ul>`: lista não ordenada
- `<video>`: vídeo

---

### ATRIBUTO ALT

O atributo alt da imagem deve descrever o conteúdo da imagem. Leitores de tela anunciam o texto alternativo no lugar das imagens. Se a imagem não puder ser carregada, este texto será apresentado no lugar da imagem.

---

### VISUALIZAÇÃO E DIMENSÃO DOS ELEMENTOS

Para visualizar melhor como seus elementos são dimensionados, adicionar uma borda pode ser útil.

Dê ao elemento `.gallery` uma largura de 50% e uma borda de 5px sólida vermelha.

Então, dê aos elementos `img` uma largura de 100%, preenchimento de 5px e uma borda de 5px sólida azul.

---

### CALCULAÇÃO DE TAMANHO COM BORDER E PADDING

Quando você adiciona uma borda ou um preenchimento (padding) a um elemento em HTML, ele pode ficar maior do que você esperava. Isso ocorre porque o navegador, por padrão, adiciona esses valores ao tamanho do conteúdo do elemento.

**Exemplo:**

Imagine que você tem uma caixa com 100 pixels de largura e adiciona 10 pixels de borda e 20 pixels de preenchimento (10 pixels de cada lado). Então, a largura total da caixa será:

100 (conteúdo) + 10 (bordas) + 20 (preenchimento) = 130 pixels.

---

### PROPRIEDADE BOX-SIZING

A propriedade box-sizing pode mudar a forma como essa largura é calculada.

**Valores possíveis:**
- `border-box`: O tamanho total do elemento, incluindo padding e border, será a largura explícita definida. O conteúdo do elemento encolherá para dar espaço ao padding e border.
- `content-box`: O tamanho do conteúdo é usado para calcular a largura, e a borda e o preenchimento são somados a isso.

---

### UTILIZAÇÃO DO SELETOR GLOBAL

O seletor global * é usado para aplicar estilos a todos os elementos da página. Portanto, ao definir box-sizing explicitamente para content-box com o seletor global, você está garantindo que todos os elementos usarão o modelo content-box.

```css
* {
  box-sizing: content-box;
}
```

---

### FLEXBOX E SUAS PROPRIEDADES

**Flexbox** é um layout CSS unidimensional que pode controlar a maneira como os itens são espaçados e alinhados dentro de um contêiner.

**Para usar Flexbox:**
Atribua uma propriedade display de `flex` a um elemento. Isso fará com que o elemento se torne um contêiner flex. Qualquer filho direto de um contêiner flex é chamado de item flex.

---

### EIXO PRINCIPAL E EIXO CRUZADO

O Flexbox possui um eixo principal e um eixo cruzado. O eixo principal é definido pela propriedade flex-direction, que possui quatro valores possíveis:

- `row` (padrão): eixo horizontal com itens flex de esquerda para direita.
- `row-reverse`: eixo horizontal com itens flex de direita para esquerda.
- `column`: eixo vertical com itens flex de cima para baixo.
- `column-reverse`: eixo vertical com itens flex de baixo para cima.

---

### PROPRIEDADE FLEX-WRAP

A propriedade `flex-wrap` determina como seus itens flex se comportam quando o contêiner flex é pequeno demais. Defini-la como `wrap` permitirá que os itens se ajustem à próxima linha ou coluna. `nowrap` (padrão) impedirá que seus itens se ajustem e os reduzirá se necessário.

---

### PROPRIEDADE JUSTIFY-CONTENT

A propriedade `justify-content` determina como os itens dentro de um contêiner flex são posicionados ao longo do eixo principal, afetando sua posição e o espaço ao redor deles.

---

### PROPRIEDADE ALIGN-ITEMS

A propriedade `align-items` posiciona o conteúdo flex ao longo do eixo transversal. Neste caso, com sua flex-direction definida como row, seu eixo transversal seria vertical.

---

### PROPRIEDADE OBJECT-FIT

A propriedade `object-fit` determina como as imagens devem se comportar. Você pode usar essa propriedade para ajustar como as imagens devem preencher o contêiner img enquanto mantém a proporção, resultando em um corte para ajustar.

```css
.gallery img {
  object-fit: cover;
}
```

---

### PROPRIEDADE GAP

A propriedade abreviada `gap` do CSS define os espaços, também conhecidos como `gutters`, entre linhas e colunas. A propriedade gap e suas subpropriedades row-gap e column-gap fornecem essa funcionalidade para layouts flex, grid e multi-coluna. Você aplica a propriedade ao elemento contêiner.

```css
.gallery {
  display: flex;
  gap: 16px;
}
```

---

### PROPRIEDADE BORDER-RADIUS

Suavize suas imagens um pouco, dando ao seletor `.gallery img` uma propriedade `border-radius` com o valor de 10px.

```css
.gallery img {
  border-radius: 10px;
}
```

---

### PSEUDO-ELEMENTO ::AFTER

O pseudo-elemento `::after` cria um elemento que é o último filho do elemento selecionado. Você pode usá-lo para adicionar um elemento vazio após a última imagem. Se você der a ele a mesma largura das imagens, ele empurrará a última imagem para a esquerda quando a galeria estiver em um layout de duas colunas. No momento, ela está no centro porque você definiu justify-content: center no contêiner flex.

**Exemplo de Código:**

```css
.container::after {
  content: "";
  width: 860px; /* Ajuste este valor conforme necessário */
}
```
