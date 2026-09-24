# Agent Lab Method

[![tests](https://github.com/janzong/agent-lab-method/actions/workflows/tests.yml/badge.svg)](https://github.com/janzong/agent-lab-method/actions/workflows/tests.yml)

Minimal read-only method package extracted from `agent-lab-console`.

It contains the shared run schema, the synthetic GenMentor adapter, and synthetic fixtures. It does not contain private runs, replay archives, deployment runners, credentials, prompts, or model responses.

```bash
python -m venv .venv
.venv/bin/pip install -e ".[test]" -i https://pypi.tuna.tsinghua.edu.cn/simple
.venv/bin/python -m pytest -q
```

## Reproductions wanted

This is `v0.1.0`. I am looking for **3 independent reproductions by non-authors**:
<https://github.com/janzong/agent-lab-method/issues/1> — expected **9 passed**.
