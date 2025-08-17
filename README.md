# Nova-Noah

Utilities and notebooks I’m building while leveling up from hands-on IT & business ops into Python-powered automation and pattern recognition.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Joew03189/nova-noah/blob/main/NOAH.ipynb)

## What’s inside
- **NOAH.ipynb** — working notebook (Colab-ready) that scaffolds a minimal “nova” package (`nova/agents`, `nova/memory`, `models/`) and demonstrates configuration with Pydantic plus basic automation hooks.

## How to run (Colab)
1. Click the **Open in Colab** badge above.
2. Runtime ▶️ **Run all**.
3. (Optional) Set your keys as Colab secrets so they’re never in code:
   - Runtime ▸ **Manage sessions** ▸ Secrets ▸ `OPENAI_API_KEY`

## Tech
- Python 3.x, Pydantic
- Google Colab
- (Planned) LLM backends, simple agents, lightweight memory

## Roadmap
- [ ] Clean, importable `nova` package layout
- [ ] Example agent script (CLI)
- [ ] Simple pattern-recognition demo
- [ ] Unit tests & GitHub Actions
- [ ] Add LICENSE and CONTRIBUTING

## Notes
API keys are never committed to the repo. Use environment variables/Colab secrets.
