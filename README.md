# ACI606 - Container Lab

Starter for the class **Containers in Cloud with Docker and GitHub Codespaces**.

## Quick test

```bash
docker version
docker compose version
```

Build:

```bash
docker build -t aci606-api:v1 .
```

Run:

```bash
docker run --rm -p 8001:8000 aci606-api:v1
```

Open `/docs` or `/` on the forwarded port 8001.

The full sequence is described in the laboratory guide.
