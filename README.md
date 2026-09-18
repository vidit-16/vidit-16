## About

i've built systems that make documents searchable and answerable, engineer guardrails around llm-driven financial decisions, trace business metrics back to their drivers, make algorithms compete using information theory, and turn everyday food descriptions into structured nutrition data.

somewhere along the way, i've worked across ai, machine learning, genai, computer vision and data.

i like interesting problems, going down rabbit holes, and figuring out how to turn an idea into something that actually works.

sometimes that means building the obvious solution.

sometimes it means wondering if there's a completely different way to do it.

either way, i'm usually building something.

**try them live:** [DocEngine](https://doc--engine.streamlit.app/) · [Wordle Solver](https://wordle--solver.streamlit.app/) · [DesiMacros](https://desimacros.onrender.com/)

## Projects

### RootSignal
[root-cause analytics for sales and supply operations](https://github.com/vidit-16/RootSignal) traces metric movements to the segments behind them, separates performance changes from mix effects, estimates business impact, and produces evidence-backed investigation signals. the same pipeline runs unchanged on 1M+ real invoice lines from a uk retailer, which broke three things generated data never could

### BaseDrift
[a pre-authorization decision layer for outbound payments](https://github.com/vidit-16/BaseDrift) combines deterministic policy rules with an LLM semantic layer, with a focus on authorization provenance, fail-safe handling, auditability, and adversarial testing. every one of the 15 mutations of its stated invariants is caught by the suite, so the rules cannot be quietly weakened

### PayFloor
[an affordability engine for financial requests](https://github.com/vidit-16/PayFloor) decides whether to pay now, in parts, in instalments, later, or not at all. the model only extracts facts; deterministic code makes the call and guarantees the balance never drops below the user's minimum over 90 days

### DocEngine
[question answering over PDFs](https://github.com/vidit-16/DocEngine) with page-cited sources. every retrieval choice is settled by measurement against a labelled question set with a held-out split rather than by preference, which took correct answers from 75.0% to 86.8% · [live](https://doc--engine.streamlit.app/)

### DesiMacros
[a conversational nutrition tracker for Indian diets](https://github.com/vidit-16/DesiMacros) turns free-form meal descriptions into structured food entries, with dish values cross-checked against two published references. median calorie error cut from 50.0% to 14.8%, and a food the databases do not know is now estimated and labelled rather than silently counted as zero · [live](https://desimacros.onrender.com/)

### Wordle Solver
[constraint satisfaction against information theory](https://github.com/vidit-16/WordleSolver) on the same board, benchmarked head to head on all 2,315 official answers. information gain loses 5 games where constraint search loses 22, and pays for it with 13x the time per game · [live](https://wordle--solver.streamlit.app/)

### Food Vision
[a ConvNeXt-Tiny food classifier](https://github.com/vidit-16/foodVision) fine-tuned on Food-101, served through FastAPI and packaged with Docker. changing the backbone and the training recipe took top-1 accuracy from 82.2% to 91.9% on the official test split

## Tools

**languages and data** Python · SQL · Pandas · NumPy · PostgreSQL · SQLite

**machine learning** PyTorch · timm · Scikit-learn · Hugging Face Transformers · sentence-transformers · FAISS · Computer Vision

**llm systems** OpenAI · Groq · retrieval-augmented generation · evaluation and benchmarking

**serving and ops** FastAPI · Streamlit · Docker · Git · GitHub Actions · pytest

[LinkedIn](https://www.linkedin.com/in/vidit-choudhary-514a98227/) · [Email](mailto:choudharyvidit5@gmail.com)
