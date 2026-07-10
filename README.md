# Hi 👋, I'm Shwetanshu Sinha

### Backend & Distributed Systems | B.Tech CS @ NIT Delhi | Building systems that don't fall over

---

## 🚀 About Me

- 🎓 B.Tech Computer Science, NIT Delhi — entering final year
- 🧠 Focused on **backend engineering, distributed systems, and infrastructure** — not chasing frameworks, chasing fundamentals
- 🏗️ I'd rather understand *why* a system is architected a certain way than just ship a feature on top of it
- 🔐 Currently deep in cryptographic system design — envelope encryption, zero-knowledge storage, key derivation
- ⚡ Competitive programming + software projects + interview prep, run like a priority queue

---

## 🛠️ Tech Stack

### Backend & Systems
- Node.js, Express.js
- Distributed systems concepts (learning & building)
- System design, REST APIs, auth architecture (SSO/JWT from scratch)

### Data & Storage
- PostgreSQL (Neon), Drizzle ORM
- MongoDB, SQL

### Frontend (when the project needs it)
- React.js, Next.js, D3.js
- TypeScript, Tailwind CSS

### Security & Crypto
- AES-256-GCM envelope encryption
- Argon2id key derivation (`libsodium.js` / `hash-wasm`)
- Applied cryptography, PKI, TLS fundamentals

---

## 📌 Featured Projects

### 🎵 You Listen
A private, full-stack music streaming platform with admin-controlled uploads, YouTube ingestion, and a custom Spotify-like player.
- Modular backend built on a Repository-Service-Controller layered architecture (Express)
- Dual-layer caching (Redis server-side, SessionStorage client-side) for infinite-scroll performance
- Cloudflare R2 + signed URLs for audio delivery; YouTube ingestion via `yt-dlp` on a BullMQ worker queue
- Currently extending it with a content-based k-NN recommendation microservice

### 🔒 Legacy Locker
A zero-knowledge, end-to-end encrypted digital vault that hands down access to trusted nominees via inactivity-based or scheduled release.
- Client-side AES-256-GCM encryption — server only ever stores ciphertext, no plaintext or passwords
- Argon2-derived Master Password protects vault keys; nominee handover re-wraps the DEK with a one-time 6-digit Sharing PIN
- Dead-man's-switch triggers via node-cron + BullMQ/Redis-backed email delivery, checked against inactivity windows or a scheduled date

### 🔑 ZyloAuth (Zyloverse SSO)
Custom-built SSO powering the Zyloverse app suite — deliberately built without NextAuth to retain full control over auth internals.
- Node.js/Express, JWT, Drizzle ORM, Neon PostgreSQL
- Unifies Zyloverse apps: SpendWise (finance), Bookmark Manager, Goal Tracker, Recipe Manager

---

## 🤝 Connect With Me

- 🌐 Portfolio: [shwetanshu.vercel.app](https://shwetanshu.vercel.app/)
- 💼 LinkedIn: [linkedin.com/in/shwetanshu13](https://www.linkedin.com/in/shwetanshu13/)
- 📧 Email: shwetanshusinha13@gmail.com

---

## ⚡ Fun Fact

Football most weekdays, gym on the rest — consistency is the whole strategy, on the field and in the codebase.
