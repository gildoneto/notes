
```Java
long myLongValue = 100;
```

A expressão acima não vai gerar um número do tipo `long`.
O número 100, por default, é um `int`.

O Java permite que alguns valores numéricos literais tenham um [[Suffix]] anexado ao valor, para forçar que ele seja de um tipo diferente do valor default.

O `long` é desses tipos e seu [[Suffix]] é um `L`.

Esse é um dos casos onde o Java não é case sensitive. Este sufixo tanto pode ser um `L` maiúsculo como pode ser um `l` minúsculo.

```Java
long myLongValue = 100L;
System.out.print("A long has a width of " + Long.SIZE);
// A long has a width of 64
```

| Atributo estático |         Valor          | Tamanho (em bits) |
| :---------------: | :--------------------: | :---------------: |
| `Long.MIN_VALUE`  | `-9223372036854775808` |        64         |
| `Long.MAX_VALUE`  | `9223372036854775807`  |        64         |
