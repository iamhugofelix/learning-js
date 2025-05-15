# Class Notes (May 15)

While_

Um ciclo while é sempre executado enquanto a condição especificada não seja availada como verdadeira.

*Sintax:

while (condição) {
    declaração
}

*Exemplo:

let j = 0;
while (j <= 6) {
    console.log(j);
    j++;
}

No exemplo acima, o codigo é repetido até chegar ao 6 (porque o j não ia é "true" se for mais que 6)

# Functions
O objectivo de uma função é cumprir uma tarefa. Ex: Uma função serve para calcular o IVA de um produto.

*Sintax:
function name (argument1, argument2) {
    const result = argument * 2; -> Não é preciso variavel, pode ser feito no "return"
    return result;
}

## Objects
const object = {
    item1: thing,
    item2: thing,
    item3: thing,
}