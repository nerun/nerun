# Referência Rápida de Markdown

**Por** Daniel Dias Rodrigues  
**Última atualização:** Qua, 21 Jan 2026 10:47 -0300

## Blocos de comentário

```txt
<!--
  Isto é um bloco de comentário.
  
  Ele não será renderizado pela maioria dos
  programas.
-->
```

## Imagens

```txt
![alt](url/path "mouseover")
```

- **alt**: é o texto alternativo, exibido quando o carregamento da imagem falha.
- **url**: `https://www.dominio.com.br`
- **path**: `media/markdown.png`
- **mouseover**: texto exibido ao passar o mouse sobre a imagem

Exemplo:

```txt
![imagem exemplo](media/markdown.png "ícone da linguagem markdown")
```

Renderiza como:

![imagem exemplo](media/markdown.png "ícone da linguagem markdown")

## Títulos

```
# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6
```

## Negrito e Itálico

`**negrito**` ou `__negrito__`

`*itálico*` ou `_itálico_`

## Linhas

Em uma única linha, use um desses:

- 3 hífens: `---`
- 3 asteriscos: `***`
- 3 underscores: `___`

## Tabelas

```txt
| esquerda | centro | direita  |
|:---------|:------:|---------:|
| a        | b      | c        |
```

| esquerda | centro | direita  |
|:---------|:------:|---------:|
| a        | b      | c        |

Onde `:` indica o alinhamento do conteúdo

## Listas

Lita não numeradas podem ser feitas com `+`, `-` ou `*`, e `4 espaços` definem uma sublista:

```txt
- Lorem ipsum
    - dolor sit amet
        - consectetur adipiscing elit
```

- Lorem ipsum
    - dolor sit amet
        - consectetur adipiscing elit

Nas listas numeradas a diferença é o uso de números. Você pode até usar "1" em todos, que ele corrige a sua numeração:

```txt
1. Lorem ipsum
    1. dolor
    2. sit amet
2. consectetur adipiscing elit
    1. sed do eiusmod
    2. tempor incididunt ut labore
```

1. Lorem ipsum
    1. dolor
    2. sit amet
2. consectetur adipiscing elit
    1. sed do eiusmod
    2. tempor incididunt ut labore

## Citação ou Blockquote

```txt
> Lorem ipsum
>> dolor sit amet
>>> consectetur adipiscing elit...
```

A renderização varia. Alguns vão exibir um _blockquote_ simples, sem decoração, outros algo mais decorado:

> Lorem ipsum
>> dolor sit amet
>>> consectetur adipiscing elit...

Por isso chamei de "citação", porque nos fóruns quando se cita uma resposta aparece uma barra vertical na esquerda com a pergunta original.

### Alertas

Alerta é um tipo especial de _blockquote_ que costuma renderizar apenas no GitHub:

#### GitHub

```txt
> [!Note]
> Sample Note Callout Style

> [!Tip]
> Sample Tip Callout Style

> [!Warning]
> Sample Warning Callout Style
```

> [!Note]
> Sample Note Callout Style

> [!Tip]
> Sample Tip Callout Style

> [!Warning]
> Sample Warning Callout Style

#### Em qualquer outro lugar

Pode-se improvisar algo parecido ou até melhor com a notação HTML:

```html
<div style="border-left: 5px solid #ffd700;
    background: #ffffce; padding: 10px;
    margin: 10px 0; color: #000000;">
    &#128161; <strong>Dica:</strong> Lorem ipsum dolor sit amet.
</div>
```

<div style="border-left: 5px solid #ffd700;
    background: #ffffce; padding: 10px;
    margin: 10px 0; color: #000000;">
    &#128161; <strong>Dica:</strong> Lorem ipsum dolor sit amet.
</div>

```html
<div style="border-left: 5px solid #2196F3;
    background: #f0f8ff; padding: 10px;
    margin: 10px 0; color: #000000;">
    &#128221; <strong>Nota:</strong> Lorem ipsum dolor sit amet.
</div>
```

<div style="border-left: 5px solid #2196F3;
    background: #f0f8ff; padding: 10px;
    margin: 10px 0; color: #000000;">
    &#128221; <strong>Nota:</strong> Lorem ipsum dolor sit amet.
</div>

```html
<div style="border-left: 5px solid #FF9800;
    background: #fff3e0; padding: 10px;
    margin: 10px 0; color: #000000;">
    &#9888;&#65039; <strong>Aviso:</strong> Lorem ipsum dolor sit amet.
</div>
```

<div style="border-left: 5px solid #FF9800;
    background: #fff3e0; padding: 10px;
    margin: 10px 0; color: #000000;">
    &#9888;&#65039; <strong>Aviso:</strong> Lorem ipsum dolor sit amet.
</div>

## Links e Notas de Rodapé

```txt
[Um link para br.lipsum.com](https://br.lipsum.com)
```

[Um link para br.lipsum.com](https://br.lipsum.com)

```txt
[Um link de rodapé][1] (não confundir com nota de rodapé) costuma ser útil quando se quer reutilizar o mesmo link.

[1]: https://www.gurpzine.com.br
```

[Um link de rodapé][1] (não confundir com nota de rodapé) costuma ser útil quando se quer reutilizar o mesmo link.

[1]: https://www.gurpzine.com.br

```txt
Uma nota de rodapé[^1] costuma funcionar no GitHub e em alguns renderizadores.

[^1]: Nota de rodapé.
```

Uma nota de rodapé[^1] costuma funcionar no GitHub e em alguns renderizadores.

[^1]: Nota de rodapé.

## Código

Código de uma linha: <code>\`lorem ipsum\`</code>

Código em bloco:

    ```linguagem
    código
    ```

## HTML

Markdown suporta HTML muito bem, quando se quer algo mais complexo ou que não funciona no renderizador que voce usa, o HTML sempre funciona.

## Símbolos UTF-8 úteis

| símbolo          | código      | ícone     |
|------------------|:-----------:|:---------:|
| seta esquerda    | `&larr;`    | &larr;    |
| seta direita     | `&rarr;`    | &rarr;    |
| emoticon mão esq | `&#128072;` | &#128072; |
| emoticon mão dir | `&#128073;` | &#128073; |

Para outros símbolos, consulte [UTF-8](https://www.w3schools.com/charsets/ref_utf_basic_latin.asp).
