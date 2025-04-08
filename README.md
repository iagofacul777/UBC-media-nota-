# Sistema de Cálculo de Média com Avaliação Final (AF)

Este programa em linguagem C simula o processo de cálculo de média de um aluno com base em duas avaliações principais (A1 e A2). Caso a soma dessas notas seja inferior a 12, o aluno terá direito a uma Avaliação Final (AF), que substituirá a menor das duas notas. Ao final, o sistema informa se o aluno foi aprovado ou reprovado com base em uma média mínima de 6,0.

## Funcionalidades

- Entrada e validação do nome do aluno (apenas letras).
- Entrada e validação de notas entre 0 e 10.
- Cálculo da média e substituição de nota com base na AF.
- Mensagem de aprovação ou reprovação com `switch/case`.
- Loop de repetição para processar múltiplos alunos.

## Tecnologias

- Linguagem: C
- Bibliotecas utilizadas:
  - `stdio.h`
  - `string.h`
  - `ctype.h`

## Como compilar

Use um compilador C como `gcc`. No terminal, digite:

```bash
gcc -o media_aluno programa.c
