# markdown

## Cabeçalhos

# Este é um Cabeçalho h1
## Este é um Cabeçalho h2
###### Este é um Cabeçalho h6

## Ênfase

*Este texto ficará em itálico*  
_Este também ficará em itálico_

**Este texto ficará em negrito**  
__Este também ficará em negrito__

_Você **pode** combiná-los_

## Listas

### Não ordenada

* Item 1
* Item 2
* Item 2a
* Item 2b
    * Item 3a
    * Item 3b

### Ordenada

1. Item 1
2. Item 2
3. Item 3
    1. Item 3a
    2. Item 3b

## Listas com formatação
Você pode adicionar diferentes níveis de listas e usar formatação dentro delas.

Exemplo com listas aninhadas e formatação:
markdown
Copiar
1. Item 1
2. Item 2
   * _Item 2a em itálico_
   * **Item 2b em negrito**
3. Item 3

## Tarefas de Listas
Se você está criando uma lista de tarefas (por exemplo, um checklist), pode usar caixas de seleção.

Exemplo de Lista de Tarefas:
markdown
Copiar
- [x] Tarefa concluída
- [ ] Tarefa pendente

## Imagens

![Este é um texto alternativo.](/image/sample.webp "Esta é uma imagem de exemplo.")

## Links

Você pode estar utilizando o [Markdown Live Preview](https://markdownlivepreview.com/).

Links com títulos
Você pode adicionar um título a um link, que aparecerá como um tooltip quando o usuário passar o mouse sobre ele.

markdown
Copiar
[Markdown Live Preview](https://markdownlivepreview.com/ "Clique para visualizar o Markdown ao vivo")

## Citações

> Markdown é uma linguagem de marcação leve com sintaxe de formatação de texto simples, criada em 2004 por John Gruber com Aaron Swartz.
>
>> Markdown é frequentemente usado para formatar arquivos README, para escrever mensagens em fóruns de discussão online e para criar texto enriquecido usando um editor de texto simples.

## Tabelas

| Colunas à esquerda | Colunas à direita |
| ------------------ |:----------------:|
| foo à esquerda     | foo à direita    |
| bar à esquerda     | bar à direita    |
| baz à esquerda     | baz à direita    |

## Blocos de código

```
let message = 'Olá mundo';
alert(message);
```

## Código em linha

Este site está utilizando `markedjs/marked`.

## Criando Caixa de Texto

```html
<button onclick="document.getElementById('myTextBox').style.display = 'block'">Clique para mostrar a caixa de texto</button>
<textarea id="myTextBox" style="display:none;" rows="4" cols="50"></textarea>
```
