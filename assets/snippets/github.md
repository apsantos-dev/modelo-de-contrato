# Snippets - Sublime Text 3

> Lista de snippets utilizados para modelar os arquivos ( .md ). Crie um novo arquivo para cada snippet e insira os códigos referente a cada um. Salve o arquivo com a extensão: `nome-do-arquivo.sublime-snippet`

Para criar um novo snippet, clique em: `Tools > Developer > New Snippet...`
Insira o código referente ao snippet que deseja criar e salve o arquivo.
Após salvar o arquivo, faça um teste. Digite a `tabTrigger` e pressione a tecla TAB.

**Exemplo de tabTrigger**: `md-title`

## Título

```javascript
<snippet>
  <content><![CDATA[
# ${1:title}
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-title</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Subtítulo

```javascript
<snippet>
  <content><![CDATA[
## ${1:Subtítulo}
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-caption</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Negrito

```javascript
<snippet>
  <content><![CDATA[
**${1:texto em negrito}**
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-bold</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Itálico

```javascript
<snippet>
  <content><![CDATA[
*${1:texto em itálico}*
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-italic</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Informação

```javascript
<snippet>
  <content><![CDATA[
> ${1:Informação}
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-note</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Código curto

```javascript
<snippet>
  <content><![CDATA[
`${1:Código curto}`
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-shortcode</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Código longo

```javascript
<snippet>
  <content><![CDATA[
(```)
${1:Código longo}
(```)

// remova as ()
// coloque apenas ```

]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-longcode</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## link

```javascript
<snippet>
  <content><![CDATA[
[${1:texto}](${2:https://github.com/})
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-link</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Lista ordenada

```javascript
<snippet>
  <content><![CDATA[
- [${1:texto}](${2:https://github.com/})
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-list</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Tag <pre>

```javascript
<snippet>
  <content><![CDATA[
<pre>
  ${1:...}
</pre>
]]></content>
  <!-- Optional: Set a tabTrigger to define how to trigger the snippet -->
  <tabTrigger>md-pre</tabTrigger>
  <!-- Optional: Set a scope to limit where the snippet will trigger -->
  <!-- <scope>source.python</scope> -->
</snippet>
```

## Lista de snippets criados:

- md-title
- md-caption
- md-bold
- md-italic
- md-note
- md-shortcode
- md-longcode
- md-link
- md-list
- md-pre

## Versão

> Release: 1.0.1
