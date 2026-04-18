# 🌐 Aula 4 — Como Funcionam HTML e CSS

---

## ❗ HTML e CSS são linguagens de programação?

Existe uma dúvida muito comum:

```
“Eu programo em HTML e CSS”
```

Essa afirmação **não está correta**.

* HTML e CSS **não são linguagens de programação**
* São **linguagens de marcação e estilo**

📌 O correto é dizer:
**“Eu desenvolvo com HTML e CSS”**

---

## 🧾 O que é HTML?

HTML significa:

* **HyperText (Hipertexto)** → textos com links clicáveis
* **Markup Language (Linguagem de Marcação)**

👉 Ou seja: o HTML é responsável por **estruturar o conteúdo**

### Exemplos de conteúdo:

* Textos
* Imagens
* Vídeos
* Listas
* Tabelas

---

## 🎨 O que é CSS?

CSS significa:

* **Cascading Style Sheets (Folhas de Estilo em Cascata)**

👉 O CSS é responsável pelo **design do site**

### Exemplos:

* Cores
* Tamanhos
* Fontes
* Espaçamentos
* Posicionamento

---

## 🧠 E o JavaScript?

Existe um terceiro elemento essencial:

👉 JavaScript

* Responsável pela **interatividade**
* É o “cérebro” do site

### Exemplos:

* Menus interativos
* Animações
* Validações de formulário
* Pop-ups

---

## ⚙️ A tríade do desenvolvimento web

* **HTML** → Estrutura (conteúdo)
* **CSS** → Aparência (design)
* **JavaScript** → Comportamento (interação)

👉 Essas três tecnologias são a base de qualquer site moderno.

---

## 🏗️ Como funciona o HTML?

HTML é baseado em **tags (marcações)**.

### Estrutura de uma tag:

* Abertura → `<h1>`
* Conteúdo → `Título`
* Fechamento → `</h1>`

### Exemplo:

```html
<h1>Exemplo de título</h1>
<p>Exemplo de parágrafo</p>
```

---

## 🧩 Tags sem fechamento

Algumas tags não possuem fechamento.

### Exemplo:

```html
<img src="foto.png" alt="Exemplo de foto">
```

### Explicação:

* `src` → caminho da imagem (source)
* `alt` → texto alternativo (acessibilidade)

---

## 🎨 Como funciona o CSS?

O CSS funciona com **seletores e declarações**.

### Exemplo:

```css
h1 {
  font-family: Arial;
  font-size: 20pt;
  color: blue;
}
```

### Estrutura:

* **Seletor** → `h1`
* **Declarações** → dentro das `{}`
* **Propriedade** → `color`
* **Valor** → `blue`

👉 Cada linha é um par: **propriedade + valor**

---

## 📄 Estrutura básica de um documento HTML

Essa estrutura é obrigatória:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>

<body>
  <h1>Olá, Mundo!</h1>
</body>
</html>
```

---

## 🧠 Explicando a estrutura

* `<!DOCTYPE html>` → define HTML5
* `<html lang="pt-br">` → idioma do site
* `<head>` → configurações
* `<body>` → conteúdo visível

### Metadados importantes:

* `<meta charset="UTF-8">`
  👉 Permite acentos (ç, á, etc.)

* `<meta name="viewport">`
  👉 Responsividade (adaptação a telas)

* `<title>`
  👉 Título da aba do navegador

---

## 🌐 Como HTML e CSS funcionam na prática?

Relembrando as aulas anteriores:

1. Você digita uma URL
2. O DNS retorna o IP
3. Seu navegador acessa o servidor
4. O servidor envia os arquivos (HTML, CSS, etc.)
5. Seu navegador interpreta esses arquivos

👉 Resultado:
O navegador **renderiza** (transforma código em interface visual)

---

## 🧠 Resumo Final

HTML e CSS são as bases da construção de sites. O HTML define a estrutura e o conteúdo, enquanto o CSS cuida da aparência. Junto com o JavaScript, formam o conjunto essencial do desenvolvimento web. Quando acessamos um site, o navegador busca esses arquivos no servidor, interpreta o código e exibe o resultado visual na tela.
