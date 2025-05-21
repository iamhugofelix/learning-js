
# Variáveis

## 🔹 O que são?
Variáveis servem para guardar dados que vamos usar no nosso código — como nomes, números ou listas.

## 🔹 Como declarar?

### 👉 `let`
Usamos `let` quando o valor **pode mudar** mais tarde.
```js
let idade = 25;
idade = 26; // funciona
```

### 👉 `const`
Usamos `const` quando o valor **não vai mudar**.
```js
const nome = "João";
nome = "Pedro"; // ERRO: não podes mudar uma const
```

> 📌 Dica: Usa `const` sempre que puderes, e só usa `let` quando precisas mesmo de mudar o valor.

## 🔹 Tipos de valores

### 🔸 String (texto)
```js
let nome = "Maria";
```

### 🔸 Number (número)
```js
let idade = 30;
```

### 🔸 Boolean (verdadeiro ou falso)
```js
let maiorDeIdade = true;
```

### 🔸 Null (valor nulo intencional)
```js
let resposta = null;
```

### 🔸 Undefined (valor ainda não definido)
```js
let preco;
console.log(preco); // undefined
```

## 🔹 Concatenar variáveis (juntar texto)
```js
let nome = "Carlos";
let saudacao = "Olá, " + nome + "!";
console.log(saudacao); // Olá, Carlos!
```

Ou com *template strings* (mais moderno e fácil):
```js
let nome = "Carlos";
console.log(`Olá, ${nome}!`);
```

## 🔹 Regras para dar nomes a variáveis:
- Não pode começar com número.
- Não pode ter espaços ou acentos.
- Pode usar letras, números, `$` e `_`.
- Usa nomes claros e fáceis de entender:
```js
let x = 10;            // mau nome
let precoProduto = 10; // bom nome
```
