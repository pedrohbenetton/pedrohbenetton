<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=160&section=header&text=Pedro%20Benetton&fontSize=42&fontColor=ffffff&desc=IA%20generativa%20%C2%B7%20LLMs%20%C2%B7%20ci%C3%AAncia%20de%20dados&descAlignY=72" width="100%" alt="Pedro Benetton">

<p>
  <a href="https://www.linkedin.com/in/pedrohbenetton/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.kaggle.com/pedrohbenetton"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white" alt="Kaggle"></a>
  <a href="https://huggingface.co/pedrohbenetton"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="mailto:pedrohcomisso@gmail.com"><img src="https://img.shields.io/badge/E--mail-D14836?style=flat&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

Oi! Estudo Ciência da Computação na UFSCar Sorocaba (6º semestre, formatura em 2028). Trabalho com LLMs: fine-tuning, RAG e, principalmente, avaliação. Gosto de projetos em que dá para medir se a ideia funcionou.

- 🔬 Iniciação científica em sistemas de recomendação na UFSCar
- 🧪 Mais de 1 ano avaliando e alinhando LLMs (RLHF, detecção de alucinações)
- 🚀 Co-fundador técnico de uma startup B2B incubada no UFSCar Labs
- 🌎 Português nativo, inglês C1, espanhol B2

## Projetos

### [pedido-extractor-ptbr](https://github.com/pedrohbenetton/pedido-extractor-ptbr)
Fine-tuning QLoRA de um Qwen2.5-1.5B para transformar mensagens de pedido de delivery, escritas do jeito que as pessoas escrevem ("2 pizzas de calabresa sem cebola, ah não, 3. pago no pix"), em JSON validado. Num conjunto de teste difícil escrito à mão, o modelo acerta o pedido inteiro em **90%** dos casos; o modelo base acerta 3% e o Claude Haiku sem ajuste, 68%. O adapter está publicado no [Hugging Face](https://huggingface.co/pedrohbenetton/pedido-extractor-ptbr-lora).

### [kaggle-llm-preference](https://github.com/pedrohbenetton/kaggle-llm-preference)
O que faz uma pessoa preferir a resposta de um chatbot à de outro? Com 57 mil comparações da Chatbot Arena e um modelo de Bradley-Terry com controle de estilo feito do zero: a resposta mais longa tende a vencer mesmo quando os dois modelos são os mesmos, e recusar responder custa caro. Próximo passo: treinar um reward model com LoRA e ver se ele herda esses vieses.

<img src="https://raw.githubusercontent.com/pedrohbenetton/kaggle-llm-preference/master/results/figures/length_winrate.png" width="600" alt="Taxa de vitória da resposta A em função da razão entre os tamanhos das respostas">

### [production-grade-hybrid-RAG](https://github.com/pedrohbenetton/production-grade-hybrid-RAG)
RAG com busca híbrida (BM25 + busca densa + fusão RRF + reranker), avaliado nos benchmarks SciFact e NFCorpus, com uma checagem de que cada afirmação da resposta está apoiada nas fontes. FastAPI, Qdrant e 242 testes.

### [ptbr-llm-bench](https://github.com/pedrohbenetton/ptbr-llm-bench)
Benchmark pequeno de LLMs em português informal, com gírias, abreviações e erros de digitação: classificação de intenção, ambiguidade e extração. Roda modelos abertos (com ou sem LoRA) e a API da Anthropic com a mesma interface.

### [kaggle-name-that-llm](https://github.com/pedrohbenetton/kaggle-name-that-llm)
Dado um parágrafo, descobrir qual de 18 LLMs o escreveu. Validação agrupada por prompt, TF-IDF de estilo e embeddings do Qwen3. O README também conta o que não funcionou e por quê, incluindo um ganho de validação que não apareceu no leaderboard.

### Outros
- [agentic-pipeline-orchestrator](https://github.com/pedrohbenetton/agentic-pipeline-orchestrator): orquestração multiagente com fallback entre modelos, function calling e tracing com OpenTelemetry.
- [enterprise-ai-automation-suite](https://github.com/pedrohbenetton/enterprise-ai-automation-suite): workflows n8n com LLM para triagem de tickets e extração de faturas.
- [ufscar-ml-competition](https://github.com/pedrohbenetton/ufscar-ml-competition): ensembles de boosting calibrados, com relatório em formato IEEE.
- [nexto](https://github.com/pedrohbenetton/nexto): PWA de transporte público em tempo real.

## Ferramentas

<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,postgres,fastapi,docker,git,linux,githubactions,ts,nodejs&theme=dark" alt="Python, PyTorch, scikit-learn, PostgreSQL, FastAPI, Docker, Git, Linux, GitHub Actions, TypeScript, Node.js">

**IA e dados:** Hugging Face (transformers, PEFT), LoRA/QLoRA, RAG, avaliação de LLMs, Qdrant, scikit-learn, LightGBM, pandas, NumPy, Matplotlib
**Engenharia:** FastAPI, Pydantic, PostgreSQL, Docker, GitHub Actions, pytest, ruff, mypy
**Outros:** n8n, Streamlit, TypeScript, C, C++, Java

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=90&section=footer" width="100%" alt="">
