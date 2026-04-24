# 🌐 Aula 7 — Semântica e Formatação de Textos em HTML

---

## 🧠 O que é Semântica?

Semântica está relacionada ao **significado** das palavras, símbolos e elementos.

👉 No contexto do HTML:

* Não importa apenas **como algo parece**
* Importa **o que aquilo significa**

---

## ⚠️ HTML antigo vs HTML moderno

No HTML4, o foco era muito mais em **aparência (forma)**.

Por isso existiam tags como:

* `bgcolor="red"`
* `<center>`
* `<marquee>`

👉 Essas práticas hoje são consideradas **obsoletas**.

---

## ✅ HTML5: foco em semântica

No HTML5, o foco mudou:

* **HTML** → significado (semântica)
* **CSS** → aparência (estilo)

👉 Separação de responsabilidades (muito importante!)

---

## 📍 Exemplo prático (endereço)

### ❌ Forma antiga (não semântica):

```html id="ex01"
<p>Eu moro na <u>Rua dos Capixabas, 229 - Botafogo - RJ</u></p>
```

👉 Aqui usamos `<u>` apenas para estilo (sublinhar)

---

### ✅ Forma correta (semântica):

```html id="ex02"
<p>Eu moro na <address>Rua dos Capixabas, 229 - Botafogo - RJ</address></p>
```

👉 Agora estamos dizendo ao navegador:
**“isso é um endereço”**

---

## ⚠️ Fique atento

Algumas tags podem se tornar obsoletas com o tempo.

👉 Por isso:

* Sempre se atualize
* Consulte documentações oficiais

---

## ✍️ Principais formatações de texto

---

## 🔠 Negrito (Bold)

### ❌ Não semântico:

```html id="b01"
<b>Texto em negrito</b>
```

👉 Apenas muda a aparência

---

### ✅ Semântico:

```html id="b02"
<strong>Texto importante</strong>
```

👉 Indica **importância** (significado)

---

## ✒️ Itálico / Ênfase

### ❌ Não semântico:

```html id="i01"
<i>Texto em itálico</i>
```

---

### ✅ Semântico:

```html id="i02"
<em>Texto com ênfase</em>
```

👉 Indica **ênfase no conteúdo**

---

## 🧠 Conclusão importante

* `<b>` e `<i>` ainda funcionam
* Mas são heranças do HTML4
* Não agregam significado

👉 Prefira sempre:

* `<strong>`
* `<em>`

---

## 🖍️ Marca-texto (Highlight)

Podemos destacar textos com:

```html id="mark01"
<mark>Texto destacado</mark>
```

👉 Por padrão:

* Cor amarela
* Definida pelo navegador

---

## 🎨 Alterando a cor (CSS)

HTML define **significado**, não estilo.

Para mudar a aparência, usamos CSS.

---

### ✔️ Estilo inline (uso pontual):

```html id="mark02"
<mark style="background-color: lime;">Texto destacado</mark>
```

---

### ✔️ Estilo interno (recomendado para reutilização):

```html id="mark03"
<head>
  <style>
    mark {
      background-color: limegreen;
    }
  </style>
</head>
```

---

## ⚠️ Boa prática

* Para mudanças rápidas → **inline**
* Para reutilização → **CSS interno ou externo**

👉 Em projetos maiores:

* Use arquivos externos (`style.css`)

---

## 🧠 Resumo Final

Semântica em HTML significa dar **sentido ao conteúdo**, e não apenas aparência. Com a evolução para HTML5, práticas antigas focadas em estilo foram substituídas por elementos semânticos. Tags como `<strong>` e `<em>` devem ser preferidas, pois agregam significado ao conteúdo. Já o CSS é responsável por toda a parte visual, mantendo o código mais organizado e profissional.

---
