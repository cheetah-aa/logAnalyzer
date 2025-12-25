# SSH-Analyzer

**SSH-Analyzer** is a dual-interface security tool designed to parse system logs and identify brute-force login attempts. It provides both a fast **Command Line Interface (CLI)** for server-side work and a modern **Web Dashboard** for visual analysis.

---

## Features

* **Log Analysis:** Filters out "noise" (successful logins) to focus exclusively on `Failed password` and `Invalid user` events.
* **Modern Web Dashboard:**
    * **Drag-and-Drop:** Instant log analysis by dropping `.log` files.
    * **High-Level Stats:** At-a-glance view of total flagged IPs and the most suspicious IP.
    * **User Mapping:** Identifies which usernames (e.g., `root`, `admin`, `postgres`) are being targeted.

---

## Tech Stack

**Backend**: Python 3.x, FastAPI, Uvicorn

**Frontend**: Vue 3, TypeScript, Vite, Pinia

**Styling**: Modern CSS3 with Flexbox/Grid
