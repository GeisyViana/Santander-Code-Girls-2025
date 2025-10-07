# Relatório de Estudos – AWS Step Functions
 
**Data:** 06/10/2025  
**Curso:** Formação AWS – DIO  
**Tema:** Consolidação de Workflows Automatizados com AWS Step Functions  

---

## 1. Introdução

Este repositório documenta a experiência de estudo e dos conceitos aprendidos sobre **AWS Step Functions**, serviço da AWS que permite a criação, execução e gerenciamento de workflows automatizados em ambientes serverless.  

O estudo abrange a compreensão dos elementos essenciais do serviço, sua integração com **AWS Lambda**, o tratamento de erros e a construção de fluxos complexos, incluindo decisões condicionais e execuções paralelas.

---

## 2. Objetivos do Estudo

- Aplicar de forma prática os conceitos aprendidos sobre AWS Step Functions.  
- Desenvolver workflows automatizados integrando funções Lambda.  
- Documentar o processo de estudo e aprendizado de forma organizada e detalhada.  

---

## 3. Conceitos Revisados

Durante o estudo foram revisados os seguintes conceitos:

- **Step Functions:** orquestração de workflows serverless, permitindo sequenciamento de tarefas e automação de processos.  
- **Estados (States) e Transições (Transitions):** definição do fluxo de execução, incluindo estados do tipo *Task*, *Choice*, *Parallel*, *Wait*, entre outros.  
- **Integração com Lambda:** execução de funções Lambda como etapas do workflow.  
- **Tratamento de erros:** configuração de políticas de retry e captura de falhas.  
- **Execuções condicionais e paralelas:** uso de *Choice State* para decisões baseadas em condições e *Parallel State* para execuções simultâneas.

---

## 4. Metodologia

O estudo foi realizado em etapas:

1. Revisão teórica da documentação oficial da AWS Step Functions e das aulas da DIO.  
2. Criação de funções Lambda simples para uso nos workflows.  
3. Definição de fluxos em JSON utilizando Amazon States Language (ASL).  
4. Testes e validação dos workflows, análise de logs e tratamento de erros.  

---

## 6. Resultados Obtidos

Automatização de um fluxo simples de validação e processamento de dados.

Compreensão da integração entre Step Functions e Lambda.

Visualização e monitoramento da execução de cada estado, com tratamento de falhas.

Organização da documentação para referência futura.

## 7. Aprendizados e Insights

Step Functions facilita a orquestração de processos serverless complexos.

Documentar etapas e resultados no GitHub é essencial para aprendizado e referência futura.

Tratamento de falhas e decisões condicionais são críticos para workflows confiáveis.

A prática consolidou a compreensão dos conceitos estudados.

## 8. Conclusão

O estudo de AWS Step Functions proporcionou uma compreensão sólida sobre orquestração de workflows serverless, integração com Lambda e automação de processos.

Este repositório serve como referência técnica e material de estudo, consolidando conhecimento prático e teórico.

## 9. Referências

AWS Step Functions – Documentação Oficial - https://aws.amazon.com/pt/step-functions/
