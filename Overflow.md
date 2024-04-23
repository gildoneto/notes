Acontece quando se tenta alocar um número maior que o suportado pelo tipo de dado. O computador vai tentar fazer a operação, resultando num número negativo.

```Java
int myMaxValue = Integer.MAX_VALUE; //2147483647
System.out.print(myMaxValue + 1);
// -2147483648 
```

Quando o valor máximo sofre um overflow, a linguagem wrap around para o valor mínimo, e simplesmente continua o processo sem erros.