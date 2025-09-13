# Santander-Code-Girls-2025
# 🚀 Desafio de Gerenciamento de EC2 na AWS

Este repositório contém minhas anotações, insights e práticas realizadas durante o **Desafio da DIO** sobre **Gerenciamento de Instâncias EC2 na AWS**.  
O objetivo é consolidar os conhecimentos adquiridos em sala, documentar o processo e criar um material de apoio para futuras consultas.

---

## 📌 Objetivos do Desafio

Ao final deste desafio, fui capaz de:

- Aplicar os conceitos aprendidos em um **ambiente prático** utilizando AWS;
- Documentar processos técnicos de forma **clara e estruturada**;
- Utilizar o **GitHub como ferramenta de versionamento e compartilhamento** de documentação técnica.

---

## 🖥️ Arquitetura Desenvolvida

Abaixo está um diagrama representando a solução prática criada durante o laboratório:

![Arquitetura AWS](./images/Captura%20de%20tela%202025-09-09%20212228.png)

### 🔎 Descrição da Arquitetura
- **Actor (usuário)**: responsável por enviar arquivos para a aplicação hospedada na AWS.  
- **EC2**: instância responsável por processar os dados recebidos.  
- **EBS (Volumes D e E)**: utilizados para armazenamento persistente dos arquivos manipulados pela instância.  
- **RDS**: banco de dados relacional para persistência e consulta estruturada dos dados.  

Esse fluxo garante que o usuário consiga **enviar arquivos**, que são armazenados e processados pela EC2, com suporte de volumes **EBS** e banco de dados **RDS**.

---

## 📂 Estrutura do Repositório

```bash
📦 desafio-ec2-aws
 ┣ 📂 images            # Capturas de tela e diagramas
 ┗ 📜 README.md         # Documentação principal do projeto

