# 📊 Visualização BI com Controle por Horário

Este projeto exibe um dashboard do Power BI em tela cheia com atualização automática e exibição periódica de uma imagem de conscientização.

---

## 🚀 Funcionalidades

✅ Exibição contínua do Power BI  
✅ Atualização automática a cada 5 minutos  
✅ Exibição automática de imagem a cada meia hora  
✅ Controle baseado no horário real do sistema  
✅ Estrutura simples (1 arquivo HTML)  

---

## 🧠 Lógica do sistema

### 📊 BI (modo normal)
- Exibido continuamente
- Atualiza automaticamente a cada 5 minutos

---

### 💧 Imagem de conscientização

A imagem `bebagua.png` é exibida automaticamente:

- 🕒 **Todo HH:00 até HH:03**
- 🕒 **Todo HH:30 até HH:33**

Exemplos:
- 10:00 → imagem
- 10:30 → imagem
- 15:00 → imagem
- 15:30 → imagem

---

### ⚠️ Prioridade

A imagem **sempre tem prioridade sobre o BI**, mesmo que:

- esteja no momento de atualizar o dashboard
- o BI esteja carregando

---

## 📁 Estrutura

