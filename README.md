## Oi, sou o Pedro

Estudo Ciência da Computação na UFSCar Sorocaba (6º semestre). Faço iniciação científica em sistemas de recomendação, sou co-fundador técnico de uma startup incubada no UFSCar Labs e, como freelancer, avalio respostas de LLMs para treinamento com RLHF. Gosto de projetos com LLMs em que dá para medir se funcionou.

### Projetos

**[pedido-extractor-ptbr](https://github.com/pedrohbenetton/pedido-extractor-ptbr)**: fine-tuning QLoRA de um Qwen2.5-1.5B para transformar pedidos de delivery escritos de qualquer jeito em JSON. Num conjunto de teste difícil, acerta 90% dos pedidos inteiros, contra 68% do Claude Haiku sem ajuste. O adapter está no [Hugging Face](https://huggingface.co/pedrohbenetton/pedido-extractor-ptbr-lora).

**[kaggle-llm-preference](https://github.com/pedrohbenetton/kaggle-llm-preference)**: o que faz uma pessoa preferir a resposta de um chatbot à de outro, com 57 mil comparações da Chatbot Arena. A mais longa tende a vencer, mesmo comparando o mesmo par de modelos:

<img src="https://raw.githubusercontent.com/pedrohbenetton/kaggle-llm-preference/master/results/figures/length_winrate.png" width="560" alt="Taxa de vitória da resposta A em função da razão entre os tamanhos das respostas">

**[production-grade-hybrid-RAG](https://github.com/pedrohbenetton/production-grade-hybrid-RAG)**: RAG com busca híbrida (BM25 + densa + reranker), avaliado nos benchmarks SciFact e NFCorpus, com checagem de que cada afirmação da resposta está nas fontes.

**[ptbr-llm-bench](https://github.com/pedrohbenetton/ptbr-llm-bench)**: benchmark pequeno de LLMs em português informal, com gírias, abreviações e erros de digitação.

**[kaggle-name-that-llm](https://github.com/pedrohbenetton/kaggle-name-that-llm)**: descobrir qual de 18 LLMs escreveu um texto. O README conta também o que não funcionou e por quê.

Outros: [agentic-pipeline-orchestrator](https://github.com/pedrohbenetton/agentic-pipeline-orchestrator), [enterprise-ai-automation-suite](https://github.com/pedrohbenetton/enterprise-ai-automation-suite), [ufscar-ml-competition](https://github.com/pedrohbenetton/ufscar-ml-competition), [nexto](https://github.com/pedrohbenetton/nexto).

### Ferramentas

Python, PyTorch, Hugging Face (transformers, PEFT), scikit-learn, pandas, SQL/PostgreSQL, FastAPI, Docker, Git.

### Contato

[LinkedIn](https://www.linkedin.com/in/pedrohbenetton/) · [Kaggle](https://www.kaggle.com/pedrohbenetton) · [Hugging Face](https://huggingface.co/pedrohbenetton) · pedrohcomisso@gmail.com
