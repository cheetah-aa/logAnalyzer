# SSH-Analyzer

**SSH-Analyzer** is a dual-interface security tool designed to parse system logs and identify brute-force login attempts. It provides both a fast **Command Line Interface (CLI)** for server-side work and a modern **Web Dashboard** for visual analysis.

---

## Features

* **Dual Interface:** Run it directly in your terminal or via a browser-based dashboard.
* **Intelligent Analysis:** Filters out "noise" (successful logins) to focus exclusively on `Failed password` and `Invalid user` events.
* **Modern Web Dashboard:**
    * **Drag-and-Drop:** Instant log analysis by dropping `.log` files.
    * **High-Level Stats:** At-a-glance view of total flagged IPs and the most frequent attacker.
    * **User Mapping:** Identifies which usernames (e.g., `root`, `admin`, `postgres`) are being targeted.
    * **Monospace Typography:** Industry-standard IP and log rendering for high readability.

---

## Tech Stack

**Backend**: Python 3.x, FastAPI, Uvicorn

**Frontend**: Vue 3, TypeScript, Vite, Pinia

**Styling**: Modern CSS3 with Flexbox/Grid
