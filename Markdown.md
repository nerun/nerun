# Referência Rápida de Markdown

**Por** Daniel Dias Rodrigues  
**Última atualização:** Sex, 6 fev 2026 10:38 -0300

## Blocos de comentário

```markdown
<!--
  Isto é um bloco de comentário.
  
  Ele não será renderizado pela maioria dos
  programas.
-->
```

## Títulos

```markdown
# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6
```

## Negrito, Itálico e Riscado

```markdown
**negrito** ou __negrito__

*itálico* ou _itálico_

~~riscado~~
```

## Linhas

Em uma única linha, use um desses:

- 3 hífens: `---`
- 3 asteriscos: `***`
- 3 underscores: `___`

## Tabelas

Não é preciso usar o pipe "|" à esquerda ou direita da tabela, só no meio.
As colunas nem mesmo precisam estar alinhadas.
Esse é o design mínimo:

```markdown
esquerda | centro | direita
:--------|:------:|---------:
a        | b      | c
```

esquerda | centro | direita
:--------|:------:|---------:
a        | b      | c

Onde `:` indica o alinhamento do conteúdo

## Listas

Lita não numeradas podem ser feitas com `+`, `-` ou `*`, e `4 espaços` definem uma sublista:

```markdown
- Lorem ipsum
    - dolor sit amet
        - consectetur adipiscing elit
```

- Lorem ipsum
    - dolor sit amet
        - consectetur adipiscing elit

Nas listas numeradas a diferença é o uso de números. Você pode até usar "1" em todos, que ele corrige a sua numeração:

```markdown
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

```markdown
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

```markdown
> [!caution]
> Sample Caution Callout Style

> [!important]
> Sample Important Callout Style

> [!note]
> Sample Note Callout Style

> [!tip]
> Sample Tip Callout Style

> [!warning]
> Sample Warning Callout Style
```

> [!caution]
> Sample Caution Callout Style

> [!important]
> Sample Important Callout Style

> [!note]
> Sample Note Callout Style

> [!tip]
> Sample Tip Callout Style

> [!warning]
> Sample Warning Callout Style

## Links e Notas de Rodapé

```markdown
[Um link para br.lipsum.com](https://br.lipsum.com)
```

[Um link para br.lipsum.com](https://br.lipsum.com)

```markdown
[Um link de rodapé][1] (não confundir com nota de rodapé) costuma ser útil quando se quer reutilizar o mesmo link.

[1]: https://www.gurpzine.com.br
```

[Um link de rodapé][1] (não confundir com nota de rodapé) costuma ser útil quando se quer reutilizar o mesmo link.

[1]: https://www.gurpzine.com.br

```markdown
Uma nota de rodapé[^1] costuma funcionar no GitHub e em alguns renderizadores.

[^1]: Nota de rodapé.
```

Uma nota de rodapé[^1] costuma funcionar no GitHub e em alguns renderizadores.

[^1]: Nota de rodapé.

## Imagens

```markdown
![alt](url/path "mouseover")
```

- **alt**: é o texto alternativo, exibido quando o carregamento da imagem falha.
- **url**: `https://www.dominio.com.br`
- **path**: `media/markdown.png`
- **mouseover**: texto exibido ao passar o mouse sobre a imagem

Exemplo:

```markdown
![imagem exemplo](media/markdown.png "ícone da linguagem markdown")
```

Renderiza como:

![imagem exemplo](media/markdown.png "ícone da linguagem markdown")

No fundo, imagens são como links, você pode usar link de rodapé também:

```markdown
![imagem exemplo][1]

[1]: media/markdown.png
```

## Código

Código de uma linha: <code>\`lorem ipsum\`</code>

Código em bloco:

    ```linguagem
    código  
    ```

O bloco de código também pode ser criado apenas inserindo 4 espaços antes de cada linha do código:

```
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
