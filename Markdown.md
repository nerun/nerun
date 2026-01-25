# Referência Rápida de Markdown

**Por** Daniel Dias Rodrigues  
**Última atualização:** Qua, 21 Jan 2026 10:47 -0300

---

## Blocos de comentário

```txt
<!--
  Isto é um bloco de comentário.
  
  Ele não será renderizado pela maioria dos
  programas.
-->
```

---

## Imagens

```txt
![alt](url/path "mouseover")
```

- **alt**: é o texto alternativo, exibido quando o carregamento da imagem falha.
- **url**: `https://www.dominio.com.br`
- **path**: `/usr/share/icons/gnome/32x32/apps/accessories-text-editor.png`
- **mouseover**: texto exibido ao passar o mouse sobre a imagem

Exemplo:

```txt
![imagem exemplo](/usr/share/icons/gnome/32x32/apps/accessories-text-editor.png "um ícone padrão do gnome")
```

Renderiza como:

<img src="data:image/png;base64,
iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABHNCSVQICAgIfAhkiAAAAAlwSFlz
AAAN1wAADdcBQiibeAAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAAARdEVY
dFRpdGxlAFRleHQgRWRpdG9yPXIhCgAAABR0RVh0QXV0aG9yAEpha3ViIFN0ZWluZXLm+/cvAAAA
IXRFWHRTb3VyY2UAaHR0cDovL2ppbW1hYy5tdXNpY2hhbGwuY3ppZuNeAAAGQklEQVRYw9VXa0yT
VxhGt+zmDzfNliVbtoiVSDSYZXOC9yVTsrkfTpfMGafGFZSCliBRiS6iohZEERWVIJotU4ckM4Mt
us1lIpRCoXcUFi4CpTegX+8XSum7856P76NIm6FL5tbkyXl7ztfzPO9z3vd8EJOcnBzzNPFUyf/7
AgBgymPGUyPNP5GAisqK3TcqK5w4Tiq+UVFF4hCO4fNPLKC9o91ntpihWdHknmQMGDc1yyF8/rEE
SCSSt04VFzYWnipwVP9UBU6XAypuXId/Ep+/cM5ZVFwox73/VsDJohMXmxXyEfIBScFxaFRIIZ+M
k4mPSY7S+DgZw+dDoRC6MnKqqKAUOZjY2OnM3LkbbfHxm0EgeH6cgNNnTkqdTgd4vW64dLkMtqel
QDkZJxPnHNgHwtRtsJ+M4fPDwwHAPXFvc0LCNOv8+SrLypVu++rVLiYhQTNOALGqzefzkh/YiQgP
GI1GssEw+P2+CXEwODHWarUT5j0eF+Ce5/IPdZYczQ2czM+D6pw90F1cDMyCBd5HjiDfjIodDhsw
zCDYbNZRMGC3c7DR9ciwj2JszuVygsNqhpL8/aFKUhMM2etsoQSqszKBmTfPP07AMUmeB88fiUgt
QG3d3VHUUChVTZRAqWqmQKfYWEFtViiboE56jwJjXHdaTXDnyHqoLBLD+bMSuFxeCkfyDsM3+7JD
THz8Gp48Nzd36uG83BC5QKgAq3UgDIO8I0jEOeIilY6OIDBTHHGNXScOWC3QdvA9MJxZASP3MsB0
bR2cOJEHRYVH4ap4+5VxXZCTkzOzoFAyhFWLGzTKZWFZKvjMVGoFJdNolAQqcLtddJTW11Jwc06G
kOe+P0qeDs7vPwFj2Vo4dyw7VHZQWDahDYmAuPOlJW48ArSZzXgsSy4zXKMEaC9xw+Nx05FzAmOX
bQD+PJQIhmKOfA2YCLlGOM1XmZ28N+I9sGdPVuLV69+5gsEgJa+XSUezruWzY1EHapIltqpGqyLP
1VFgjJ2jUTaAcm8C9J1eBiM1Y+TKlFfghxRBVtSLKDM7c01VdZUbWw2z5jK22Wx8dmwH2OkRYGux
TjgoMPY4GWg7nETIl7Pk1z8G06VPQZv2KvxSsteXIRYnRxUgzhJvvlvzhw/bcHBwgM8Ys0WbMUME
Emt1auqQrEFKYg3te41KDpoD74L+9AoI1ojGkVsbKuHO73e8op2iL6IKSN+ZntmsaB4OBIZINk6+
ktmb0UMzRPh8PirI5WK/45rfbYf2gg9BX7QcgnfTCPlHlFwneg0GpNcgEAgQsbJAqmhHRlQBOzJE
ea1trTA05GftJCQIJMCsEZgpAp9BoFjEYP1FsFTvgpHGr1ny8nWgJeRdty+CXq+H/v5+ci8oQ9tS
hQejChCJ06/09HQTAj/06rtpsXEFhpbTq5bY3dBYD7oWLSVuua+jsNzaDX59PYSGvWC5ugWUqTPg
x/w0IH8TEOt/owIwuZS07ReiC9iV8bPFYqFE6AB3tXKthvPsUbipG1grKFYhvQ3H01eCU1sBll/3
g/GmEGpLc0Amk4FOpyPvBAP5vYckpUcBN2NiYp4hmDLxCNJFcoax0s07O9v5tsLssdhkDZi5hs+8
Ud5AsWntMpj58ksg+3YXtNw6C61qKbUdOwVbGrsKX0qYnHBHqpSQv0DwHMGzVAwn4KvUlA6nE9uL
LbjwVsOYLTgvFcC64aUFqSXvfSTAGxQgREcEXmgoANdwtDIMbBVua31EwFRewKatWwbRqmjFxxYe
W3RoP5tZkBAFKRlHHEkAPovJbdz8pRHtj3gEn23Y4Mcz5ToABXAi2OoPr/wAb224iPEI8keAgtGt
9Rs+d0UsQvJ58YNVq4CxW0HXqgLtAyUBuXjuk5FCxYPOPRj7rnugDltXg24U2hbyvUUNmhZ23tJv
BsIRRNsjCXhzYWIiDJDXp2XAxMPcb6QwWQxgMveBkcBgYtFn7IU+Qy/oDT3Q24fohh7Svt29Dyke
9nRBV3cndD3sgM6uDjq3MCkpRLhmRBLw+iKymLRkCXBIDMfSUdB4KY+oz0cCeX7R4sUoYHrEe+CN
WbMWvC0QJHGYPXv24jAs4RAbG7uUw6y4uGUc4sIwZ86c5RwEAsEKBM6T8Z3/1/+G/wb+Au/ZeDVF
bVNDAAAAAElFTkSuQmCC"
alt="imagem exemplo"
title="um ícone padrão do gnome"
/>

---

## Títulos

```
# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6
```

---

## Negrito e Itálico

`**negrito**` ou `__negrito__`

`*itálico*` ou `_itálico_`

---

## Linhas

Em uma única linha, use um desses:

- 3 hífens: `---`
- 3 asteriscos: `***`
- 3 underscores: `___`

---

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

---

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

---

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

---

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

---

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

---

## Código

Código de uma linha: <code>\`lorem ipsum\`</code>

Código em bloco:

    ```linguagem
    código
    ```

---

## HTML

Markdown suporta HTML muito bem, quando se quer algo mais complexo ou que não funciona no renderizador que voce usa, o HTML sempre funciona.

---

## Símbolos UTF-8 úteis

| símbolo          | código      | ícone     |
|------------------|:-----------:|:---------:|
| seta esquerda    | `&larr;`    | &larr;    |
| seta direita     | `&rarr;`    | &rarr;    |
| emoticon mão esq | `&#128072;` | &#128072; |
| emoticon mão dir | `&#128073;` | &#128073; |

Para outros símbolos, consulte [UTF-8](https://www.w3schools.com/charsets/ref_utf_basic_latin.asp).
