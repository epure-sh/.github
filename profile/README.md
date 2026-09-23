<p align="center">
  <img src="lockup.svg" alt="Epure" width="220" />
</p>

<p align="center">
  <strong>Exception-only error monitoring.</strong><br />
  Keep your Sentry SDK. Point the DSN here.<br />
  Two containers. Readable stacks. No Kafka, Redis, or ClickHouse.
</p>

<p align="center">
  <a href="https://epure.sh">Website</a>
  ·
  <a href="https://epure.sh/docs">Docs</a>
  ·
  <a href="https://github.com/epure-sh/epure">Product</a>
  ·
  <a href="https://github.com/epure-sh/epure/discussions">Discussions</a>
</p>

---

### Product

| Repository | What it is |
|---|---|
| [**epure**](https://github.com/epure-sh/epure) | Self-hosted exception tracker — Rust + PostgreSQL 16, Apache 2.0 |

```bash
git clone https://github.com/epure-sh/epure.git
cd epure
docker compose up -d
# → http://localhost:8080
```

Image: [`ghcr.io/epure-sh/epure`](https://github.com/epure-sh/epure/pkgs/container/epure)

### Scope

Epure tracks production exceptions: ingest, grouping, sourcemaps (JS/TS), triage, alerts, releases.

It does **not** ship tracing, session replay, continuous profiling, or generic log storage.

### Community

- Bugs & SDK gaps → [Issues](https://github.com/epure-sh/epure/issues)
- Setup questions → [Discussions](https://github.com/epure-sh/epure/discussions)
- Security → [SECURITY.md](https://github.com/epure-sh/epure/blob/main/.github/SECURITY.md) · `security@news.epure.sh`
- Contribute → [CONTRIBUTING.md](https://github.com/epure-sh/epure/blob/main/CONTRIBUTING.md)

Managed hosting (optional): [epure.sh](https://epure.sh)
