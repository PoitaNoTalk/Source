## Artigo

By FabasaPro for Social<br /><sup>Publicado 19 Jun 2023 8h49 &#x22EE; Atualizado 19 Jun 2023 8h49</sup>

## Sintaxe

Repete um bloco de instruções enquanto uma condição é verdadeira ou até que uma condição se torne verdadeira.

`DO` [ { `WHILE` | `UNTIL` } _condição_ ]<br />
&nbsp;&nbsp;&nbsp;&nbsp;_bloco-instruções_<br />
`LOOP`<br />

`DO`<br />
&nbsp;&nbsp;&nbsp;&nbsp;_bloco-instruções_<br />
`LOOP` [ { `WHILE` | `UNTIL` } _condição_ ]<br />

A parte da _condição_ é tipo [`Boolean`]() [ { _verdadeiro_ | _falso_ } ]. As expressões **_enquanto i < 10_** ou **_até i > 10_** são avaliadas como [`True`](), diferente de zero, ou [`False`](), igual a zero.

## Exemplo
```basic
Dim i = 0
Do While i < 10 ' enquanto i < 10
    i = i + 1
Loop
```
```basic
Dim i = 0
Do
    i = i + 1
Loop Until i > 10 ' até i > 10
```

## Consulte
- [`Exit`](https://github.com/poitanotalk/source/vb/exit.md)
- [`For`...`Next`](https://github.com/poitanotalk/source/vb/fornext.md)
- [`While`...`Wend`](https://github.com/poitanotalk/source/vb/whilewend.md)

---

[`Blogs`](https://github.com/fabasapro/wikis/blogs) &#x22EE; [`Tutoriais`](https://github.com/fabasapro/wikis/tutorials) &#x22EE; [`Contribuir`](https://github.com/fabasapro/wikilinks/pulls) &#x22EE; [`Termos de Uso`](LICENSE)

<sup><b>Copyright © 1996-2023 Fábio Santos. All rights reserved.</b></sup>
