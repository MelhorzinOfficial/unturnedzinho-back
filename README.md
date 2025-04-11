# 🧩 Unturned Server Manager - Backend
Backend para gerenciamento de servidor dedicado Unturned, oferecendo uma API RESTful para automação e controle remoto de funcionalidades administrativas, como execução de comandos, monitoramento de jogadores e configuração do servidor.

---

## 📦 Tecnologias Utilizadas
Go + Fiber – Framework web leve e rápido
Docker – Containerização do ambiente
Redis / RabbitMQ – Pub/Sub (opcional para comandos assíncronos)
WebSocket – Para comunicação em tempo real (opcional)
MongoDB / PostgreSQL – Armazenamento de dados persistentes
RCON / Sockets personalizados – Comunicação com o servidor Unturned

---

## 🚀 Funcionalidades
- 🔐 Autenticação de usuários (Administração)
- ⚙️ Execução de comandos no servidor
- 📡 Monitoramento em tempo real dos jogadores online
- 📜 Log de eventos e comandos
- 🧪 Endpoint de healthcheck
- 📁 Configuração e reinício remoto do servidor
- 📈 Estatísticas do servidor e players
