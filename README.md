## About

i've built systems that make documents searchable and answerable, engineer guardrails around llm-driven financial decisions, trace business metrics back to their drivers, make algorithms compete using information theory, and turn everyday food descriptions into structured nutrition data.

somewhere along the way, i've worked across ai, machine learning, genai, computer vision and data.

i like interesting problems, going down rabbit holes, and figuring out how to turn an idea into something that actually works.

sometimes that means building the obvious solution.

sometimes it means wondering if there's a completely different way to do it.

either way, i'm usually building something.

## Projects

### RootSignal
[root-cause analytics for sales and supply operations](https://github.com/vidit-16/RootSignal) traces metric movements to the segments behind them, separates performance changes from mix effects, estimates business impact, and produces evidence-backed investigation signals. tested on 1M+ real invoice lines; the best forecast beats naive by 38.8% WAPE

### BaseDrift
[a pre-authorization decision layer for outbound payments](https://github.com/vidit-16/BaseDrift) combines deterministic policy rules with an LLM semantic layer, with a focus on authorization provenance, fail-safe handling, auditability, and adversarial testing. 15/15 mutations of its stated invariants caught by the suite

### PayFloor
[an affordability engine for financial requests](https://github.com/vidit-16/PayFloor) decides whether to pay now, in parts, in instalments, later, or not at all. the model only extracts facts; deterministic code makes the call and guarantees the balance never drops below the user's minimum over 90 days

### DocEngine
[question answering over PDFs](https://github.com/vidit-16/DocEngine) with page-cited sources, comparing semantic, BM25 and hybrid retrieval on a labelled question set before picking a default

### DesiMacros
[a conversational nutrition tracker for Indian diets](https://github.com/vidit-16/DesiMacros) turns free-form meal descriptions into structured food entries and combines nutrition lookup with rule-based insights

### Wordle Solver
[constraint vs entropy optimization](https://github.com/vidit-16/WordleSolver) built around Wordle-accurate feedback handling, candidate reduction, and information-gain scoring, benchmarked on all 2,315 official answers

### Food Vision
[a ConvNeXt-Tiny food classifier](https://github.com/vidit-16/foodVision) fine-tuned on Food-101 (91.9% top-1, up from 82.2% with ResNet-50), served through FastAPI and packaged with Docker

## Tools

Python · SQL · Pandas · NumPy · PyTorch · timm · Scikit-learn · Hugging Face Transformers · sentence-transformers · FAISS · LLMs · Computer Vision · FastAPI · Streamlit · PostgreSQL · SQLite · Docker · Git · GitHub Actions · pytest

[LinkedIn](https://www.linkedin.com/in/vidit-choudhary-514a98227/) · [Email](mailto:choudharyvidit5@gmail.com)
