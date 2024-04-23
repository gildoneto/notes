O range de Byte é muito pequeno. Talvez você iria querer usar em um caso onde os números não extrapolariam o range e se precisa salvar memória.

A memória RAM dos computadores atuais é enorme, então não faz sentido usar esse tipo na ideia de salvar memória.

O tipo `byte` também tem o mesmo problema de [[Overflow]] e [[Underflow]], mas obviamente dentro do seu próprio range.

| Atributo estático | Valor  | Tamanho (em bits) |
| :---------------: | :----: | :---------------: |
| `Byte.MIN_VALUE`  | `-128` |         8         |
| `Byte.MAX_VALUE`  | `127`  |         8         |

Related to [[Wrapper Class]]