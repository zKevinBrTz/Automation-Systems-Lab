
---

# 📁 🧠 2. docs/arquitetura.md

👉 Explica como o sistema funciona tecnicamente

```md id="d1"
# 🧠 Arquitetura do Sistema

O sistema é baseado em camadas interligadas:

---

## 🏗️ Estrutura

- Comandos → iniciam ações
- Core → processa lógica
- Eventos → conectam ações
- Entidades → executam comportamentos
- Respostas → retornam resultado

---

## 🔁 Fluxo geral

```mermaid
flowchart LR
A[Comando] --> B[Core]
B --> C[Evento]
C --> D[Entidade]
D --> E[Resposta]
