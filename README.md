# 🚀 GLPI → Planner Automation (n8n)

Automação completa utilizando n8n para integração entre:

- 🎫 GLPI (Service Desk)
- 📊 Microsoft Planner
- 💬 Microsoft Teams

---

## 🧠 Overview

Este fluxo automatiza o ciclo de vida de chamados corporativos, promovendo:

- Integração entre Service Desk e gestão de projetos  
- Classificação inteligente de tickets  
- Redução de atividades manuais  
- Aumento da visibilidade operacional  

---

## 🎯 Objetivo

Criar uma camada de automação entre sistemas corporativos, garantindo:

- Gestão eficiente de chamados  
- Organização de demandas em backlog estruturado  
- Monitoramento contínuo de SLA  
- Apoio à tomada de decisão baseada em dados  

---

## ⚙️ Funcionalidades

✅ Integração com API do GLPI  
✅ Classificação automática de chamados (Projeto vs Operacional)  
✅ Criação automatizada de tarefas no Microsoft Planner  
✅ Evita duplicação de atividades  
✅ Geração de painel "Gestão à Vista"  
✅ Envio de dashboard para Microsoft Teams  
✅ Consolidação de indicadores operacionais  

---

## 🔗 Arquitetura (Visão Simplificada)

GLPI → n8n → Tratamento → Planner → Teams

---

## 🏗️ Arquitetura da Solução

```mermaid
flowchart LR

A[GLPI API] --> B[n8n Workflow]

B --> C[Data Processing]
C --> D{Classification}

D -->|Project| E[Microsoft Planner]
D -->|Operational| F[SLA Analysis]

F --> G[Metrics Engine]
G --> H[Adaptive Card]

E --> I[Planner Tasks]
H --> J[Microsoft Teams]
