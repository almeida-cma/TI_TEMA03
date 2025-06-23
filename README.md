# TI_TEMA03
Sistema operacional: Softwares

# 🔢 Desafio Simples: Número Positivo, Negativo ou Zero

## 🎯 Objetivo

Criar uma página onde o usuário digita um número e o sistema informa se ele é **positivo**, **negativo** ou **zero**.

Você deve **construir a estrutura HTML e CSS** com base no exemplo apresentado no material:  
📄 *Exemplo com editor interativo W3School.pdf*

Abaixo, está disponível apenas o **script de apoio em JavaScript**, responsável pela lógica da verificação:

---

## 🧠 Script de Apoio (JavaScript)

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
````

---

## 📤 Entrega

1. Crie um repositório **público** no GitHub contendo os arquivos HTML, CSS e JS.
2. Publique o projeto com **GitHub Pages**.
3. Envie o link do projeto publicado para:
   👉 [https://almeida-cma.github.io/receber/](https://almeida-cma.github.io/receber/)

```
