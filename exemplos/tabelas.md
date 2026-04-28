# Tabelas

Tabelas em Markdown são usadas para organizar dados em linhas e colunas de forma simples e legível.

Você pode definir o alinhamento das colunas utilizando `:` na linha de separação.

---

## Sintaxe básica

Código:

```markdown id="t9k2q1"
| Colunas à esquerda | Colunas centralizadas |
|--------------------|:---------------------:|
| foo                | bar                   |
| baz                | qux                   |
```

Resultado:

| Colunas à esquerda | Colunas centralizadas |
| ------------------ | :-------------------: |
| foo                |          bar          |
| baz                |          qux          |

---

## Alinhamento de colunas

* `:---` → Alinhado à esquerda
* `:---:` → Centralizado
* `---:` → Alinhado à direita

Código:

```markdown id="d4p8zm"
| Esquerda | Centro | Direita |
|:---------|:------:|--------:|
| A        | B      | C       |
| D        | E      | F       |
```

Resultado:

| Esquerda | Centro | Direita |
| :------- | :----: | ------: |
| A        |    B   |       C |
| D        |    E   |       F |

---

## Intercalando linhas (efeito visual)

O Markdown puro não possui suporte nativo para “linhas zebras” (intercaladas), mas você pode simular esse efeito usando HTML (quando suportado pela plataforma).

Código:

```markdown id="8z1mya"
<table>
  <tr>
    <th>Item</th>
    <th>Valor</th>
  </tr>
  <tr style="background-color: #f2f2f2;">
    <td>Item 1</td>
    <td>10</td>
  </tr>
  <tr>
    <td>Item 2</td>
    <td>20</td>
  </tr>
  <tr style="background-color: #f2f2f2;">
    <td>Item 3</td>
    <td>30</td>
  </tr>
</table>
```

Resultado:

<table>
  <tr>
    <th>Item</th>
    <th>Valor</th>
  </tr>
  <tr style="background-color: #f2f2f2;">
    <td>Item 1</td>
    <td>10</td>
  </tr>
  <tr>
    <td>Item 2</td>
    <td>20</td>
  </tr>
  <tr style="background-color: #f2f2f2;">
    <td>Item 3</td>
    <td>30</td>
  </tr>
</table>

---

## Tabela com formatação

Você pode usar formatação dentro das células.

Código:

```markdown id="m2v7kf"
| Nome   | Destaque        |
|--------|-----------------|
| João   | **Negrito**     |
| Maria  | _Itálico_       |
| Pedro  | `Código`        |
```

Resultado:

| Nome  | Destaque    |
| ----- | ----------- |
| João  | **Negrito** |
| Maria | *Itálico*   |
| Pedro | `Código`    |

---

## Dicas

* Use espaços para melhorar a legibilidade do código (opcional)
* Tabelas simples funcionam na maioria das plataformas
* Recursos avançados (cores, estilos) dependem de HTML e suporte da ferramenta
* Evite tabelas muito largas para não prejudicar a leitura

---
