# Guanabara_HTML5_CSS3
 Documentação simplificada para HTML5 e CSS3, usando como base o "Curso HTML5 e CSS3" do "Curso em Vídeo"

*HTML é uma linguagem de marcação para a internet, sua sigla significa *HyperText Markup Language* ou *“Linguagem de Marcação de Hipertexto”*.

```html
ESTRUTURA
<elemento atributo="">Conteúdo</elemento> 
```

# \<head\> #

### \<link\> ###

```html
DEFINIÇÃO:
Define o tipo de relacão entre o documento e a fonte externa

EXEMPLO DE LINK CSS
<head>
	<link rel="stylesheet" href="style.css">
</head>

EXEMPLO DE LINK FAVICON
<head>
	<link rel="icon" type="image/x-icon" href="logo.ico">
</head>
```

| Attribute | Value | Description |
| --- | --- | --- |
| href | URL | Especifica a localização de um documento linkado. |
| rel | stylesheet | Especifica a relação entre o documento atual e o documento linkado. |
| type | media_type | Especifica o tipo de media do documento linkado |

# \</head\> #

# \<body\> #

### \<p\> ###

```html
DEFINIÇÃO:
Parágrafo

EXEMPLO:
<p>conteúdo do parágrafo</p>
```

### <br>

```html
DEFINIÇÃO:
Quebra de linha

EXEMPLO:
Linha 1 **<br>** Linha 2

RESULTADO:
Linha 1
Linha 2
```

### <img>

```html
DEFINIÇÃO:
Imagens

EXEMPLO:
<img src="imagem.png" alt="texto alternativo">
```

### <h1>

```html
DEFINIÇÃO:
Indicar o grau de importância de títulos

EXEMPLO:
<h1>Títulos de maior importância</h1>
<h2>Títulos de segunda maior importância</h2>
<h3>Títulos de terceira maior importância</h3>
<h4>Títulos de quarta maior importância</h4>
<h5>Títulos de quinta maior importância</h5>
<h6>Títulos de sexta maior importância</h6>

```

### <strong> e <em>

```html
DEFINIÇÃO:
strong e ênfase são usados para definir importância semântica aos elementos.
Se o efeito desejado for apenas estético, o uso do CSS é recomendado.

EXEMPLO:
<strong>Texto importante</strong>
<em>Texto importante</em>

RESULTADO:
Texto importante**
*texto importante*
```

### Outras tags de formatação:

```html
<mark>texto marcado</mark>
<del>texto deletado</del>
<ins>Texto inserito</ins>
<sub>Texto sobrescrito</sub>
<sup>Texto subscrito</sup>
<code>Código</code>
<q>citação em linha</q>
<blockquote>Citação em bloco</blockquote>
<abbr title="abreviação">ABBR</abbr>
```

### <ol> e <ul>

```html
DEFINIÇÃO:
ol - lista ordenada
ul - lista não ordenada

EXEMPLO:
<ol>
<li>item 1</li>
<li>item 2</l1>
</ol>

<ul>
<li>item 1</li>
<li>item 2</l1>
</ul>**
```

| Attribute | Description |
| --- | --- |
| type=”a” ou type=”A” | ordem alfabética (a para minusculas e A para maisculas) |
| type=”i” ou type=”I” | ordem em algarismos romanos (i para minusculas e I para maisculas) |
| type=”1” | ordem númerica |

### <a>

```html
DEFINIÇÃO:
tag "âncora", define a ligação entre hyperlinks

EXEMPLO:
<a href="https://www.sitedeexemplo.com">clique aqui para vistar o site</a>
```

| Attribute | Description |
| --- | --- |
| type=”_blank” | abre o link em uma janela em branco |
| type=”_self” | abre o link na janela atual |
| rel=”next” | indica que o link é o próximo do documental atual |
| rel=”prev” | indica que o link é o anterior do documental atual |
| rel=”external” | indica que o link é de sites externos |

# \</body\> #
