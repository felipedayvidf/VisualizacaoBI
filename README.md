# 📊 Visualização BI (Dashboard Rotator)

Este projeto é um **visualizador automático de dashboards (Power BI)**, desenvolvido para uso em TVs, painéis corporativos ou monitores dedicados.

---

## 🚀 Funcionalidades

✅ Alternância automática entre dashboards (Power BI)  
✅ Exibição de imagem de conscientização (hidratação)  
✅ Controle de tempo por slide  
✅ Ciclo automático de exibição  
✅ Estrutura simples (apenas 1 arquivo HTML)  

---

## 🧠 Lógica de funcionamento

O sistema segue o seguinte fluxo:

- 📊 Dashboard 1 → 5 minutos  
- 📊 Dashboard 2 → 5 minutos  
- 🔁 Repete esse ciclo 3 vezes (total de 30 minutos)  
- 💧 Exibe imagem de conscientização ("beber água") por 1 minuto  
- 🔁 Reinicia o processo  

---

## 📁 Estrutura do projeto

VisualizacaoBI/
│
├── index.html      # Código principal
└── bebagua.png     # Imagem exibida a cada 30 minutos

---

## ⚙️ Como usar

### 1. Clonar ou baixar

```bash
git clone https://github.com/seu-usuario/VisualizacaoBI.git
