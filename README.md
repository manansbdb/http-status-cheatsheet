<p align="center">
  <img src="docs/banner.svg" alt="HTTP Status Cheatsheet banner" width="100%" />
</p>

<h1 align="center">http-status-cheatsheet</h1>

<p align="center">
  <strong>EN</strong> HTTP status codes table — common codes explained<br/>
  <strong>PT</strong> Tabela de códigos HTTP — códigos comuns explicados
</p>

<p align="center">
  <a href="https://github.com/manansbdb/http-status-cheatsheet/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/HTTP-e34c26?style=for-the-badge" alt="HTTP" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A markdown **HTTP status codes** cheatsheet for APIs and debugging. | Uma cheatsheet markdown de **códigos de estado HTTP** para APIs e debugging. |
| Open `STATUS_CODES.md` whenever you pick a response code. | Abre `STATUS_CODES.md` sempre que escolheres um código de resposta. |

```mermaid
flowchart LR
  A["🌐 Request"] --> B["📚 STATUS_CODES.md"]
  B --> C["🔢 Pick 2xx/4xx/5xx"]
  C --> D["📤 Response"]
  style A fill:#2563eb,stroke:#1d4ed8,color:#fff
  style B fill:#e34c26,stroke:#b91c1c,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/http-status-cheatsheet.git
cd http-status-cheatsheet
```

### 2) Copy / Copia

```bash
mkdir -p docs/api
cp STATUS_CODES.md docs/api/http-status-codes.md
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/http-status-cheatsheet.git
# open STATUS_CODES.md
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `STATUS_CODES.md` | Status code table |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
http-status-cheatsheet/
├── docs/banner.svg
├── STATUS_CODES.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
