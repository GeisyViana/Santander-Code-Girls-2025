# 🧠 Desafio: Automatização com AWS Lambda e S3

## 📘 Descrição do Desafio
Este laboratório tem como objetivo **consolidar os conhecimentos em tarefas automatizadas com AWS Lambda Function e Amazon S3**.  
O entregável é um **repositório organizado** contendo anotações e insights adquiridos durante a prática, servindo como **material de apoio para estudos e futuras implementações**.

---

## ☁️ Conceitos Principais

### 🔹 AWS Lambda
O **AWS Lambda** é um serviço de computação sem servidor (serverless) que permite **executar código sob demanda**, em resposta a eventos, **sem precisar gerenciar servidores**.  
Ele é amplamente utilizado para automação, processamento de dados e integrações com outros serviços da AWS.

**Principais pontos:**
- Executa funções em diversas linguagens (Python, Node.js, Java, etc.);
- Escala automaticamente conforme a demanda;
- Cobra apenas pelo tempo de execução do código;
- Pode ser disparado por eventos de serviços como S3, DynamoDB, SNS e API Gateway.

### 🔹 Amazon S3
O **Amazon Simple Storage Service (S3)** é um serviço de **armazenamento de objetos** altamente escalável, seguro e durável.  
É utilizado para armazenar arquivos, backups, logs e dados estáticos de aplicações web.

**Principais pontos:**
- Armazena objetos em buckets;
- Permite configurar políticas de acesso (IAM e Bucket Policies);
- Gera eventos que podem acionar funções Lambda automaticamente (ex: upload de arquivo);
- Integra-se com outros serviços AWS para automação e análise de dados.

---

## ⚙️ Cenário Prático

Durante o laboratório, foi configurada uma **integração entre o S3 e o Lambda**, onde:
1. Um arquivo é enviado (upload) para um bucket S3;
2. O envio aciona automaticamente uma **Lambda Function**;
3. A função executa uma tarefa, como:
   - Processar o arquivo (ex: leitura, formatação, compressão);
   - Mover ou copiar o arquivo para outro bucket;
   - Registrar logs no CloudWatch;
   - Enviar notificações via SNS.

---

## 🧩 Passos Gerais da Implementação

1. **Criar o bucket S3**  
   - Definir nome único e região.  
   - Configurar permissões e versionamento (opcional).

2. **Criar a função Lambda**  
   - Escolher a linguagem (ex: Python).  
   - Definir código para processar os eventos do S3.  

Adicionar o gatilho (trigger) S3 → Lambda

Configurar o evento ObjectCreated no bucket S3 para invocar a função Lambda.

Testar o fluxo

Fazer upload de um arquivo no S3;

Verificar os logs no CloudWatch para confirmar a execução.

---

## 📊 Insights e Aprendizados
Automatização: Lambda e S3 trabalham juntos para eliminar tarefas manuais e acelerar processos.

Escalabilidade: A arquitetura serverless se ajusta automaticamente à demanda.

Baixo custo: Você paga apenas pelo tempo de execução e armazenamento usado.

Monitoramento: O CloudWatch é essencial para acompanhar logs e métricas.

---

## Boas práticas:

Usar roles IAM específicas e com permissões mínimas;

Versionar o código da Lambda;

Configurar variáveis de ambiente para maior flexibilidade.
