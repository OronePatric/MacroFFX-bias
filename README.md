PROJECT STRUCTURE. 

MacroFundamentalFX-bias-engine/
├─ .github/
│  └─ workflows/ci.yml
├─ docker/
│  ├─ Dockerfile
│  └─ docker-compose.yml
├─ docs/
│  └─ runbook.md
├─ src/
│  ├─ policy_bias/
│  │  ├─ __init__.py
│  │  ├─ config.py
│  │  ├─ fetchers/
│  │  │  ├─ __init__.py
│  │  │  ├─ fed.py
│  │  │  ├─ cme_fedwatch.py
│  │  │  └─ central_banks.py
│  │  ├─ scoring/
│  │  │  ├─ __init__.py
│  │  │  ├─ text_score.py
│  │  │  ├─ market_score.py
│  │  │  └─ combine.py
│  │  ├─ storage/
│  │  │  ├─ __init__.py
│  │  │  ├─ csv_store.py
│  │  │  └─ gsheet_store.py
│  │  ├─ cli.py
│  │  └─ utils.py
├─ tests/
│  ├─ test_text_score.py
│  └─ test_market_score.py
├─ environment.yml
├─ requirements.txt
├─ README.md
├─ .gitignore
├─ .pre-commit-config.yaml
└─ setup.cfg / pyproject.toml (optional)
