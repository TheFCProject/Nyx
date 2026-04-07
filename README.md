# 🌙 Nyx

> The high-performance guardian for your Discord community.

Nyx is a next-generation, high-speed moderation and utility bot designed from the ground up for scale and responsiveness. Built on the core philosophy that moderation tools should be instant and intuitive, Nyx uses the fastest modern stack available.

### Why Nyx?

* **⚡ Seyfert Engine:** Leveraging the speed of the Seyfert framework for near-zero latency command processing.
* **🐰 Bun Runtime:** Built using Bun for optimized performance, rapid startup, and native TypeScript execution.
* **🐘 PostgreSQL + Drizzle:** An efficient, relational database backend providing robust infraction tracking and server configuration management.
* **🔒 Moderation First:** Advanced automod, rapid purge tools, and timed punishments designed for high-traffic servers.

---

### Prerequisites

Before setting up Nyx locally, ensure you have:

* [Bun](https://bun.sh/) installed.
* A [PostgreSQL](https://www.postgresql.org/) database instance running.
* A Discord Bot Token from the [Developer Portal](https://discord.com/developers/applications).

### Local Setup

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/nyx.xyz.git](https://github.com/YOUR_USERNAME/nyx.xyz.git)
    cd nyx.xyz
    ```

2.  **Install Dependencies:**
    ```bash
    bun install
    ```

3.  **Configure Environment:**
    Copy the `.env.example` to a new file named `.env` and fill in your details:
    ```bash
    cp .env.example .env
    ```

4.  **Setup Database (Drizzle):**
    Generate and run the initial migrations:
    ```bash
    bun drizzle-kit generate:pg
    bun drizzle-kit push:pg
    ```

5.  **Start Nyx:**
    ```bash
    bun src/main.ts
    ```

### Technology Stack

* **Runtime:** [Bun](https://bun.sh/)
* **Language:** [TypeScript](https://www.typescriptlang.org/)
* **Library:** [Seyfert](https://www.seyfert.dev/)
* **Database:** [PostgreSQL](https://www.postgresql.org/)
* **ORM:** [Drizzle ORM](https://orm.drizzle.team/)

---

### Meet our fellow developers
| highschoolcrackhead. | alexxxzdevelops |
| -------- | -------- |

---

### License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
