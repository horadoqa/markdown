# Blocos de Código

Blocos de código são usados para exibir trechos de código de forma formatada e legível.

Você pode criá-los utilizando três crases (```) ou indentação com quatro espaços.

---

## Usando crases (recomendado)

Você também pode especificar a linguagem para habilitar destaque de sintaxe.

Código:

````markdown id="k2j4dn"
```javascript
let message = 'Olá, mundo';
alert(message);
````

````

Resultado:

```javascript
let message = 'Olá, mundo';
alert(message);
````

---

## Sem especificar linguagem

Código:

```markdown id="v91l2p"
```

Texto simples sem destaque de sintaxe

```
```

Resultado:

```
Texto simples sem destaque de sintaxe
```

---

## Usando indentação (4 espaços)

Código:

```markdown id="n3m8xa"
    let message = 'Olá, mundo';
    alert(message);
```

Resultado:

```
let message = 'Olá, mundo';
alert(message);
```

---

## Dicas

* Prefira usar crases (```) ao invés de indentação
* Sempre que possível, informe a linguagem (`javascript`, `html`, `css`, etc.)
* Isso melhora a legibilidade e o destaque do código

---
