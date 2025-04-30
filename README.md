# Dicas sobre Markdown

<div align="center">
<img src="./images/markdown.jpg" alt="Imagem Markdown">
</div>

## Cabeçalhos

```markdown
# Este é um cabeçalho h1
## Este é um cabeçalho h2
### Este é um cabeçalho h3
#### Este é um cabeçalho h4
##### Este é um cabeçalho h5
###### Este é um cabeçalho h6
```

Exemplo:

# Este é um cabeçalho h1  
## Este é um cabeçalho h2  
### Este é um cabeçalho h3  
#### Este é um cabeçalho h4  
##### Este é um cabeçalho h5  
###### Este é um cabeçalho h6  

---

## Ênfase

```markdown
*Este texto ficará em itálico*  
_Este também ficará em itálico_

**Este texto ficará em negrito**  
__Este também ficará em negrito__

_Você **pode** combiná-los_
```

---

## Listas

### Não ordenada

```markdown
* Item 1
* Item 2
  * Item 2a
  * Item 2b
    * Item 3a
    * Item 3b
```

Exemplo:

* Item 1  
* Item 2  
  * Item 2a  
  * Item 2b  
    * Item 3a  
    * Item 3b  

---

### Ordenada

```markdown
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

Exemplo:

1. Item 1  
2. Item 2  
3. Item 3  
   1. Item 3a  
   2. Item 3b  

---

### Listas com formatação

Você pode adicionar diferentes níveis de listas e usar formatação dentro delas.

```markdown
1. Item 1
2. Item 2
   * _Item 2a em itálico_
   * **Item 2b em negrito**
3. Item 3
```

---

## Lista de Tarefas

Se você está criando uma lista de tarefas (por exemplo, um checklist), pode usar caixas de seleção:

```markdown
- [x] Tarefa concluída
- [ ] Tarefa pendente
```

Exemplo:

- [x] Tarefa concluída  
- [ ] Tarefa pendente  

---

## Imagens

```markdown
![Este é um texto alternativo.](./images/markdown.jpg)
```

Exemplo:

![Este é um texto alternativo.](./images/markdown.jpg)

---

## Alinhamento de Imagens

```markdown
<div align="center">
<img src="./images/markdown.jpg" alt="Imagem Markdown">
</div>
```

Exemplo:

<div align="center">
<img src="./images/markdown.jpg" alt="Imagem Markdown">
</div>

---

## Links

```markdown
[Markdown Live Preview](https://markdownlivepreview.com/)

[Markdown Live Preview](https://markdownlivepreview.com/ "Clique para visualizar o Markdown ao vivo")
```

---

## Citações

```markdown
> Markdown é uma linguagem de marcação leve com sintaxe de formatação de texto simples, criada em 2004 por John Gruber com Aaron Swartz.
>
>> Markdown é frequentemente usado para formatar arquivos README, escrever mensagens em fóruns e criar texto enriquecido em editores simples.
```

Exemplo:

> Markdown é uma linguagem de marcação leve com sintaxe de formatação de texto simples, criada em 2004 por John Gruber com Aaron Swartz.  
>
>> Markdown é frequentemente usado para formatar arquivos README, escrever mensagens em fóruns e criar texto enriquecido em editores simples.

---

## Tabelas

```markdown
| Colunas à esquerda | Colunas centralizadas |
|--------------------|:---------------------:|
| foo                | bar                   |
| baz                | qux                   |
```

Exemplo:

| Colunas à esquerda | Colunas centralizadas |
|--------------------|:---------------------:|
| foo                | bar                   |
| baz                | qux                   |

---

## Blocos de Código

Para blocos de código, use crase tripla (\`\`\`) ou indentação com quatro espaços:

```javascript
let message = 'Olá, mundo';
alert(message);
```

---

## Código em Linha

Use uma crase simples para destacar trechos de código em linha:

```markdown
Este site está utilizando `markedjs/marked`.
```

Exemplo:

Este site está utilizando `markedjs/marked`.

---

## Criando uma Caixa de Texto com HTML

```html
<button onclick="document.getElementById('myTextBox').style.display = 'block'">
  Clique para mostrar a caixa de texto
</button>
<textarea id="myTextBox" style="display:none;" rows="4" cols="50"></textarea>
```

Exemplo:

<button onclick="document.getElementById('myTextBox').style.display = 'block'">Clique para mostrar a caixa de texto</button>  
<textarea id="myTextBox" style="display:none;" rows="4" cols="50"></textarea>


## Dropdown

```markdown
<details>
<summary>Conhecimento das melhores ferramentas para garantir que o software seja sempre de alta qualidade.</summary>

  - [**Selenium**](https://www.selenium.dev/): Automação de navegadores para testes de aplicações web.
  - [**Robot Framework**](https://robotframework.org/): Framework de automação de testes baseado em palavras-chave.
  - [**Cypress**](https://www.cypress.io/): Framework moderno para testes end-to-end de aplicações web.
  - [**Playwright**](https://playwright.dev/): Framework para automação de testes em múltiplos navegadores.
  - [**Postman**](https://www.postman.com/): Postman é sua plataforma única para desenvolvimento colaborativo de API. 
  - [**k6**](https://grafana.com/docs/k6/latest/): O Grafana k6 é uma ferramenta de teste de carga extensível, de código aberto e fácil de usar para desenvolvedores.
</details>
```

Exemplo:

<details>
<summary>Conhecimento das melhores ferramentas para garantir que o software seja sempre de alta qualidade.</summary>

  - [**Selenium**](https://www.selenium.dev/): Automação de navegadores para testes de aplicações web.
  - [**Robot Framework**](https://robotframework.org/): Framework de automação de testes baseado em palavras-chave.
  - [**Cypress**](https://www.cypress.io/): Framework moderno para testes end-to-end de aplicações web.
  - [**Playwright**](https://playwright.dev/): Framework para automação de testes em múltiplos navegadores.
  - [**Postman**](https://www.postman.com/): Postman é sua plataforma única para desenvolvimento colaborativo de API. 
  - [**k6**](https://grafana.com/docs/k6/latest/): O Grafana k6 é uma ferramenta de teste de carga extensível, de código aberto e fácil de usar para desenvolvedores.
</details>