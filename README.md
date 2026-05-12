# 🛡️ LinuxBot Forense

> Inteligência Forense, Automação Defensiva e Monitoramento em Tempo Real

---

## 📖 Descrição do Projeto

O **LinuxBot Forense** é uma plataforma de engenharia de segurança focada na análise comportamental de logs em tempo real para ambientes Linux de alta disponibilidade.

O sistema monitora serviços **Nginx** e **HAProxy**, identifica atividades suspeitas e executa bloqueios automáticos diretamente no kernel Linux utilizando **Nftables**.

Além da mitigação automática, a plataforma integra o **Sentinela Panel**, responsável pelo monitoramento visual, auditoria operacional e inteligência defensiva centralizada.

---

# 🛰️ Sentinela Panel

O **Sentinela Panel** é o núcleo de monitoramento e observabilidade da plataforma LinuxBot Forense.

O painel fornece:

- 📊 Monitoramento de eventos em tempo real
- 🚨 Alertas automáticos de ameaças
- 🌐 Visualização de IPs maliciosos
- 📈 Estatísticas de ataques e bloqueios
- 🔥 Status operacional do Firewall
- 🧠 Inteligência de reputação IP
- 📂 Auditoria completa das ações executadas
- ⚡ Dashboard de performance da infraestrutura

---

## 🧠 Tecnologias Integradas

### 🚀 Redis
Processamento de reputação IP e contagem de eventos em milissegundos para resposta imediata.

### 🗄️ MariaDB
Persistência forense, blacklist permanente e armazenamento de trilhas de auditoria.

### 🔥 Nftables
Firewall executado diretamente no kernel Linux com alta performance e baixo overhead.

### 🛰️ Sentinela Panel
Painel centralizado para monitoramento operacional, observabilidade e inteligência defensiva.

---

## 📂 Arquitetura Modular

- **Motor de Decisão**
  - Cálculo inteligente de reputação baseado em erros HTTP e comportamento suspeito.

- **Persistência Híbrida**
  - Integração entre memória volátil (Redis) e armazenamento SQL permanente.

- **Audit Log**
  - Rastreabilidade total das ações defensivas executadas pela plataforma.

- **Threat Intelligence**
  - Correlação de eventos para identificação avançada de ameaças.

- **Sentinela Monitor**
  - Dashboard de monitoramento em tempo real da infraestrutura protegida.

---

## ⚙️ Stack

```bash
Python
Redis
MariaDB
Nftables
Nginx
HAProxy
Linux
Sentinela Panel
