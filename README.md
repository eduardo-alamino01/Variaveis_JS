# 📘 Projeto de Estudos em JavaScript

Este repositório contém exemplos e exercícios desenvolvidos para estudar conceitos fundamentais do **JavaScript**, como declaração de variáveis, escopo, uso de `.gitignore` e formas de armazenamento de dados.

## 📌 Objetivo
O objetivo deste projeto é praticar conceitos básicos de programação em JavaScript e entender como organizar um projeto utilizando **Git e GitHub**.

---

# 🟢 Declaração de Variáveis

Em JavaScript, variáveis são utilizadas para armazenar dados que podem ser usados ao longo do programa.

Existem três formas principais de declarar variáveis:

```javascript
var nome = "João";
let idade = 20;
const cidade = "São Paulo";
var: forma mais antiga de declaração.

let: permite alterar o valor da variável.

const: usada quando o valor não deve ser alterado.

🟢 Escopo

O escopo define onde uma variável pode ser acessada dentro do código.

Existem dois tipos principais:

Escopo Global

A variável pode ser acessada em qualquer parte do código.

let mensagem = "Olá";

function mostrarMensagem() {
  console.log(mensagem);
}
Escopo Local (ou de bloco)

A variável só existe dentro do bloco onde foi criada.

function exemplo() {
  let numero = 10;
  console.log(numero);
}
🟢 Arquivo .gitignore

O arquivo .gitignore serve para indicar quais arquivos ou pastas não devem ser enviados para o repositório.

Exemplo de .gitignore para projetos JavaScript:

node_modules/
.env
dist/
build/
logs/
*.log

Isso ajuda a evitar que arquivos desnecessários ou sensíveis sejam enviados ao GitHub.

🟢 Armazenamento de Dados

Em JavaScript, os dados podem ser armazenados em diferentes estruturas, como:

Variáveis

Armazenam valores simples.

let nome = "Carlos";
Arrays

Armazenam vários valores em uma lista.

let frutas = ["maçã", "banana", "laranja"];
Objetos

Armazenam informações mais organizadas.

let pessoa = {
  nome: "Ana",
  idade: 25
};
🛠️ Tecnologias Utilizadas

JavaScript
Git
GitHub
