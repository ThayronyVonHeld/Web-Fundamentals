# 🌐 Aula 3 — O que é Domínio e Hospedagem?

---

## ❓ Como outras pessoas podem ver meu site?

Relembrando um conceito importante da aula anterior:

Quando você acessa um site, você está se conectando a um **servidor**, que possui um:

👉 **Endereço IP (Internet Protocol)**

### Exemplo:

* Servidor → `3.244.112.47`
* Seu dispositivo → `172.23.41.49`

---

## 🔎 Domínios e DNS (Revisão)

Memorizar IPs seria inviável, então usamos nomes de domínio, como:

* `instagram.com`

Isso funciona graças ao DNS.

### Como funciona:

1. Você digita um domínio
2. Seu dispositivo consulta o DNS
3. O DNS retorna o IP correspondente
4. Você acessa o servidor correto

---

## ⚠️ Problema: Meu site está no meu computador

Se o seu site estiver apenas no seu PC:

👉 **Outras pessoas NÃO conseguem acessá-lo**

Por quê?

* Seu computador não é um servidor público
* Ele não está exposto na internet
* Não há domínio associado
* O DNS não consegue encontrá-lo

---

## 🌍 Solução: Hospedagem + Domínio

Para que seu site seja acessível, você precisa de duas coisas:

### 🏠 Hospedagem (Hosting)

É onde seu site fica armazenado.

* Espaço para arquivos
* Memória e processamento
* Servidor conectado à internet

👉 Pode ser:

* Pago (mais comum)
* Gratuito (com limitações)

---

### 🌐 Domínio

É o nome do seu site na internet.

Exemplo:

* `github.io`

📌 Características:

* Deve ser **único**
* Geralmente é **pago anualmente**
* Possui diferentes tipos (TLDs)

---

## 🔗 Exemplo prático

Vamos analisar:

👉 `gustavoguanabara.github.io`

* `gustavoguanabara` → subdomínio
* `github.io` → domínio
* `.io` → TLD

---

## 🧩 Estrutura de uma URL

Uma URL (Uniform Resource Locator) é o endereço completo de um recurso na internet.

### Exemplo:

👉 `www.github.com/ThayronyVonHeld`

Vamos dividir:

* `www` → subdomínio
* `github.com` → domínio
* `.com` → TLD
* `/ThayronyVonHeld` → caminho (path)

---

## 🌐 Tipos de TLD

O TLD (Top-Level Domain) é a parte final do domínio.

### Tipos principais:

* **gTLD (genéricos)**

  * `.com`, `.org`, `.net`, `.io`

* **ccTLD (país)**

  * `.br` (Brasil)
  * `.es` (Espanha)

---

## 🔐 Outro exemplo completo

👉 `https://gustavoguanabara.github.io`

Vamos identificar:

* `https://` → protocolo
* `gustavoguanabara` → subdomínio
* `github.io` → domínio
* `.io` → TLD

👉 Tudo isso junto forma a **URL completa**

---

## 🧠 Resumo Final

Para que um site seja acessível na internet, ele precisa estar hospedado em um servidor e possuir um domínio. O domínio funciona como um nome fácil de lembrar, enquanto a hospedagem armazena os arquivos do site. A URL é o endereço completo que permite acessar esse recurso, e o DNS é responsável por traduzir o domínio em um IP.

