# 🛡️ Sentinela

> Inteligência Forense • Automação Defensiva • Monitoramento em Tempo Real • Edge Security

---

## 📖 Descrição do Projeto

O **Sentinela** é uma plataforma de engenharia de segurança focada em análise comportamental de logs em tempo real para ambientes Linux de alta disponibilidade.

O sistema monitora serviços **Nginx** e **HAProxy**, identifica padrões de atividade suspeita e executa ações de mitigação automática diretamente no kernel Linux utilizando **nftables**.

Além da resposta automatizada a incidentes, a plataforma integra o **Sentinela Panel**, responsável pela observabilidade, auditoria operacional e centralização da inteligência defensiva.

---

## 🛰️ Sentinela Panel

O **Sentinela Panel** é o núcleo de monitoramento e observabilidade da plataforma Sentinela Forense.

Ele fornece visibilidade completa da infraestrutura e do tráfego de segurança em tempo real.

### Funcionalidades

- 📊 Monitoramento de eventos em tempo real
- 🚨 Detecção e alertas automáticos de ameaças
- 🌐 Visualização de IPs maliciosos e padrões de ataque
- 📈 Estatísticas de tráfego, bloqueios e incidentes
- 🔥 Status operacional do firewall (nftables)
- 🧠 Análise de reputação de IPs
- 📂 Auditoria completa de ações de segurança
- ⚡ Métricas de performance da infraestrutura

---

## 🧠 Tecnologias Integradas

### 🚀 Redis
Camada de processamento de alta velocidade para reputação de IPs e contagem de eventos em tempo real.

### 🗄️ MariaDB
Armazenamento persistente de dados forenses, blacklist e histórico de incidentes.

### 🔥 nftables
Firewall em nível de kernel Linux para filtragem de tráfego com alta performance e baixo overhead.

### 🛰️ Sentinela Panel
Sistema centralizado de observabilidade e inteligência de segurança.

---

## 📂 Arquitetura Modular

### 🧭 Motor de Decisão
Responsável por calcular reputação e identificar comportamentos suspeitos com base em eventos HTTP.

### 💾 Persistência Híbrida
Integração entre dados em memória (Redis) e armazenamento persistente (MariaDB).

### 📜 Audit Log
Registro completo de ações executadas pela plataforma para rastreabilidade e análise forense.

### 🧠 Threat Intelligence
Correlação de eventos para identificação de padrões avançados de ataque.

### 📡 Sentinela Monitor
Dashboard de observabilidade em tempo real da infraestrutura protegida.

<img width="1204" height="880" alt="Panel Sentinela" src="https://github.com/user-attachments/assets/cf7d2cea-1848-4564-962c-1239c2e871c9" />

---

## ⚙️ Stack Tecnológica

- Python
- Redis
- MariaDB
- nftables
- Nginx
- HAProxy
- Linux
- Sentinela Panel

---

## 🧠 Objetivo do Sistema

- Detectar e mitigar ameaças em tempo real
- Reduzir superfície de ataque na borda
- Garantir alta disponibilidade e resiliência
- Automatizar resposta a incidentes
- Centralizar observabilidade de segurança

---

<div align="center">

🛡️ Linux Security Engineering  
DICCARLO• Edge Defense • 2026

</div>
