# Links

Links permitem direcionar o usuário para páginas externas ou internas dentro do seu documento.

---

## Sintaxe básica

Código:

```markdown id="l2p9sx"
- [Markdown Live Preview](https://markdownlivepreview.com/)
```

Resultado:

* [Markdown Live Preview](https://markdownlivepreview.com/)

---

## Link com título (tooltip)

Você pode adicionar um texto extra que aparece ao passar o mouse sobre o link.

Código:

```markdown id="w8d3ka"
- [Markdown Live Preview](https://markdownlivepreview.com/ "Clique para visualizar o Markdown ao vivo")
```

Resultado:

* [Markdown Live Preview](https://markdownlivepreview.com/ "Clique para visualizar o Markdown ao vivo")

---

## Links internos

Usados para navegar dentro do próprio documento (âncoras).

Código:

```markdown id="c5n1zr"
- [Ir para Tabelas](#tabelas)
```

Resultado:

* [Ir para Tabelas](#tabelas)

---

## Links com referência

Permitem reutilizar URLs e deixar o Markdown mais organizado.

Código:

```markdown id="q7m4ty"
- [Markdown Live Preview][preview]

[preview]: https://markdownlivepreview.com/
```

Resultado:

* [Markdown Live Preview][preview]

[preview]: https://markdownlivepreview.com/

---

## Links automáticos

Algumas plataformas convertem URLs automaticamente em links clicáveis.

Código:

```markdown id="r9x6bd"
https://markdownlivepreview.com/
```

Resultado:

[https://markdownlivepreview.com/](https://markdownlivepreview.com/)

---

## Dicas

* Use textos descritivos no lugar de "clique aqui"
* Prefira links com referência em documentos longos
* Verifique se os links internos correspondem exatamente aos títulos
* Utilize títulos (tooltip) quando quiser fornecer mais contexto

---
