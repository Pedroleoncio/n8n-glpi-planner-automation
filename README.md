# 🚀 GLPI → Planner Automation (n8n)

Automação completa utilizando n8n para integração entre:

- 🎫 GLPI (Service Desk)
- 📊 Microsoft Planner
- 💬 Microsoft Teams

---

## 🧠 Overview

O fluxo automatiza o processamento de chamados GLPI, separando entre:

- Chamados de Projeto
- Chamados Operacionais

---

## ⚙️ Funcionalidades

✅ Integração com API do GLPI  
✅ Classificação automática de chamados  
✅ Criação de tarefas no Microsoft Planner  
✅ Evita duplicações de tasks  
✅ Geração de painel "Gestão à Vista"  
✅ Envio de dashboard para Teams  

---

## 🔗 Arquitetura

GLPI → n8n → Tratamento → Planner → Teams

---

## 📊 Inteligência Aplicada

- Normalização de categorias
- Priorização automática
- Identificação de SLA vencido
- Ranking de chamados mais antigos
- Consolidação de indicadores

---

## 🚧 Segurança

⚠️ Este projeto é uma versão **SANITIZADA**  
Nenhuma credencial real está incluída.

---

## 🛠️ Como usar

1. Importar o JSON no n8n  
2. Configurar credenciais:
   - GLPI API
   - Microsoft Graph API
3. Ajustar:
   - Plan ID
   - Bucket ID
4. Executar fluxo

---

## 🧩 Stack

- n8n
- GLPI API
- Microsoft Graph API
- JavaScript (Code Nodes)

---

## 💡 Autor

Pedro Henrique  
Analista de Sistemas Sênior | ERP | Integrações | Automação | Data
