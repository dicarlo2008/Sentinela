# 🛡️ LinuxBot Forense

> Inteligência Forense e Automação de Defesa de Borda

---

## 📖 Descrição do Projeto

O **LinuxBot Forense** é uma solução de engenharia de segurança focada na análise de logs em tempo real para servidores **Nginx** e **HAProxy**.

O motor identifica comportamentos maliciosos e aplica bloqueios automáticos para proteger a infraestrutura.

---

## 🧠 Tecnologias Integradas

### 🚀 Redis
Processamento de contagem de ataques em milissegundos para resposta imediata.

### 🗄️ MariaDB
Armazenamento de base de dados para análise forense e blacklist persistente.

### 🔥 Nftables
Bloqueios executados diretamente no Kernel Linux com impacto mínimo na CPU.

---

## 📂 Arquitetura Modular

- **Motor de Decisão**
  - Cálculo de reputação baseado em erros HTTP.

- **Persistência Híbrida**
  - Dados voláteis (RAM) e permanentes (SQL).

- **Audit Log**
  - Rastreabilidade total das ações tomadas.

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
```

---

## 📸 Preview

Adicione screenshots aqui:

```md
![Dashboard](images/dashboard.png)
```

---

## 📜 Licença

MIT License

---

<div align="center">

DICCARLO © 2026

</div>
