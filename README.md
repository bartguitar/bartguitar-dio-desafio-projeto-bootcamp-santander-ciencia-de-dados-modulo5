# Relatório de Implementação de Serviços AWS

## 📅 Dados do Projeto
- **Data de início:** Janeiro de 2026  
- **Empresa:** Abstergo Industries  
- **Responsável:** Adriel Bart  

---

## 📌 Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Adriel Bart**.  
O objetivo do projeto foi elencar **três serviços essenciais da AWS**, com a finalidade de **reduzir custos imediatos**, aumentar a eficiência operacional e melhorar a gestão da infraestrutura de TI utilizando computação em nuvem.

---

## 🛠️ Tecnologias Utilizadas

Para a implementação deste projeto, foram selecionadas tecnologias essenciais da AWS, priorizando simplicidade, baixo custo e eficiência operacional.

### Amazon EC2 (Elastic Compute Cloud)
Serviço responsável pela criação e gerenciamento de máquinas virtuais na nuvem. Permite executar aplicações de forma escalável, pagando apenas pelos recursos utilizados, reduzindo custos com infraestrutura física.

### Amazon S3 (Simple Storage Service)
Serviço de armazenamento de objetos altamente durável e escalável. Utilizado para armazenar arquivos, documentos e backups, eliminando a necessidade de servidores locais de armazenamento.

### Amazon RDS (Relational Database Service)
Serviço gerenciado de banco de dados relacional que automatiza tarefas como backups, atualizações e escalabilidade, reduzindo custos operacionais e riscos de indisponibilidade.

### Amazon IAM (Identity and Access Management)
Responsável pelo gerenciamento de usuários e permissões, garantindo que apenas pessoas autorizadas tenham acesso aos recursos da AWS, aumentando a segurança do ambiente.

### Amazon CloudWatch
Ferramenta de monitoramento que permite acompanhar métricas, logs e alarmes dos serviços AWS, auxiliando no controle de desempenho e na identificação de falhas.

### AWS Cost Explorer
Serviço utilizado para análise e controle de custos, permitindo identificar desperdícios e otimizar o uso dos recursos da nuvem.

---

## 📊 Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em **três etapas**, cada uma com seus objetivos específicos, conforme descrito a seguir:

### Etapa 1 – Amazon EC2
- **Foco:** Computação em nuvem  
- **Descrição de uso:** Migração de servidores físicos para instâncias EC2, reduzindo custos com manutenção de hardware e permitindo escalabilidade conforme a demanda.

### Etapa 2 – Amazon S3
- **Foco:** Armazenamento de dados  
- **Descrição de uso:** Centralização do armazenamento de arquivos e backups no Amazon S3, garantindo alta durabilidade, disponibilidade e redução de custos com servidores locais.

### Etapa 3 – Amazon RDS
- **Foco:** Banco de dados gerenciado  
- **Descrição de uso:** Implementação de banco de dados relacional gerenciado, eliminando a necessidade de administração manual, aumentando a confiabilidade e reduzindo custos operacionais.

---

## ✅ Conclusão

A implementação das ferramentas AWS na empresa **Abstergo Industries** tem como resultado esperado a **redução imediata de custos**, aumento da eficiência operacional e maior segurança da infraestrutura de TI.  
Recomenda-se a continuidade da utilização dos serviços implementados e a avaliação constante de novas tecnologias em nuvem que possam aprimorar ainda mais os processos da empresa.

---

## 📎 Anexos

- [Documentação Oficial da AWS](https://docs.aws.amazon.com/pt_br/)
- [AWS Pricing Calculator – Simulação de Custos](https://calculator.aws/)
  
  ## 📐 Diagrama de Arquitetura

```text
┌───────────────┐
│   Usuários    │
└───────┬───────┘
        │
        ▼
┌────────────────────┐
│   Amazon EC2       │
│  (Aplicação)       │
└───────┬────────────┘
        │
        │
┌───────▼────────────┐        ┌────────────────────┐
│   Amazon RDS       │        │   Amazon S3         │
│ (Banco de Dados)   │        │ (Arquivos / Backup) │
└────────────────────┘        └────────────────────┘
```

---

## ✍️ Assinatura

**Adriel Bart**  
Responsável pelo Projeto
