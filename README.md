# Sistema de Cadastro e Gestão de Alunos

## 📋 Descrição

Este é um sistema simples de cadastro e gestão de alunos desenvolvido em linguagem C. O sistema permite cadastrar, autenticar, atualizar, listar e deletar alunos, além de realizar o cálculo da média final com base nas notas das avaliações A1, A2 e, se necessário, AF (Avaliação Final).

O sistema também gera relatórios com a situação do aluno: **Aprovado** ou **Reprovado**.

## 🎯 Funcionalidades

- ✅ Cadastro de alunos com validação de nome, RGM e senha.
- ✅ Login de aluno com autenticação por RGM e senha.
- ✅ Cálculo automático da média final e situação (Aprovado/Reprovado).
- ✅ Atualização de dados do aluno.
- ✅ Deleção de alunos cadastrados.
- ✅ Listagem de todos os alunos cadastrados.
- ✅ Relatório completo dos alunos com médias e situações.

## 🛠️ Tecnologias Utilizadas

- Linguagem C
- Biblioteca padrão: stdio.h, string.h, ctype.h, locale.h

## 🚀 Como Executar

1. Clone ou baixe o repositório.
2. Compile o código com um compilador C (por exemplo, GCC):

   ```bash
   gcc sistema_alunos.c -o sistema_alunos
