# HOZ Architecture

HOZ is the LLM analysis agent behind TradingAssist: a retail trader asks about a ticker and gets a scored, grounded pattern read with a server-built UI panel, and no trade instructions.

This repo holds the design write-up only: how the system is split into a deterministic context layer, one reasoning model, and a deterministic delivery layer; how cost, safety, and output quality are controlled; and what changed after running it in production.

Start with **[ARCHITECTURE.md](ARCHITECTURE.md)**.
