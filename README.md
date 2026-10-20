# Hakvin Vosteen

**Economics × AI engineering.** I build AI-native systems end-to-end — from data pipelines to MCP interfaces — and do research on behavior, markets and formal modeling.

## What I'm building

- **Uni-Management** — a personal operating system for university life, running fully in the cloud: automatic Stud.IP sync (hourly, incremental), hybrid RAG over course materials (BM25 + OpenAI embeddings, OCR for scans, every answer cited to the exact PDF page), university mail with agent-safe draft/send flow, calendar sync with conflict detection, and a daily 08:00 briefing automation. Exposed to ChatGPT and Claude as a single authenticated MCP endpoint with per-tool OAuth scopes.
- **statiq** — interactive statistical distribution explorer (32 distributions, live plots, parameter sliders, PyQt6 + scipy).

## Research

Independent researcher. Working papers and preprints on economics, behavior, and formal modeling → [hakvinv.github.io/H.Vosteen-Research-](https://hakvinv.github.io/H.Vosteen-Research-/)

## Stack

`Python` `FastMCP` `SQLite/FTS5` `OpenAI API` `Railway` `rclone` `pandas/scipy` `LaTeX`

## Principles

- Answers should cite sources, not vibes — every retrieval system I build returns file, page and hash.
- Automate the boring loop (sync, index, brief), keep humans on the decision.
- Ship small, verify live, write it down.
