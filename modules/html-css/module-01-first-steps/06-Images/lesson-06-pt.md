# 🌐 Aula 6 — Imagens e Favicon

---

## ⚠️ Direitos autorais (Copyright)

Um ponto extremamente importante no desenvolvimento web é o uso de conteúdos de terceiros.

👉 Imagens, vídeos e outros arquivos **podem possuir direitos autorais**

Se utilizados de forma incorreta, isso pode gerar:

* Problemas legais
* Remoção de conteúdo
* Penalizações

---

## ✅ Solução: usar imagens livres

Uma alternativa segura é utilizar imagens **free/copyright-free**.

Exemplo de plataforma:

* Unsplash

📌 Observação:
Mesmo em plataformas gratuitas, sempre verifique:

* Licença de uso
* Necessidade de atribuição

---

## 🖼️ Formatos de imagem para Web

Os formatos mais comuns são:

* **JPEG/JPG**
* **PNG**
* **GIF**
* **SVG**
* **TIFF** (pouco usado na web por ser pesado)

---

## 🤔 Qual formato usar?

👉 Depende da aplicação:

* **JPEG**

  * Mais leve
  * Ideal para fotos
  * Maior compressão (perde um pouco de qualidade)

* **PNG**

  * Melhor qualidade
  * Suporte à transparência
  * Arquivos maiores que JPEG

* **GIF**

  * Suporta animações
  * Qualidade limitada

* **SVG**

  * Vetorial (não perde qualidade ao aumentar)
  * Ideal para ícones e logos

---

## ⚠️ Dica essencial

👉 **Evite imagens pesadas!**

Imagens muito grandes:

* Deixam o site lento
* Prejudicam a experiência do usuário
* Afetam SEO

---

## 📏 Tamanho e resolução das imagens

Se uma imagem for muito grande (ex: 3840x2160):

👉 Solução:

* Redimensionar
* Comprimir
* Escolher o formato adequado

Quanto menor o tamanho (sem perder qualidade relevante), melhor para o site.

---

## 🧩 Como adicionar imagens no HTML

Utilizamos a tag:

```html id="img01"
<img src="" alt="">
```

### Atributos:

* `src` → caminho/origem da imagem
* `alt` → descrição da imagem (acessibilidade + SEO)

---

## 📁 Exemplos de uso

### Mesma pasta:

```html id="img02"
<img src="logo-html.png" alt="Logo HTML">
```

### Pasta diferente:

```html id="img03"
<img src="assets/logo-css.png" alt="Logo CSS">
```

### Imagem da internet:

```html id="img04"
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d4/JavaScript-shield.svg" alt="Logo JavaScript">
```

📌 Importante:
O caminho precisa estar **correto** (relativo ou absoluto).

---

## 🎨 Ajustando tamanho da imagem

Por padrão, a imagem aparece no tamanho original.

Você pode:

* Editar em ferramentas externas
* Ou usar CSS (recomendado, veremos mais à frente)

---

## ⭐ O que é Favicon?

Favicon é o ícone que aparece na aba do navegador.

Exemplo:

* Aba do YouTube → nome + ícone

---

## 🧩 Como adicionar um favicon

### 1. Escolher um ícone

Plataformas úteis:

* IconArchive
* Favicon.io
* Favicon.cc

👉 Formato recomendado:

* `.ico` (mais compatível)

---

### 2. Adicionar no HTML

Dentro da tag `<head>`:

```html id="fav01"
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

---

## 🧠 Como tudo isso funciona?

Relembrando:

1. Você acessa um site
2. O servidor envia HTML + CSS + imagens
3. O navegador carrega esses arquivos
4. As imagens são exibidas na tela

👉 Ou seja:
As imagens fazem parte dos **recursos carregados pelo navegador**

---

## 🧠 Resumo Final

No desenvolvimento web, o uso correto de imagens é essencial tanto para desempenho quanto para legalidade. Devemos utilizar formatos adequados, otimizar o tamanho dos arquivos e sempre respeitar direitos autorais. Além disso, elementos como o favicon ajudam na identidade visual do site. Tudo isso contribui para uma melhor experiência do usuário.
