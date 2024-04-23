Representa o tipo inteiro (integer), ele não contém elementos fracionários ou decimais.
Existe um range específico de valores permitidos para o tipo `int`, o que significa que ele não é infinito. Há um valor mínimo e máximo definido para cada tipo de dado numérico, ou seja, você não consegue atribuir um número menor ou maior que esse limite.

|  Atributo estático  |     Valor     | Tamanho (em bits) |
| :-----------------: | :-----------: | :---------------: |
| `Integer.MIN_VALUE` | `-2147483648` |        32         |
| `Integer.MAX_VALUE` | `2147483647`  |        32         |
Efetuar uma [[Operação Aritmética]] com um número maior que o máximo resultará em um [[Overflow]]. E efetuar a mesma operação com um número menor que o mínimo resultará em um [[Underflow]].

Esses casos também são conhecidos como integer wraparounds. Esse não é um comportamento que queremos, e como um desenvolvedor, você precisa ficar ciente que isto pode acontecer, e então escolher um tipo de dado mais apropriado para cada caso.

Um evento de integer wraparound, seja ele de overflow ou underflow, pode ocorrer no Java quando você está usando expressões que não são um valor literal simples.
O Java compiler não tenta calcular a expressão para determinar seu valor, então ele NÃO LANÇA um erro.

Não é possível usar vírgulas num valor `int`, mas é possível usar underline para tornar um número mais legível:

```Java
int myMaxIntTest = 2_147_483_647;
```
