# SPECTER: Human Voice Extinction Tracker

SPECTER is an archaeologist of thought. It maps where human voice persists, where it is dying, and where it is being replaced by AI at the domain level.

## Overview

As the internet increasingly floods with synthetic content, SPECTER provides the tools to monitor the health of the human voice online. By analyzing domain-level data, this project helps track the shift from human-authored content to AI-generated or machine-curated material.

## Core Objectives

- **Map Human Persistence:** Identify online spaces and domains where high-quality human writing still thrives.
- **Detect AI Replacement:** Monitor for rapid degradation in domains, signaling a shift toward AI-generated or synthetic content.
- **Signal Human Voice Health:** Quantify the 'Human-ness' of a domain using multi-faceted metrics.

## Data & Methodology

SPECTER utilizes a multi-layered detection pipeline to analyze content:

1. **Stylometric Fingerprinting:** Identifying unique human writing patterns.
2. **Perplexity & Burstiness:** Analyzing the statistical patterns associated with LLM outputs.
3. **Domain-level Tracking:** Aggregating data across thousands of URLs.
4. **Database-backed Analytics:** All metadata—including crawl frequency and HAS (Human-Authorship Score)—is persisted in a SQLite database.

## Getting Started

1. Install requirements: `pip install -r requirements.txt`
2. Configure your crawl list in `config/seeds.yaml`.
3. Initialize database: `python scripts/init_db.py`
4. Run the tracker: `python main.py`

## Contributing

We encourage contributions from researchers, archaeologists of thought, and anyone concerned with the future of the human internet. Please see our [Contributing](CONTRIBUTING.md) guide.

## License

MIT License (c) 2026 Andrew Arkins.