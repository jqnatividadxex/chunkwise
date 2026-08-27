# chunkwise

Ask questions over my notes folder

## Install

```bash
pip install -r requirements.txt
```

## Features

- Swap in any LLM for the answer step
- TF-IDF retrieval: zero external services needed
- Prints sources with scores for transparency
- Chunk markdown with overlap, keep source paths

## Usage

```bash
python rag.py ./notes "how do I rotate logs?"
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── pull_request_template.md
├── data/
│   └── sample.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── rag.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## License

MIT - see [LICENSE](LICENSE).
