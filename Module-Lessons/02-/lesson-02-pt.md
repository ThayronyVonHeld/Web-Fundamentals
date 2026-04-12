# 🌐 Aula 2 — Como a Internet Funciona?

---

## 💻 Como os computadores representam dados?

Os computadores são máquinas eletrônicas que funcionam utilizando apenas dois sinais:

👉 **0 e 1** (sistema binário)

Esses sinais são chamados de:

* **Bits (binary digits)** → menor unidade de informação

Um único bit não é suficiente para representar dados úteis.
Por isso, foi definido um padrão mínimo:

👉 **1 Byte = 8 bits**

### Exemplo:

* `01000001` → representa a letra **"A"** no padrão UTF-8

Ou seja, ao pressionar uma tecla, o computador interpreta essa ação como uma sequência de bits organizada em bytes.

---

## 📦 Múltiplos de Byte

Assim como unidades de medida (kg, g, mg), a computação também possui seus múltiplos:

* **1024 Bytes** = 1 Kilobyte (KB)
* **1024 KB** = 1 Megabyte (MB)
* **1024 MB** = 1 Gigabyte (GB)
* **1024 GB** = 1 Terabyte (TB)
* **1024 TB** = 1 Petabyte (PB)

📌 Observação:

* Computadores trabalham em **base 2**, não base 10
* Por isso: **2¹⁰ = 1024**

---

## ⚠️ Diferença entre MB e Mb

Existe uma diferença importante:

* **MB (Megabytes)** → armazenamento
* **Mb (Megabits)** → transmissão de dados

👉 Exemplo:
Sua internet pode ser de **500 Mb/s (megabits por segundo)**

---

## 🌐 Como nos conectamos à Internet?

Quando você acessa a internet, você atua como um **cliente**, solicitando um serviço (como acessar um site).

### Caminhos da conexão:

* **Computador:**
  PC → Modem → Internet

* **Celular:**
  Celular → Antena → Internet

Para isso, é necessário um provedor de internet (ISP).

---

## 📡 Modulação e Demodulação

Existe um desafio importante na comunicação:

* Computadores usam sinais digitais (0 e 1) → onda quadrada
* Sistemas de transmissão usam sinais analógicos → onda senoidal

👉 Solução: conversão de sinais

* **Modulação** → digital → analógico
* **Demodulação** → analógico → digital

📌 Curiosidade:
O termo **modem** vem de:

* **MO** (Modulação)
* **DEM** (Demodulação)

---

## 🌍 Como acessamos servidores?

Quando você acessa um site (como Instagram), você está se conectando a um servidor.

Esses servidores são identificados por:

👉 **Endereço IP (Internet Protocol)**

### Exemplo:

* Servidor → `3.244.112.47`
* Seu dispositivo → `172.23.41.49`

---

## 🔎 Domínios e DNS

Memorizar IPs seria muito difícil. Por isso usamos nomes de domínio, como:

* `instagram.com`

Isso é possível graças ao DNS.

### Como funciona:

1. Você digita `instagram.com`
2. Seu dispositivo envia a solicitação para um servidor DNS
3. O DNS traduz o domínio em um endereço IP
4. Você é conectado ao servidor correto

📌 Analogia:
O DNS funciona como uma **agenda telefônica**:

* Nome → “Mãe”
* Número → telefone real

---

## 🧭 Rotas na Internet

A internet não funciona em linha reta.

👉 Os dados percorrem **rotas** dentro da rede.

* Um mesmo destino pode ter vários caminhos
* A rota pode mudar dinamicamente

📌 Analogia:
Como o Waze:

* Ele recalcula rotas conforme o trânsito
* Sempre busca o caminho mais rápido

---

## 📦 Pacotes de Dados

Quando você acessa um conteúdo:

* Os dados são divididos em **pacotes**
* Cada pacote pode seguir rotas diferentes
* No destino, eles são reorganizados

---

## 🧠 Resumo Final

Os computadores representam dados em binário (0 e 1), organizados em bytes.
Para acessar a internet, utilizamos provedores e sistemas de conversão de sinal (modulação/demodulação).
Os sites são acessados por nomes de domínio, que são traduzidos em IPs pelo DNS.
Por fim, os dados trafegam em pacotes por diferentes rotas até chegar ao destino.

