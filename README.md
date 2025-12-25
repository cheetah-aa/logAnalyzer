# SSH-Analyzer

**SSH-Analyzer** is a modern web-based companion to the [logAnalyzer](https://github.com/cheetahh1/LogAnalyzer.git) CLI tool. While the core analysis is powered by the existing engine, this interface provides a visual, drag-and-drop dashboard for users who prefer a GUI-driven approach to identifying brute-force security threats without needing to interact with the command line.

---

## Features

* **Powered by logAnalyzer:** Utilizes the robust [logAnalyzer](https://github.com/cheetahh1/LogAnalyzer.git) Python core to identify `Failed password` and `Invalid user` events.
* **Log Analysis:** Filters out "noise" (successful logins) to focus exclusively on `Failed password` and `Invalid user` events.
* **Zero CLI Knowledge Required:** Simply drag and drop your `.log` file into the browser to get instant results.
* **Modern Web Dashboard:**
    * **Drag-and-Drop:** Instant log analysis by dropping `.log` files.
    * **High-Level Stats:** At-a-glance view of total flagged IPs and the most suspicious IP.
    * **User Mapping:** Identifies which usernames (e.g., `root`, `admin`, `postgres`) are being targeted.

---

## Tech Stack

**Backend**: Python 3.x, FastAPI, Uvicorn

**Frontend**: Vue 3, TypeScript, Vite, Pinia

**Styling**: Modern CSS3 with Flexbox/Grid
