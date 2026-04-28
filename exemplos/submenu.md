# 1. Menu com submenu (Markdown puro)

```markdown id="m1"
# Menu

- [Introdução](#introdução)
- [Instalação](#instalação)
- [Uso](#uso)
  - [Básico](#uso-básico)
  - [Avançado](#uso-avançado)
- [Exemplos](#exemplos)
- [FAQ](#faq)

---

## Introdução

Texto da introdução.

## Instalação

Instruções de instalação.

## Uso

### Uso Básico
Explicação simples de uso.

### Uso Avançado
Explicação mais detalhada.

## Exemplos

Exemplos práticos.

## FAQ

Perguntas frequentes.
```

---

# 2. Menu estilo “GitHub Pages / documentação”

Esse formato fica bem comum em README de projetos:

```markdown id="m2"
## 📚 Índice

1. [Introdução](#introdução)
2. [Instalação](#instalação)
3. [Como usar](#como-usar)
   - [Primeiros passos](#primeiros-passos)
   - [Configuração avançada](#configuração-avançada)
4. [Exemplos](#exemplos)
5. [Contribuição](#contribuição)

---

## Introdução
Conteúdo aqui.

## Instalação
Conteúdo aqui.

## Como usar

### Primeiros passos
Conteúdo aqui.

### Configuração avançada
Conteúdo aqui.

## Exemplos
Conteúdo aqui.

## Contribuição
Conteúdo aqui.
```

---

# 3. Menu “colapsável” (HTML dentro do Markdown)

Isso funciona muito bem em GitHub, Notion (parcialmente) e páginas HTML:

```markdown id="m3"
<details>
  <summary>📌 Menu do conteúdo</summary>

- [Introdução](#introdução)
- [Instalação](#instalação)
- [Uso](#uso)
  - [Básico](#uso-básico)
  - [Avançado](#uso-avançado)
- [Exemplos](#exemplos)
- [Conclusão](#conclusão)

</details>

---

## Introdução
Texto da introdução.

## Instalação
Texto da instalação.

## Uso

### Uso Básico
Texto.

### Uso Avançado
Texto.

## Exemplos
Texto.

## Conclusão
Texto final.
```

---

## Dica importante

Se quiser garantir que as âncoras funcionem em qualquer lugar (GitHub, MkDocs, etc.), evite:

* acentos inconsistentes
* espaços duplos
* caracteres especiais

Exemplo:

* `## Uso Básico` → `#uso-básico`

---
