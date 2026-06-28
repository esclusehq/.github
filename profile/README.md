# Escluse

Your hardware, your rules. Game server management on your own machines.

**Website**: [https://esluce.com](https://esluce.com)

---

### What We Build

Escluse is a self-hosted game server management platform. You bring the hardware — a VPS, a dedicated server, or an old laptop — and we provide the software.

Install the lightweight Solys agent on any Linux machine, connect it to your dashboard, and manage game servers from one place. No lock-in, no paying for compute you are not using.

---

### Current Status

- **Early Access** — actively developed, feedback welcome
- **Supported games**: Minecraft (Java & Bedrock)
- More games coming based on community requests

---

### Why Escluse?

Most solutions either lock you into expensive hosting or leave you wrestling with command-line configs. Escluse gives you the control of self-hosting without the complexity. A custom Rust agent (Solys) handles the heavy lifting, while the dashboard gives you one-click mod management, backups, monitoring, and scheduling.

---

### Tech Stack

- **Backend**: Rust (Axum)
- **Frontend**: React + TypeScript
- **Database**: PostgreSQL + Redis
- **Agent**: Rust (Solys Agent)

---

### Get Started

Install the agent on your Linux machine and link it to your dashboard:

```bash
curl -fsSL https://get.esluce.com/latest/install.sh | bash
```

Visit [https://esluce.com](https://esluce.com) for more info.

Star us on GitHub if you like what we build.
