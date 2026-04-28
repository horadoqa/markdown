# Imagem

Imagens podem ser adicionadas no Markdown para ilustrar conteúdos, diagramas ou exemplos visuais.

Embora o Markdown tenha uma sintaxe própria para imagens, também é comum usar HTML para controle mais preciso de alinhamento e estilo.

---

## Usando HTML (com alinhamento)

Código:

```html id="img1a9"
<div align="center">
<img src="../images/markdown.jpg" alt="Imagem Markdown">
</div>
```

Resultado:

<div align="center">
<img src="../images/markdown.jpg" alt="Imagem Markdown">
</div>

---

## Sintaxe padrão do Markdown

Código:

```markdown id="img2b8"
![Imagem Markdown](../images/markdown.jpg)
```

Resultado:

![Imagem Markdown](../images/markdown.jpg)

---

## Imagem com texto alternativo (alt)

O atributo `alt` é importante para acessibilidade e também aparece caso a imagem não carregue.

Código:

```markdown id="img3c7"
![Descrição da imagem Markdown](../images/markdown.jpg)
```

Resultado:

![Descrição da imagem Markdown](../images/markdown.jpg)

---

## Imagem com título (tooltip)

Você pode adicionar um título que aparece ao passar o mouse.

Código:

```markdown id="img4d6"
![Imagem Markdown](../images/markdown.jpg "Clique para ampliar")
```

Resultado:

![Imagem Markdown](../images/markdown.jpg "Clique para ampliar")

---

## Imagem com tamanho (via HTML)

O Markdown puro não controla tamanho de imagem, mas HTML permite isso.

Código:

```html id="img5e5"
<img src="../images/markdown.jpg" alt="Imagem Markdown" width="300">
```

Resultado:

<img src="../images/markdown.jpg" alt="Imagem Markdown" width="300">

---

## Dicas

* Sempre use `alt` para acessibilidade
* Prefira Markdown puro quando não precisar de estilos avançados
* Use HTML apenas quando precisar de controle (alinhamento, tamanho, etc.)
* Evite imagens muito grandes para não prejudicar a leitura

---
