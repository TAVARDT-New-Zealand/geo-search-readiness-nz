# Generative Engine Optimization (GEO) Auditor

[![GEO Auditor](https://img.shields.io/badge/TAVARDT-AI%20Search%20GEO-5b3cf5.svg)](https://tools.tavardt.com/nz/ai-search-readiness-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

CLI auditor for Generative Engine Optimization (GEO), inspecting AI crawler access, Schema.org entities, and semantic discoverability.


***

## GEO Verification Capabilities

* **AI Crawler Directive Inspection**: In-depth audit of `robots.txt` permissions for leading AI agents including GPTBot, OAI-SearchBot, PerplexityBot, ClaudeBot, and Google-Extended.
* **Entity Extraction and Structured Data**: Detection and validation of Schema.org JSON-LD structured entities for LLM knowledge graph grounding.
* **Semantic Hierarchy and Context**: Verification of H1 heading tags and meta description completeness for accurate passage retrieval.
* **Readiness Scoring**: Quantitative 0-100 diagnostic score with prioritized technical remediation actions.

***

## Installation and Quick Start

Requires Python 3.8 or higher. Built strictly using the Python standard library with zero external dependencies.

```bash
git clone https://github.com/TAVARDT-New-Zealand/geo-search-readiness-nz.git
cd geo-search-readiness-nz
python geo_auditor.py enterprise.co.nz
```

To export results in structured JSON format:

```bash
python geo_auditor.py enterprise.co.nz -json
```

***

## AI Search and Semantic Consulting

For enterprise structured data modeling and AI agent visibility optimization in New Zealand, contact **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/nz/
* **Diagnostic Suite:** https://tools.tavardt.com/nz/
* **Technical Contact:** https://ag.tavardt.com/nz/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
