# 📚 Sistema de Gestão de Alunos em C

## 🎯 Descrição

Este projeto consiste em um sistema completo de cadastro e gestão de alunos, desenvolvido na linguagem C. O sistema permite realizar operações de CRUD (Create, Read, Update, Delete), autenticação de usuário, cálculo de médias e emissão de relatórios.

---

## 🛠️ Funcionalidades

✅ **Cadastro de Alunos:**  
- Registro de nome, RGM (Registro Geral do Aluno) e senha.  
- Validação para impedir cadastros duplicados e garantir entrada de dados correta.

✅ **Login de Alunos:**  
- Autenticação via RGM e senha.  
- Inserção das notas A1 e A2.  
- Caso necessário, realização da AF (Avaliação Final) substituindo a menor nota.  
- Cálculo automático da média e definição da situação: Aprovado ou Reprovado.  
- Geração de relatório individual com notas e situação.

✅ **Relatório Geral de Alunos:**  
- Exibe todos os alunos cadastrados, com nome, RGM, média e situação final.

✅ **Listagem Administrativa:**  
- Mostra nome, RGM e senha de todos os alunos (uso exclusivo para administração).

✅ **Atualização de Cadastro:**  
- Permite alterar o nome e a senha do aluno a partir do RGM.

✅ **Exclusão de Aluno:**  
- Remove permanentemente um aluno do sistema através do RGM.

---

## ⚙️ Tecnologias Utilizadas

- Linguagem: **C**  
- Bibliotecas padrão:  
  - `<stdio.h>` — Entrada e saída de dados  
  - `<string.h>` — Manipulação de strings  
  - `<ctype.h>` — Validação de caracteres  

---

## 🏗️ Estrutura do Sistema

- Estrutura `struct Aluno` para armazenar dados de cada aluno.  
- Vetor `alunos[MAX_ALUNOS]` para manter os registros na memória.  
- Funções separadas para cada operação: cadastro, login, relatório, atualização e exclusão.  
- Validações para garantir integridade e segurança dos dados.

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/sistema-gestao-alunos.git
