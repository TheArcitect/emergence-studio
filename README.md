# Emergence Studio — Imagine with Claude (Research Demo)

Public landing + reproducible SharePack for my Imagine with Claude session.

- **Goal:** Reveal phase shifts in accuracy under controlled stress (tokens, latency, noise, tool-access).
- **Artifacts:** Brief (HTML/PDF), results CSV, heatmaps, delta plots, provenance.json (with SHA256 + deterministic rerun command).

## Contact

- **Name:** Michael Schaeffer
- **Email:** michael@letsexperiment.com
- **LinkedIn:** https://www.linkedin.com/in/michael-schaeffer-ba3762382/
- **Short link:** (optional) https://michael.link/claude

## Deterministic re-run

```bash
/emergence_studio --seed=42 --config=v1.1 --tasks=math,table,tool \
  --stressors=context,noise,latency,paraphrase,tool_access
```
