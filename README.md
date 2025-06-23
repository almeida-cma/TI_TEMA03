# TI_TEMA03
Sistema operacional: Softwares

title: "🔢 Desafio Simples: Número Positivo, Negativo ou Zero"
description: |
  🎯 Objetivo:
  Criar uma página onde o usuário digita um número e o sistema informa se ele é positivo, negativo ou zero.

  O aluno deve construir a estrutura HTML e CSS por conta própria, utilizando o exemplo presente no material:
  📄 "Exemplo com editor interativo W3School.pdf"

  Abaixo, segue apenas o script de apoio com a lógica em JavaScript:

script_de_apoio_js: |
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

entrega:
  instrucoes: |
    Envie o(s) arquivo(s) para um repositório no seu GitHub público.
    Publique o projeto usando GitHub Pages.
    Em seguida, envie o link do projeto publicado para:
  url_envio: "https://almeida-cma.github.io/receber/"

