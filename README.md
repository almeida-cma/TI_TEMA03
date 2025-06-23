# TI_TEMA03
Sistema operacional: Softwares

# 🔢 Desafio Simples: Número Positivo, Negativo ou Zero

## 🎯 Objetivo:

Criar uma página onde o usuário digita um número e o sistema informa se ele é positivo, negativo ou zero.

---

## 🧠 Script de apoio (JavaScript):

```javascript
function verificarNumero() {
    const valor = parseFloat(document.getElementById("numero").value);
    let mensagem = "";

    if (isNaN(valor)) {
        mensagem = "Por favor, digite um número válido.";
    } else if (valor > 0) {
        mensagem = "O número é positivo.";
    } else if (valor < 0) {
        mensagem = "O número é negativo.";
    } else {
        mensagem = "O número é zero.";
    }

    document.getElementById("resultado").innerText = mensagem;
}

Use esse trecho como base e monte sua própria estrutura HTML e CSS. Consulte o exemplo presente no material:

📄 Exemplo com editor interativo W3School.pdf

📤 Entrega
Envie o(s) arquivo(s) para um repositório no seu GitHub público.

Publique o projeto com o GitHub Pages.

Envie o link do projeto publicado para: 👉 https://almeida-cma.github.io/receber/
