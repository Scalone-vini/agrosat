# 🛰️ AgroSat — Alertas Climáticos para o Campo

> Conectando dados de satélite (NASA + INPE) e sensores locais (Arduino) para levar alertas climáticos precisos ao agricultor familiar — antes que o problema chegue à lavoura.

🔗 **[Ver demo ao vivo](https://scalone-vini.github.io/agrosat/)**

![status](https://img.shields.io/badge/status-protótipo%20de%20landing%20page-yellow)
![tech](https://img.shields.io/badge/stack-HTML%20%7C%20CSS-blue)

---

## 📌 Sobre o projeto

O AgroSat é uma proposta de solução para um problema real da agricultura familiar brasileira: a perda de safras por falta de alertas climáticos precisos e acessíveis. Segundo a EMBRAPA, o Brasil perde bilhões de reais por ano com eventos climáticos que poderiam ser minimizados com aviso antecipado.

Este repositório contém a **landing page de apresentação do conceito**, desenvolvida como projeto acadêmico da FIAP (Matéria 4 — Front-End Design).

## ⚠️ Status do projeto

Este é um **protótipo visual / página de apresentação**, não uma aplicação funcional. Aqui está o que existe hoje e o que é proposta de arquitetura:

| Componente | Status |
|---|---|
| Landing page (HTML/CSS responsivo) | ✅ Implementado |
| Design do fluxo de dados e UX do app | ✅ Implementado (conceitual) |
| Integração real com NASA POWER API | 🔜 Não implementado — próxima etapa |
| Integração real com dados INPE (BDQueimadas/CPTEC) | 🔜 Não implementado — próxima etapa |
| Leitura de sensores Arduino (DHT22, capacitivo, pluviômetro) | 🔜 Não implementado — próxima etapa |
| App mobile / backend de alertas | 🔜 Não implementado — próxima etapa |

## 💡 A ideia

- **Coleta**: dados climáticos da NASA POWER API + satélites/previsão do INPE + sensores Arduino instalados na propriedade
- **Processamento**: cruzamento dos dados para calcular risco por cultura e fase da lavoura
- **Alerta**: notificação (push/SMS/WhatsApp) até 48h antes de eventos críticos como geada, seca ou granizo
- **Ação**: o produtor toma decisões preventivas com base em dados reais da sua própria terra, não em previsões genéricas de TV

## 🎯 Público-alvo

- Agricultores familiares (até 4 módulos fiscais)
- Técnicos agrícolas que atendem múltiplas propriedades
- Cooperativas rurais

## 🛠️ Tecnologias utilizadas (nesta etapa)

- **HTML5** semântico
- **CSS3** (Grid, Flexbox, variáveis, responsividade)
- **Google Fonts** (Playfair Display + Montserrat)

> Próximas etapas do roadmap devem incorporar JavaScript para consumo das APIs e Python para o processamento/classificação de risco no backend.

## 🚀 Como rodar localmente

```bash
git clone https://github.com/Scalone-vini/agrosat.git
cd agrosat
# Basta abrir o index.html no navegador,
# ou usar uma extensão como Live Server no VS Code
```

## 🗺️ Roadmap

- [ ] Integrar API real da NASA POWER
- [ ] Integrar dados do INPE (previsão + alerta de geada por município)
- [ ] Protótipo de hardware com Arduino + transmissão LoRa
- [ ] MVP funcional do app (cadastro, GPS da propriedade, notificações)
- [ ] Painel para técnicos agrícolas e cooperativas

## 👥 Equipe

Projeto desenvolvido para a disciplina **Front-End Design** — FIAP, 2026.

| Nome | RM |
|---|---|
| Vinicius Scalone | 573783 |
| Rafael de Souza | 568777 |

## 📄 Licença

Projeto acadêmico sem licença definida — uso educacional.
