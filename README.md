# 🖥️ Sistemas Operacionais

Repositório dedicado aos projetos práticos desenvolvidos para a disciplina de **Sistemas Operacionais** da **Faculdade ESEG (Grupo Etapa)**, sob a orientação do **Prof. Victor Lattari**.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* 🐧 **Ambiente:** Linux / Terminal Bash
* 📜 **Linguagens:** Bash Scripting, Python
* 📊 **Formatos de Dados:** CSV, Arquivos de Log (`.log`), Arquivos de Configuração (`.conf`)

---

## 🚀 Projetos Desenvolvidos

### 1️⃣ Simulador de Cluster (Análise de Logs em Bash)
Este projeto consiste em um ambiente didático simulando a operação de um cluster de 20 nós. O objetivo principal foi criar scripts em **Bash** para minerar logs, tratar erros, validar parâmetros e gerar relatórios automatizados diretamente pelo terminal.

#### 📂 Estrutura do Cluster Simulado
```text
cluster-simulado/
├── logs/
│   ├── auth.log              # Histórico de login/logout dos usuários
│   ├── processes_node1..20.log # Snapshots atuais de processos por nó
│   ├── jobs.log              # Histórico de 300 jobs (submit, start, end)
│   ├── backup_status.log     # Histórico de 15 backups simulados
│   └── errors.log            # 30 registros de erros e alertas
├── data/
│   ├── disk_status.csv       # Uso de disco por usuário
│   ├── cpu_usage.csv         # Uso de CPU por hora (72 registros)
│   └── users.csv             # Cadastro de 14 usuários
└── nodes.conf                # Configuração de hardware dos 20 nós
