# Milestone 1: O Resgate (Arquitetura & Legado) 

## **Foco:** Estabilizar o ambiente e conectar com os dados de 2006. 

| ID | Issue (Título) | Descrição / Task | Prioridade |
| --- | --- | --- | --- |
| #01 | Config: Docker & Colima | Validar docker-compose e persistência no HD externo. | Alta |
| #02 | DB: Bridge Legacy | Criar script/config para ler o dp2006 (MariaDB 10.3). | Alta |
| #03 | Setup: Prisma ORM | Inicializar Prisma no Next.js e fazer o db pull do legado. | Média |
| #04 | Fix: Charset Latin1 | Tratar strings bugadas (acentos) na leitura do banco antigo. | Média |

---

# Milestone 2: O Novo Cérebro (ERP Core) 

## **Foco:** Cadastro de clientes e fluxo de orçamento moderno. 

| ID | Issue (Titulo) | Descrição / Task | Prioridade |
| --- | --- | --- | --- |
| #05 | Schema: Novo DB (SQLite) | Desenhar as tabelas de Clientes e OS de 2026. | Alta |
| #06 | Feature: Importador On-Demand | Botão no App para puxar dados do dp2006 para o Novo DB. | Alta |
| #07 | UI: Dashboard de Vendas | Tela inicial com resumo de orçamentos pendentes. | Média |
| #08 | Module: Gerador de PDF | Criar template de orçamento limpo para envio via WhatsApp. | Alta |

---

# Milestone 3: A Fusão (DAM & Chat) 

## **Foco:** Integração de arquivos e comunicação interna. 

| ID | Issue (Título) | Descrição / Task | Prioridade |
| --- | --- | --- | --- |
| #09 | Engine: Client-side Crop | Implementar resize de imagens no navegador antes do upload. | Média |
| #10 | Feature: Chat por Projeto | Sistema de mensagens vinculado a cada ID de Orçamento/OS. | Baixa |
| #11 | DAM: File Indexer | Criar o "Explorer" que lista arquivos do NAS via banco. | Baixa |
| #12 | Service: Thumbnailer | Worker para gerar miniaturas leves das artes pesadas. | Baixa |
