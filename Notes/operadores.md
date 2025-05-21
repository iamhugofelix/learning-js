
# Ponto 2 – Operadores

## 🔹 O que são?
Operadores são símbolos usados para fazer operações com valores — como somar, comparar, ou verificar condições.

---

## 🔸 1. Operadores Aritméticos (números)

| Operador | Significado       | Exemplo    | Resultado |
|----------|-------------------|------------|-----------|
| `+`      | Soma              | `5 + 2`    | `7`       |
| `-`      | Subtração         | `5 - 2`    | `3`       |
| `*`      | Multiplicação     | `5 * 2`    | `10`      |
| `/`      | Divisão           | `10 / 2`   | `5`       |
| `%`      | Resto da divisão  | `10 % 3`   | `1`       |

---

## 🔸 2. Operadores de Comparação (usados em condições)

| Operador | Significado                   | Exemplo        | Resultado |
|----------|-------------------------------|----------------|-----------|
| `==`     | Igual (valor)                 | `5 == '5'`     | `true`    |
| `===`    | Igual (valor e tipo)          | `5 === '5'`    | `false`   |
| `!=`     | Diferente (valor)             | `5 != '5'`     | `false`   |
| `!==`    | Diferente (valor ou tipo)     | `5 !== '5'`    | `true`    |
| `<`      | Menor que                     | `3 < 5`        | `true`    |
| `>`      | Maior que                     | `10 > 2`       | `true`    |
| `<=`     | Menor ou igual                | `5 <= 5`       | `true`    |
| `>=`     | Maior ou igual                | `6 >= 7`       | `false`   |

---

## 🔸 3. Operadores Lógicos (usados em `if`, `while`, etc.)

| Operador | Nome      | Exemplo         | Resultado |
|----------|-----------|------------------|-----------|
| `&&`     | E (and)   | `true && false`  | `false`   |
| `||`     | OU (or)   | `true || false`  | `true`    |
| `!`      | NÃO (not) | `!true`          | `false`   |

### Exemplo:
```js
let idade = 20;
let temCarta = true;

if (idade >= 18 && temCarta) {
  console.log("Pode conduzir");
}
```
