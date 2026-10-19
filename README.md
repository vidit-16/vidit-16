## About

i've built systems that engineer guardrails around llm-driven financial decisions, run voice agents that people talk to in their own language, prove when a document existed, and trace business metrics back to their drivers.

right now i'm a software engineer intern (mlops) at pulseforge labs, serving retinal-screening models to clinics in production. outside of that, i'm a final-year ai and robotics student at bangalore institute of technology.

i like interesting problems, going down rabbit holes, and figuring out how to turn an idea into something that actually works.

sometimes that means building the obvious solution.

sometimes it means wondering if there's a completely different way to do it.

either way, i'm usually building something.

**try them live:** [Saakshi](https://d5gpae5oilzws.cloudfront.net) · [Mohar](https://mohar-in.vercel.app) · [DocEngine](https://doc--engine.streamlit.app/) · [ClassFind](https://classfind-prod.eba-ttyqcasp.ap-south-1.elasticbeanstalk.com/)

## Projects

### Saakshi
[pays farmers not to burn crop stubble, then checks every field by satellite](https://github.com/vidit-16/saakshi). farmers talk to it on whatsapp or the web, by text or voice, in punjabi, hindi, haryanvi or english, and a bedrock agent picks one of seven tools, none of which can approve or pay. fixed rules make every decision and keep the evidence. on 615 hand-labelled fields it wrongly flags 1.6% of clean fields, against 8.7% for nasa's fire alerts, and property tests catch all 27 bugs planted in the rules and payments · [live](https://d5gpae5oilzws.cloudfront.net)

### Mohar
[prove who had the exam paper before the exam](https://github.com/vidit-16/mohar). exam bodies seal salted hashes of every question on arkiv before the exam, anyone can prove a leak came first, and anyone can check it without us, in english and hindi. 95 unit tests, 14 checks on the live chain and 78 browser tests with an accessibility audit, and mutation testing catches 98.1% of bugs planted in the verdict logic. the verifier is on npm as `mohar-verify` · [live](https://mohar-in.vercel.app)

### BaseDrift
[a pre-authorization decision layer for outbound payments](https://github.com/vidit-16/BaseDrift) combines deterministic policy rules with an LLM semantic layer, with a focus on authorization provenance, fail-safe handling, auditability, and adversarial testing. every one of the 15 mutations of its stated invariants is caught by the suite, so the rules cannot be quietly weakened

### RootSignal
[root-cause analytics for sales and supply operations](https://github.com/vidit-16/RootSignal) traces metric movements to the segments behind them, separates performance changes from mix effects, estimates business impact, and produces evidence-backed investigation signals. the same pipeline runs unchanged on 1M+ real invoice lines from a uk retailer, which broke three things generated data never could, and the same forecast model wins on both — beating a naive baseline by 38.8% on the real data. that data now moves from s3 through a pyspark job into postgresql and redshift, with spark's output matching the pandas version on every one of the million rows, and a power bi report on top

### PayFloor
[an affordability engine for financial requests](https://github.com/vidit-16/PayFloor) decides whether to pay now, in parts, in instalments, later, or not at all. the model only extracts facts; deterministic code makes the call and guarantees the balance never drops below the user's minimum over 90 days. built at hackerrank orchestrate, where it won a silver medal

### DocEngine
[question answering over PDFs](https://github.com/vidit-16/DocEngine) with page-cited sources. every retrieval choice is settled by measurement against a labelled question set with a held-out split rather than by preference, which took correct answers from 75.0% to 86.8% · [live](https://doc--engine.streamlit.app/)

### ClassFind
[a campus lost-and-found board](https://github.com/vidit-16/ClassFind) where students report what they lost or found, by text or voice, search, and claim items, with each lost report scored against found ones and the reasons for every match shown. items are handed over at the security desk with one-time collection codes. flask and sqlalchemy on elastic beanstalk, postgres on rds, and images in s3 behind presigned urls, with 124 tests in ci · [live](https://classfind-prod.eba-ttyqcasp.ap-south-1.elasticbeanstalk.com/)

## Open source

**[Parsec](https://github.com/daseinlabs/parsec)** · property tests against the python reference on 400k inputs found and fixed 4 bugs in the rust runtime

**[Tin](https://github.com/tin-computer/tin)** · added a marketing workflow that finds which app marketplaces a product should be listed on

**[Arkiv](https://github.com/Arkiv-Network/arkiv-sdk-js)** · reported 4 bugs and 4 feature ideas to arkiv's sdk and network while building mohar

## Tools

**languages** Python · TypeScript · JavaScript · SQL

**llm systems** OpenAI · Anthropic · Amazon Bedrock · Gemini · Groq · MCP · tool calling · RAG · evaluation and benchmarking

**backend and web** FastAPI · Flask · SQLAlchemy · React · Vite · Redis · PostgreSQL · DynamoDB

**data and ml** Pandas · NumPy · PySpark · Power BI · PyTorch · Scikit-learn · sentence-transformers · FAISS

**cloud and ops** AWS (EC2 · Lambda · S3 · RDS · Redshift · Elastic Beanstalk) · Docker · Vercel · Git · GitHub Actions · pytest · Playwright

[LinkedIn](https://www.linkedin.com/in/vidit-choudhary) · [HackerRank](https://www.hackerrank.com/choudharyvidit5) · [Email](mailto:choudharyvidit5@gmail.com)
