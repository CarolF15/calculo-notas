# 📘 Projeto de Consulta de Satisfação 
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)

# Sistema de Cálculo de Notas Escolares

Projeto desenvolvido para praticar lógica de programação com Python. O programa é estruturado para coletar as notas bimestrais de uma turma de alunos, realizar o cálculo da média aritmética, verificar a situação acadêmica de cada estudante (aprovado ou reprovado) e apresentar um relatório final com o desempenho geral da turma.

---

## 🎯 Objetivo do Programa 

* Automatizar o cálculo da média escolar a partir de quatro notas bimestrais fornecidas pelo usuário.
* Praticar o ciclo de Entrada → Processamento → Saída: capturar dados, aplicar regras de negócio (média mínima de aprovação) e exibir os resultados estruturados.
* Utilizar estruturas de repetição (`for` e `while`) para controle de fluxo e robustez no cadastro de múltiplos alunos.
* Implementar o tratamento de exceções (`try-except`) para garantir que apenas valores numéricos válidos sejam computados, evitando interrupções indesejadas no programa.

---

## 📋 Regras e Funcionalidades

| Informação | Descrição |
|---|---|
| Quantidade de alunos | Definida dinamicamente pelo usuário no início da execução |
| Dados coletados | Nome do aluno e 4 notas bimestrais (validadas entre 0 e 10) |
| Critério de aprovação | Média final maior ou igual a 6,0 |
| Resultado apresentado | Média final individual, situação (Aprovado/Reprovado) e relatório consolidado da turma |

---

## 🚀 Como Executar o Programa

### Pré-requisitos
* **Python 3.10** (ou superior) instalado.

### Passo a Passo

1. Clone este repositório:
   ```bash
   git clone https://github.com/CarolF15/calculo-notas.git