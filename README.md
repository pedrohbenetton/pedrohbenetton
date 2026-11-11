# Oi, eu sou o Pedro Benetton 👋

Estudante de Ciência da Computação na **UFSCar Sorocaba** (6º semestre, formatura em jul/2028).
Construo sistemas com LLMs que são **medidos, testados e documentados**, não só demos.

- 🔬 Iniciação científica em **Sistemas de Recomendação** (Prof. Dr. Tiago Almeida)
- 🧪 +1 ano avaliando e alinhando LLMs (RLHF, detecção de alucinações)
- 🚀 Co-fundador técnico de uma startup B2B incubada no UFSCar Labs
- 🌎 Inglês C1 · Espanhol B2

## IA generativa

| Projeto | O que mostra |
|---|---|
| [**pedido-extractor-ptbr**](https://github.com/pedrohbenetton/pedido-extractor-ptbr) | Fine-tuning QLoRA de um Qwen2.5-1.5B para transformar pedidos de delivery em PT-BR em JSON validado. **90% de exact match** num conjunto difícil escrito à mão (modelo base: 3,3%; Claude Haiku zero-shot: 68,3%). Adapter no [Hugging Face](https://huggingface.co/pedrohbenetton/pedido-extractor-ptbr-lora). |
| [**production-grade-hybrid-RAG**](https://github.com/pedrohbenetton/production-grade-hybrid-RAG) | RAG híbrido (BM25 + denso + RRF + reranker) avaliado em BEIR (SciFact e NFCorpus), com checagem de fidelidade por afirmação. 242 testes, 93% de cobertura, `mypy --strict`. |
| [**ptbr-llm-bench**](https://github.com/pedrohbenetton/ptbr-llm-bench) | Benchmark de LLMs em PT-BR informal (gírias, abreviações, erros de digitação): intenção, ambiguidade e extração. Roda modelos abertos com LoRA e a API da Anthropic. |
| [**agentic-pipeline-orchestrator**](https://github.com/pedrohbenetton/agentic-pipeline-orchestrator) | Orquestração multiagente com cadeia de fallback entre modelos, function calling, tracing OpenTelemetry e evals de LLM no CI. |

## Kaggle

| Projeto | O que mostra |
|---|---|
| [**kaggle-llm-preference**](https://github.com/pedrohbenetton/kaggle-llm-preference) | Que vieses os humanos têm ao escolher entre dois chatbots (Chatbot Arena, 57 mil batalhas)? Bradley-Terry com controle de estilo feito do zero: cada desvio-padrão a mais de tamanho aumenta as **odds de vitória em 44%**, mesmo controlando pelo modelo; recusar reduz as odds em 27%. |
| [**kaggle-name-that-llm**](https://github.com/pedrohbenetton/kaggle-name-that-llm) | Qual de 18 LLMs escreveu este parágrafo? Validação agrupada por prompt, TF-IDF de estilo, embeddings do Qwen3 e uma análise honesta de por que um ganho de validação não transferiu para o leaderboard. |

## Outros projetos

- [**enterprise-ai-automation-suite**](https://github.com/pedrohbenetton/enterprise-ai-automation-suite): workflows n8n com LLM (triagem de tickets, extração de faturas), com validação de schema e fallback em 3 níveis.
- [**ufscar-ml-competition**](https://github.com/pedrohbenetton/ufscar-ml-competition): ensembles de boosting calibrados e relatório em formato IEEE.
- [**nexto**](https://github.com/pedrohbenetton/nexto): PWA de transporte público em tempo real, com decodificação de Protocol Buffers.

## Stack

**IA/ML:** Python · PyTorch · Hugging Face (transformers, PEFT) · LoRA/QLoRA · RAG · LLM evals · scikit-learn · LightGBM · pandas/NumPy
**Engenharia:** FastAPI · Pydantic · PostgreSQL · Docker · GitHub Actions · pytest · mypy/ruff
**Automação:** n8n · Streamlit · TypeScript/Node

## Como eu trabalho

Spec primeiro, testes antes do código, métricas antes de opinião. Se não dá para medir, não afirmo que melhorou, e quando algo não funciona, o README diz por quê.

[Hugging Face](https://huggingface.co/pedrohbenetton) · [Kaggle](https://www.kaggle.com/pedrohbenetton) · 📫 pedrohcomisso@gmail.com
