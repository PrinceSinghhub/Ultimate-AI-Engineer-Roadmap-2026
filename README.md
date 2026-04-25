# Ultimate AI Engineer Roadmap 2026 🔥
### From Zero to Production-Grade AI Systems

**Ultimate AI Engineer Roadmap 2026** - built specifically for your context as an AI Architect building PrinceSinghAI, PrinceSinghDev, Multi-LLM orchestration, RoadmapAI, CodeLLM, and AskAI, Global AI Search

## 🎥 Watch Complete Video

[![Watch the video](https://img.youtube.com/vi/7Gxu-VCPJ0A/maxresdefault.jpg)](https://www.youtube.com/watch?v=7Gxu-VCPJ0A)

**What's inside (17 Phases + Capstone):**

The roadmap starts from absolute zero and goes all the way to production-grade AI architecture. Here's the breakdown:

- **Phase 0** - Mindset: AI Engineer vs ML Engineer, market demand 2026
- **Phase 1** - Python (including async/await for AI APIs - most roadmaps miss this)
- **Phase 2** - Math & Stats (linear algebra, calculus, probability, optimization)
- **Phase 3** - Machine Learning Fundamentals (foundation for understanding LLMs)
- **Phase 4** - Deep Learning (foundation for understanding LLMs)
- **Phase 5** - NLP & Transformers (architecture deep dive)
- **Phase 6** - LLM Engineering (ALL major APIs: OpenAI, Claude, Gemini, Mistral, Groq, NVIDIA)
- **Phase 7** - **Multi-LLM Orchestration** (your specialty - routing, fallbacks, MCP, LangGraph, LangChain, CrewAI, AutoGen)
- **Phase 8** - RAG & Vector Databases (advanced techniques: HyDE, reranking, hybrid search)
- **Phase 9** - AI Agents & Agentic Systems (AskAI framework)
- **Phase 10** - Fine-tuning (LoRA, QLoRA, DPO, RLHF)
- **Phase 11** - Generative AI (diffusion, multimodal, voice, video)
- **Phase 12** - MLOps & LLMOps (production, monitoring, Kubernetes, CI/CD)
- **Phase 13** - AI System Design (interview-ready + real architecture patterns)
- **Phase 14** - SQL + pgvector for AI
- **Phase 15** - Quantization & Optimization (vLLM, GGUF, SLMs)
- **Phase 16** - Reinforcement Learning (RLHF, DPO, PPO)
- **Phase 17** - AI Ethics, Safety & Governance

Every phase has **3 projects** 
- Easy 🟢
- Medium 🟡
- Hard 🔴) 

51 projects total. The capstone is the full 


multi-LLM platform architecture.

---

## 📌 How to Use This Roadmap

```
FRESHER  → Follow Phase 1 → 2 → 3 → 4 (foundation-first approach)
MID-LEVEL → Start Phase 3, revisit Phase 1-2 gaps
EXPERT   → Phase 5 → 6 → 7 → 8 (advanced systems & architecture)
```

Each phase ends with **Project-Based Learning**:
- 🟢 **Easy** - Build confidence, reinforce fundamentals
- 🟡 **Medium** - Real-world patterns, production thinking
- 🔴 **Hard** - Production-grade, multi-system, scalable

---

## 🗺️ PHASE 0 - Mindset & Orientation

### What is an AI Engineer (2026)?

An AI Engineer is **not** a data scientist or ML researcher. You are the bridge between powerful AI models and real-world products. You:

- Integrate, orchestrate, and deploy AI models into production systems
- Design multi-LLM pipelines with routing, fallback, and cost optimization
- Build RAG systems, AI agents, and agentic workflows
- Know when to use OpenAI vs Claude vs Gemini vs Mistral vs open-source
- Ship reliable, secure, scalable AI-powered software

### AI Engineer vs ML Engineer

| AI Engineer | ML Engineer |
|---|---|
| Uses pre-trained models via APIs | Trains models from scratch |
| API integration, prompt engineering | Data pipelines, model evaluation |
| Faster time to market | Expensive, research-heavy |
| Product + dev expertise | Deep ML/math expertise |
| **You are this** | Data science role |

### Market Demand 2026

Skills companies are actively hiring for:
- Multi-LLM orchestration (OpenAI + Claude + Gemini routing)
- RAG architecture & vector databases
- AI Agents & agentic systems
- LLMOps & production monitoring
- Prompt engineering at scale
- Fine-tuning & PEFT methods
- MCP (Model Context Protocol)
- Multimodal AI systems
- Cost optimization & inference efficiency

---

## 🗺️ PHASE 1 - Programming Foundation

> **Goal:** Write clean, production-quality Python. This is non-negotiable.

### 1.1 Python Fundamentals

**Data Types & Variables**
- Integers, floats, strings, booleans, None
- Type conversion: `int()`, `float()`, `str()`, `bool()`
- `type()` and `isinstance()`
- Mutable vs immutable types - critical for AI pipelines

**Strings**
- String slicing: `s[start:stop:step]`
- Methods: `split`, `join`, `strip`, `replace`, `find`, `startswith`, `endswith`
- f-strings: `f"value is {x:.2f}"`
- Multiline strings with triple quotes

**Collections**
- Lists - indexing, slicing, `append`, `extend`, `pop`, `sort`, `reverse`
- Tuples - immutability and when to prefer over lists
- Dictionaries - CRUD, `.keys()`, `.values()`, `.items()`, `.get()`
- Sets - uniqueness, union, intersection, difference
- Nested collections - list of dicts, dict of lists

**Control Flow**
- `if / elif / else`
- `for` loops - iterating over lists, dicts, ranges
- `while` loops and `break / continue`
- `range()`, `enumerate()`, `zip()`

### 1.2 Functions

- Defining functions with `def`
- Positional vs keyword arguments
- Default argument values
- `*args` and `**kwargs` - used constantly in AI SDKs
- Return values, tuple unpacking
- Lambda functions
- Recursion
- Docstrings

### 1.3 Object-Oriented Programming

- Classes and instances
- `__init__` constructor
- Instance methods and `self`
- Class vs instance variables
- Inheritance and `super()`
- Overriding methods
- `__repr__`, `__str__`, `__len__`, `__getitem__`
- `@property`, `@staticmethod`, `@classmethod`
- Abstract classes with `ABC` - used heavily in LangChain, LlamaIndex

### 1.4 Pythonic Code & Idioms

- List, dict, set comprehensions
- Generator expressions - memory efficient for large datasets
- `map()`, `filter()`, `reduce()`
- Unpacking: `a, b, *rest = lst`
- `any()`, `all()`, `sorted()` with `key=`
- `collections` module: `Counter`, `defaultdict`, `deque`

### 1.5 File I/O & Data Handling

- Reading/writing text files with `open()` and context managers
- Reading CSVs with `csv` module
- Reading/writing JSON: `json.load()`, `json.dump()`
- Pickle: `pickle.dump()`, `pickle.load()`
- `os` module: path joining, listing dirs, making dirs
- `pathlib.Path` - modern file path handling
- `glob` - pattern matching files (useful for batch processing)

### 1.6 Error Handling & Debugging

- `try / except / finally`
- Catching specific exceptions
- Raising exceptions: `raise ValueError("message")`
- Custom exception classes
- `logging` module - DEBUG, INFO, WARNING, ERROR
- `pdb` and `breakpoint()`
- Reading tracebacks

### 1.7 Performance & Memory

- Generators and `yield` - critical for streaming AI responses
- `itertools` module
- `timeit` and `cProfile` for benchmarking
- Shallow vs deep copy
- Vectorization preference over Python loops

### 1.8 NumPy (Non-Negotiable for AI)

- Array creation: `np.array()`, `np.zeros()`, `np.ones()`, `np.eye()`
- Array shape, ndim, dtype
- Reshaping: `reshape()`, `flatten()`, `ravel()`
- Stacking: `np.stack()`, `np.hstack()`, `np.vstack()`
- Boolean indexing, `np.where()`
- Broadcasting rules
- `np.dot()` and `@` operator
- Matrix operations: `np.linalg.inv()`, `np.linalg.eig()`
- Aggregations with `axis=` argument
- `np.random` module

### 1.9 Pandas (Essential for Data Work)

- DataFrames & Series creation
- `df.head()`, `df.info()`, `df.describe()`, `df.shape`
- `loc` vs `iloc` indexing
- Boolean filtering
- Handling missing values: `isna()`, `dropna()`, `fillna()`
- `groupby()`, `agg()`, `pivot_table()`, `value_counts()`
- `merge()`, `concat()`, `melt()`, `pivot()`
- Parsing dates: `pd.to_datetime()`

### 1.10 Code Quality & Project Structure

- Virtual environments: `venv` or `conda`
- `requirements.txt` and `pip freeze`
- Writing modular code - splitting into files and modules
- `__init__.py` - making a folder a package
- Type hints: `def fn(x: int) -> str:`
- `dataclasses` - cleaner data containers
- Unit tests with `pytest`
- Linting with `ruff` or `flake8`, formatting with `black`

### 1.11 Python for AI Workflows

- Jupyter notebooks - cells, magic commands
- Google Colab - GPU access
- `tqdm` - progress bars for training loops
- `argparse` - CLI arguments for scripts
- `hydra` or `yaml` configs - managing experiment configs
- `dotenv` - managing API keys (CRITICAL for AI projects)
- Seeding for reproducibility: `random`, `numpy`, `torch`
- Saving/loading models: `pickle`, `joblib`, `torch.save()`

### 1.12 Async Python (Critical for AI APIs)

- `async/await` syntax
- `asyncio` event loop
- `aiohttp` - async HTTP calls to AI APIs
- Concurrent API calls with `asyncio.gather()`
- `httpx` - async-first HTTP client used in production AI apps
- Understanding why streaming LLM responses need async

---

### 📦 Phase 1 Projects

**🟢 Easy: Python AI Toolkit CLI**
- Build a CLI tool that accepts text input and calls the OpenAI API
- Features: summarize, translate, sentiment analysis
- Stack: Python, `argparse`, `openai` SDK, `.env`

**🟡 Medium: Async Multi-API Caller**
- Call OpenAI + Anthropic + Gemini simultaneously with `asyncio.gather()`
- Compare responses side by side
- Add error handling, retries with exponential backoff
- Stack: Python, `httpx`, `asyncio`, `rich` for terminal display

**🔴 Hard: Production-Grade Data Pipeline**
- Build a pipeline that reads CSVs, cleans data, chunks into batches, and sends to an embedding API
- Features: progress bars, error recovery, resume from checkpoint, async batching
- Stack: Python, Pandas, NumPy, `tqdm`, `asyncio`, OpenAI Embeddings API

---

## 🗺️ PHASE 2 - Mathematics & Statistics for AI

> **Goal:** Understand the math behind what models do - you don't need to derive everything, but you must understand it.

### 2.1 Linear Algebra

**Vectors**
- What a vector is - geometrically and algebraically
- Vector addition, scalar multiplication
- Dot product - geometric intuition (similarity, projection)
- Vector magnitude / norm (`L1`, `L2`, `Lp` norms)
- Unit vectors and normalization
- Cosine similarity - how embeddings work
- Orthogonality

**Matrices**
- Matrix operations: addition, multiplication, transpose
- Element-wise vs matrix product
- Identity matrix, inverse matrix
- Determinant - geometric intuition
- Rank of a matrix

**Matrix Operations in ML Context**
- Linear transformations
- Systems of linear equations: `Ax = b`
- Overdetermined systems and least squares
- Trace of a matrix

**Decompositions**
- Eigenvalues and eigenvectors
- Why eigenvalues matter in PCA
- Singular Value Decomposition (SVD) - high-level intuition
- How SVD relates to dimensionality reduction

### 2.2 Calculus

**Derivatives**
- What a derivative is - rate of change, slope
- Power rule, chain rule, product rule
- Derivative of `log`, `exp`, `sigmoid`
- Minima, maxima, saddle points
- Second derivative - concavity, convexity

**Partial Derivatives & Multivariable**
- Partial derivative - rate of change w.r.t. one variable
- Gradient - vector of all partial derivatives
- Gradient points uphill - minimizing means going opposite
- Jacobian matrix
- Hessian matrix

**Chain Rule (Critical for ML)**
- Chain rule for single variable
- Chain rule for multivariable - how backpropagation works
- Computational graphs - forward and backward pass

**Key Functions to Differentiate**
- Sigmoid: `σ(x) = 1/(1+e^-x)` and its derivative
- ReLU and its derivative
- Softmax gradient
- Cross-entropy loss gradient
- MSE loss gradient

### 2.3 Probability & Statistics

**Probability Basics**
- Sample space, events, outcomes
- Joint, marginal, conditional probability
- Independence
- Law of total probability

**Bayes' Theorem**
- Formula: `P(A|B) = P(B|A) * P(A) / P(B)`
- Prior, likelihood, posterior
- Bayesian updating
- Naive Bayes as direct application

**Random Variables & Distributions**
- Discrete vs continuous random variables
- PMF, PDF, CDF
- Expected value, variance, standard deviation
- Covariance and correlation

**Key Distributions**
- Bernoulli, Binomial, Gaussian (Normal), Uniform
- Poisson, Exponential, Multinomial (used in NLP)

**Statistical Concepts**
- Central Limit Theorem
- Law of Large Numbers
- MLE (Maximum Likelihood Estimation)
- MAP (Maximum A Posteriori)
- Entropy, KL Divergence, Cross-entropy

### 2.4 Optimization

**Core Concepts**
- Objective / loss function
- Convex vs non-convex functions
- Local minima vs global minima vs saddle points
- Constrained vs unconstrained optimization

**Gradient Descent**
- Intuition - ball rolling downhill
- Update rule: `θ = θ - α * ∇L(θ)`
- Learning rate - too high vs too low
- Batch GD vs SGD vs Mini-batch

**Optimizers**
- Momentum
- RMSProp
- Adam - combines momentum + RMSProp (most common)
- Learning rate schedules: step decay, cosine annealing, warmup

**Key Challenges**
- Vanishing gradients
- Exploding gradients + gradient clipping
- Saddle points in high dimensions
- Plateau regions

**Regularization**
- L2 regularization (weight decay)
- L1 regularization - promotes sparsity
- Dropout
- Early stopping

### 2.5 Information Theory

- Entropy `H(X) = -Σ p(x) log p(x)`
- Cross-entropy loss - natural loss for classification
- KL Divergence - used in VAEs, distillation, RL
- Mutual information
- Bits vs nats

---

### 📦 Phase 2 Projects

**🟢 Easy: Cosine Similarity Search**
- Implement cosine similarity from scratch using NumPy
- Build a mini semantic search: given a query, find the most similar sentences
- Visualize vector space with matplotlib

**🟡 Medium: Gradient Descent Visualizer**
- Implement gradient descent from scratch for linear regression and logistic regression
- Visualize loss curves, decision boundaries
- Compare SGD vs Adam vs RMSProp convergence
- Stack: Python, NumPy, Matplotlib

**🔴 Hard: Build Your Own Neural Network from Scratch**
- Implement forward pass, backward pass (backprop), weight updates
- Support: Linear, ReLU, Sigmoid, Softmax layers
- Train on MNIST, achieve >95% accuracy
- No PyTorch/TensorFlow - pure NumPy
- Stack: Python, NumPy, Matplotlib

---

## 🗺️ PHASE 3 - Machine Learning Fundamentals

> **Goal:** Understand the classic ML algorithms that power AI feature engineering and evaluation.

### 3.1 Core ML Concepts

- Supervised vs Unsupervised vs Reinforcement Learning
- Training set, validation set, test set
- Overfitting and underfitting
- Bias-variance tradeoff
- Cross-validation (k-fold)
- Evaluation metrics: Accuracy, Precision, Recall, F1, AUC-ROC

### 3.2 Linear & Logistic Regression

- Linear regression - closed form and gradient descent
- Logistic regression - sigmoid output, binary classification
- Cost functions: MSE, Binary Cross-Entropy
- Regularization: Ridge (L2), Lasso (L1)
- Multi-class classification: One-vs-Rest

### 3.3 Decision Trees & Ensembles

- Decision trees - splitting criteria (Gini, entropy)
- Random forests - bagging of decision trees
- Gradient boosting - XGBoost, LightGBM (used in ML features)
- Feature importance

### 3.4 Unsupervised Learning

- K-Means clustering
- DBSCAN
- PCA - dimensionality reduction (connects to embeddings)
- t-SNE / UMAP - visualization of high-dimensional data (embedding visualization)

### 3.5 Hyperparameter Tuning

- Grid search, random search
- Bayesian optimization
- Learning rate, batch size, epochs, layers
- Early stopping

### 3.6 ML with Scikit-Learn

- Pipelines: `Pipeline()` class
- Preprocessors: `StandardScaler`, `MinMaxScaler`, `OneHotEncoder`
- Model selection: `GridSearchCV`, `cross_val_score`
- Saving models: `joblib`
- Understanding the sklearn API pattern (fit/transform/predict)

---

### 📦 Phase 3 Projects

**🟢 Easy: Spam Classifier**
- Build a spam/not-spam email classifier with TF-IDF + Logistic Regression
- Evaluate with precision, recall, F1
- Stack: Scikit-learn, Pandas, NLTK

**🟡 Medium: Customer Churn Prediction System**
- Full pipeline: data cleaning → feature engineering → model training → evaluation
- Try Logistic Regression vs Random Forest vs XGBoost
- Add SHAP for explainability
- Stack: Scikit-learn, XGBoost, SHAP, Pandas, Matplotlib

**🔴 Hard: AutoML Mini-Framework**
- Build a framework that automatically tries multiple models and hyperparameters
- Generate a full evaluation report
- Add feature importance, confusion matrix, ROC curve
- Stack: Scikit-learn, Optuna (Bayesian optimization), Pandas, Matplotlib

---

## 🗺️ PHASE 4 - Deep Learning

> **Goal:** Understand neural networks deeply enough to work with transformers.

### 4.1 Neural Network Fundamentals

- Neuron, Perceptron, MLP
- Activation functions: Sigmoid, Tanh, ReLU, GELU, SwiGLU
- Forward pass - how information flows
- Backpropagation - how gradients flow backward
- Weight initialization strategies
- Vanishing / exploding gradient problem

### 4.2 Training Techniques

- Batch normalization - stabilizing training
- Layer normalization - used in transformers
- Dropout - stochastic regularization
- Residual connections (skip connections) - used in every modern model
- Gradient clipping

### 4.3 Convolutional Neural Networks (CNN)

- Convolution operation - feature detection
- Pooling layers - spatial downsampling
- CNN architectures: LeNet, AlexNet, VGG, ResNet
- Transfer learning with CNNs
- Applications: image classification, object detection

### 4.4 Recurrent Neural Networks (RNN)

- RNN - processing sequences one step at a time
- Hidden state - memory across time steps
- Vanishing gradient in RNNs
- LSTM - cell state, forget/input/output gates
- GRU - simpler LSTM alternative
- Bidirectional RNNs
- Seq2Seq: encoder + decoder
- Beam search decoding

### 4.5 Attention Mechanism (Pre-Transformer)

- Attention as "soft" alignment
- Additive vs multiplicative attention
- Bahdanau attention for seq2seq
- Why attention solved the bottleneck problem

### 4.6 PyTorch (Master This)

- Tensors - creation, operations, GPU
- `torch.nn.Module` - building models
- `torch.optim` - Adam, SGD, etc.
- Custom datasets with `torch.utils.data.Dataset`
- DataLoader - batching and shuffling
- Training loop: forward → loss → backward → step
- `model.eval()` vs `model.train()`
- Saving/loading: `torch.save()`, `torch.load()`
- Moving to GPU: `.to(device)`
- Gradient computation: `.requires_grad`, `torch.no_grad()`
- Custom loss functions
- Learning rate schedulers

### 4.7 Transfer Learning

- What is pretraining and why it matters
- Fine-tuning vs feature extraction
- Freezing layers
- ImageNet moment for NLP
- Using HuggingFace pretrained models

---

### 📦 Phase 4 Projects

**🟢 Easy: Image Classifier with Transfer Learning**
- Fine-tune ResNet-18 on a custom image dataset (5 categories)
- Track train/val accuracy, plot loss curves
- Stack: PyTorch, torchvision, Matplotlib

**🟡 Medium: Sentiment Analysis with LSTM vs BERT**
- Build LSTM from scratch, then use pretrained BERT
- Compare performance on movie reviews dataset
- Stack: PyTorch, HuggingFace Transformers

**🔴 Hard: Build a Mini GPT from Scratch**
- Implement the full transformer architecture: attention, multi-head attention, positional encoding, feed-forward, residual connections
- Train on a small text corpus (Shakespeare/wiki)
- Stack: PyTorch, NumPy (follow Andrej Karpathy's nanoGPT style)

---

## 🗺️ PHASE 5 - Natural Language Processing & Transformers

> **Goal:** Deep NLP expertise for LLM-powered products.

### 5.1 Text Preprocessing

- Tokenization - words, subwords, characters
- Lowercasing, punctuation removal, whitespace normalization
- Stopword removal - when to and when not to
- Stemming vs Lemmatization
- Sentence segmentation
- Handling special tokens: URLs, emails, hashtags
- Unicode and encoding issues (`utf-8`)

### 5.2 Classical Text Representation

- Bag of Words (BoW)
- TF-IDF - formula and intuition
- N-grams - capturing context
- One-hot encoding - and why it fails at scale
- Sparse vs dense representations

### 5.3 Word Embeddings

- Why embeddings - dense, semantic vectors
- Word2Vec - CBOW vs Skip-gram
- GloVe - global co-occurrence statistics
- FastText - subword embeddings, handles OOV
- Cosine similarity on embeddings
- Analogy tasks: `king - man + woman = queen`
- Static vs contextual embeddings

### 5.4 Subword Tokenization (Modern)

- Byte Pair Encoding (BPE) - used in GPT
- WordPiece - used in BERT
- SentencePiece - used in T5, LLaMA
- Special tokens: `[CLS]`, `[SEP]`, `[PAD]`, `[MASK]`, `<eos>`, `<bos>`
- Token IDs - how text maps to integers
- Vocabulary size tradeoffs

### 5.5 Transformer Architecture (Master This)

- Why transformers replaced RNNs - parallelism and long-range attention
- Self-attention - every token attending to every other
- Query, Key, Value (Q, K, V) - intuition and matrix formulation
- Attention score: `softmax(QKᵀ / √d_k) * V`
- Multi-head attention - attending to different aspects
- Positional encoding - injecting order
- Feed-forward sublayer
- Layer normalization and residual connections
- Encoder-only (BERT-style) - understanding tasks
- Decoder-only (GPT-style) - generation tasks
- Encoder-Decoder (T5-style) - seq2seq tasks
- Causal masking in decoders

### 5.6 Language Modeling

- `P(next token | previous tokens)`
- Autoregressive language modeling
- Masked language modeling (MLM)
- Perplexity - evaluating language models
- Temperature, Top-k, Top-p (nucleus) sampling
- Greedy vs sampling vs beam search

### 5.7 Key Pretrained Models

| Model | Type | Best For |
|---|---|---|
| BERT | Encoder-only | Classification, NER, QA |
| GPT-4 | Decoder-only | Generation, chat |
| Claude 3.5/4 | Decoder-only | Long context, safety |
| Gemini | Encoder-Decoder | Multimodal |
| T5 | Encoder-Decoder | Seq2seq tasks |
| LLaMA 3 | Decoder-only | Open-source fine-tuning |
| Mistral 7B | Decoder-only | Efficient inference |
| Qwen 2.5 | Decoder-only | Multilingual |

### 5.8 NLP Evaluation Metrics

- Accuracy, Precision, Recall, F1
- BLEU - machine translation
- ROUGE - summarization
- Perplexity - language models
- BERTScore - semantic similarity
- Human evaluation
- Exact Match (EM) - QA tasks

### 5.9 Key Python Libraries

- `NLTK` - classic NLP
- `spaCy` - production NLP: NER, parsing
- `transformers` (HuggingFace) - pretrained models
- `datasets` (HuggingFace) - loading datasets
- `sentence-transformers` - sentence embeddings
- `tiktoken` - OpenAI's tokenizer (BPE)
- `evaluate` - HuggingFace metrics

---

### 📦 Phase 5 Projects

**🟢 Easy: Named Entity Recognition (NER) Pipeline**
- Use spaCy to extract entities from news articles
- Build a simple web interface with Streamlit
- Stack: spaCy, Streamlit

**🟡 Medium: Semantic Search Engine**
- Embed 10,000 Wikipedia paragraphs with BERT
- Build a search interface that finds semantically similar passages
- Stack: HuggingFace, sentence-transformers, FAISS, Streamlit

**🔴 Hard: Fine-tune BERT for Multi-Label Classification**
- Fine-tune BERT on a multi-label text classification dataset
- Handle class imbalance, custom evaluation metrics
- Deploy as a REST API with FastAPI
- Stack: PyTorch, HuggingFace Transformers, FastAPI, Docker

---

## 🗺️ PHASE 6 - Large Language Models & AI Engineering

> **Goal:** This is your core domain. Master LLM fundamentals, APIs, and production patterns.

### 6.1 LLM Fundamentals

**Architecture Deep Dive**
- Transformer at scale - what changes going from 1B to 100B parameters
- Context window - how it works and limitations
- KV Cache - how it speeds up inference
- Tokenization at scale
- Positional encodings: Absolute, Relative, RoPE, ALiBi
- Flash Attention - memory-efficient attention
- Grouped Query Attention (GQA) - used in LLaMA 3
- Sliding window attention - used in Mistral

**Training LLMs**
- Pretraining - learning from internet-scale text
- Instruction tuning - following user instructions
- RLHF (Reinforcement Learning from Human Feedback)
- Constitutional AI (Anthropic's approach)
- DPO (Direct Preference Optimization) - alternative to RLHF
- Scaling laws - relationship between model size, data, compute

### 6.2 Prompt Engineering (Production-Grade)

**Prompt Anatomy**
- System prompt - role and constraints
- User prompt - the actual request
- Assistant turn - model's response history
- Few-shot examples in context

**Prompting Techniques**
- Zero-shot prompting
- One-shot and few-shot prompting
- Chain-of-Thought (CoT) - "think step by step"
- Self-consistency - generate multiple CoT paths, vote
- ReAct prompting - Reasoning + Acting (for agents)
- Tree of Thought (ToT)
- Structured output prompting - JSON, XML
- Role prompting - "You are a senior software engineer..."
- Prompt chaining - output of one prompt → input of next

**Production Prompt Engineering**
- Giving clear instruction + format + boundaries
- Always specifying what NOT to do
- Using examples and output constraints
- Prompt versioning and changelogs
- A/B testing prompts
- Prompt compression - reducing token count
- Prompt injection defense

**Tools**
- PromptLayer - tracking prompt versions
- LangSmith - LangChain observability
- OpenAI Playground
- Anthropic Console

### 6.3 Working with AI APIs

**OpenAI API**
- Chat Completions API - `messages` array
- Function calling / Tool use
- JSON mode / Structured outputs
- Streaming responses (SSE)
- Embeddings API
- Vision API (GPT-4V)
- Assistants API with file search
- Batch API for bulk processing
- Token counting with `tiktoken`
- Rate limits and quotas

**Anthropic (Claude) API**
- Messages API structure
- System prompts
- Long context (200K tokens)
- Vision support
- Tool use
- Streaming

**Google AI (Gemini) API**
- Gemini Pro / Ultra
- Multimodal inputs (text, image, video, audio)
- Real-time search grounding
- Context caching (cost reduction)

**Mistral AI API**
- Mistral 7B, 8x7B (MoE), Large
- Function calling
- JSON mode
- Open-source models via Ollama

**Meta (LLaMA) via HuggingFace / Ollama**
- LLaMA 3 models
- Running locally with Ollama
- Fine-tuning LLaMA with PEFT

**Other Key Providers**
- Cohere - enterprise embeddings, RAG
- NVIDIA NIM - GPU-optimized inference
- Groq - ultra-fast inference (LPU)
- Together AI - open-source hosting
- Replicate - model API hosting

### 6.4 API Integration Patterns

**Handling Token Limits**
- Count tokens before sending (tiktoken, anthropic tokenizer)
- Truncation strategies
- Context window management
- Summarization of old history

**Streaming APIs**
- Server-Sent Events (SSE) - streaming text chunks
- Handling partial responses
- Client-side rendering of streaming output
- Benefits: perceived latency reduction

**Rate Limiting & Retries**
- Exponential backoff with jitter
- Respect provider quotas
- Queue-based request management
- Circuit breaker pattern

**Cost Control**
- Log token usage per user/feature
- GPT-3.5 vs GPT-4 routing by task complexity
- Prompt compression (strip whitespace, summarize context)
- Caching with SHA-256 fingerprinting
- Async pipelines for non-realtime tasks

**Error Handling & Fallback**
```
try:
    response = call_gpt4(prompt)
except APIError:
    response = call_gpt35(prompt)  # cheaper fallback
except RateLimitError:
    response = get_cached_response(prompt)
except Exception:
    response = DEFAULT_MESSAGE
```

### 6.5 Secure API Integration

- **Never** expose API keys to frontend
- `.env` files locally, Secret Manager in production
- Backend proxy pattern - frontend → your API → LLM provider
- Per-user rate limiting with Redis
- API key rotation strategy
- Logging and monitoring

---

### 📦 Phase 6 Projects

**🟢 Easy: Multi-Provider AI Chatbot**
- Build a chatbot that can switch between OpenAI / Claude / Gemini
- Add streaming support with SSE
- Store conversation history in Redis
- Stack: FastAPI, OpenAI SDK, Anthropic SDK, Redis, React

**🟡 Medium: AI-Powered Resume Ranker**
- Upload a PDF resume → extract text → compare with job description
- Return match score, missing skills, feedback
- Add caching with Redis (SHA-256 fingerprinting)
- Stack: FastAPI, OpenAI, `pdf-parse`, Redis, React

**🔴 Hard: Production AI Middleware Service**
- Build a middleware that sits between your app and multiple LLM providers
- Features: intelligent routing, rate limiting, cost tracking, fallback chain, prompt logging, token counting, async batching
- Stack: FastAPI, Redis, PostgreSQL, OpenAI + Anthropic + Gemini SDKs, Docker

---

## 🗺️ PHASE 7 - Multi-LLM Orchestration (Your Specialty)

> **Goal:** Design and build production-grade multi-LLM systems. This is what separates good AI engineers from great ones.

### 7.1 Why Multi-LLM Architecture

- No single model is best for all tasks
- Cost optimization - use expensive models only when needed
- Reliability - fallback when one provider is down
- Latency - route to fastest model for simple queries
- Compliance - some enterprise customers can't use certain providers
- Context window - route to Claude for long docs, GPT-4 for reasoning

### 7.2 Routing Strategies

**Task-Based Routing**
```
Simple query   → Mistral 7B / GPT-3.5    (cheap, fast)
Reasoning      → GPT-4 / Claude 3 Opus   (expensive, accurate)
Long context   → Claude 3.5 Sonnet       (200K context)
Code           → GPT-4 / CodeLlama       (specialized)
Multimodal     → Gemini Pro / GPT-4V     (vision)
Embeddings     → text-embedding-3-small  (cost-effective)
Fast inference → Groq (LLaMA 3)          (ultra-low latency)
```

**Cost-Based Routing**
- User tier check: free → cheap models, premium → GPT-4
- Token budget monitoring
- Dynamic routing based on monthly spend
- Cache hit rate optimization

**Performance-Based Routing**
- Track response quality per model per task type
- A/B testing models in production
- Feedback loop - user ratings inform routing
- Latency SLA enforcement

### 7.3 Fallback Architecture

```
Primary:   GPT-4o           (preferred, best quality)
    ↓ fail
Secondary: Claude 3.5 Sonnet (similar quality)
    ↓ fail
Tertiary:  GPT-3.5 Turbo    (cheaper, still capable)
    ↓ fail
Cache:     Last known response (stale but something)
    ↓ miss
Default:   Static template response
```

**Circuit Breaker Pattern**
- Track failure rate per provider
- Open circuit after N failures in M seconds
- Half-open state - test with single request
- Close circuit on success

### 7.4 Model Context Protocol (MCP)

- What is MCP - Anthropic's open standard for AI-tool connectivity
- MCP vs function calling vs tool use
- MCP Servers - resources, tools, prompts
- MCP Clients - Claude Desktop, IDEs, custom apps
- Building an MCP server in Python
- Building an MCP server in TypeScript
- Connecting MCP to databases, APIs, file systems
- MCP for multi-agent systems
- Security considerations in MCP

### 7.5 LLM Orchestration Frameworks

**LangChain**
- Core concepts: Chains, Agents, Memory, Tools
- `LLMChain` - basic prompt + LLM
- `SequentialChain` - chaining multiple LLMs
- `ConversationalChain` - with memory
- `RetrievalQA` - RAG chain
- Tool calling with LangChain agents
- LCEL (LangChain Expression Language) - new composition syntax
- LangSmith - observability and tracing

**LangGraph**
- What LangGraph adds over LangChain - stateful, cyclical workflows
- Nodes - units of work (LLM calls, tools, conditions)
- Edges - connections between nodes (conditional, parallel)
- State - shared state passed between nodes
- Building multi-agent workflows with LangGraph
- Human-in-the-loop patterns
- Streaming from LangGraph
- Persistence and checkpointing

**LlamaIndex**
- Data connectors - loading documents
- Index types: VectorStore, Summary, Knowledge Graph
- Query engines
- Sub-question decomposition
- LlamaIndex vs LangChain - when to use which

**CrewAI**
- Multi-agent task decomposition
- Agents with roles, backstories, goals
- Tasks and process flows
- Tool integration

**AutoGen (Microsoft)**
- Multi-agent conversation patterns
- AssistantAgent vs UserProxy
- Code execution agents
- Group chat patterns

### 7.6 Building PrinceSinghAI / PrinceSinghDev Style Systems

**Multi-LLM Gateway Architecture**
```
Client Request
    ↓
API Gateway (Auth, Rate Limit, Logging)
    ↓
Router Service (Task Classification)
    ↓ ↓ ↓
OpenAI  Claude  Gemini  Mistral  (parallel or cascading)
    ↓
Response Aggregator
    ↓
Cache Layer (Redis)
    ↓
Client Response
```

**Key Components to Build**
- Provider abstraction layer - unified interface for all LLMs
- Intelligent router - classify task, select optimal model
- Token counter - per-provider, per-user
- Cost tracker - real-time spend monitoring
- Response validator - schema validation, quality checks
- Fallback manager - cascade through providers
- Cache manager - semantic caching with embeddings
- Observability - traces, metrics, logs

---

### 📦 Phase 7 Projects

**🟢 Easy: LLM Router Dashboard**
- Build a UI that lets you compare responses from GPT-4, Claude, Gemini side by side
- Show token count, cost, latency for each
- Stack: React, FastAPI, OpenAI + Anthropic + Gemini SDKs

**🟡 Medium: Intelligent Multi-LLM Router**
- Classify incoming queries (simple/complex/code/long-context/vision)
- Route to the best model based on classification
- Add fallback chain, cost tracking, response caching
- Stack: FastAPI, Redis, PostgreSQL, OpenAI + Anthropic + Gemini

**🔴 Hard: Production Multi-LLM Orchestration Platform (PrinceSinghAI)**
- Full gateway service with: authentication, per-user rate limiting, intelligent routing, fallback chains, cost tracking per user/feature, prompt versioning, A/B testing, response streaming, observability dashboard
- MCP integration for tool connectivity
- Deploy on Kubernetes with auto-scaling
- Stack: FastAPI, Redis, PostgreSQL, Kafka, OpenAI + Anthropic + Gemini + Mistral, Docker, Kubernetes, Grafana

---

## 🗺️ PHASE 8 - RAG & Vector Databases

> **Goal:** Build retrieval systems that give LLMs access to your private knowledge.

### 8.1 Why RAG Exists

- LLMs have knowledge cutoffs
- LLMs can't access private/proprietary data
- LLMs hallucinate when they don't know
- RAG = Embedding-based search + Prompt-based generation
- RAG vs Fine-tuning - when to use which

### 8.2 Embeddings Deep Dive

- What are embeddings - dense, semantic vector representations
- Embedding models: `text-embedding-3-small`, `text-embedding-3-large` (OpenAI)
- `all-MiniLM-L6-v2`, `bge-large` (open source, HuggingFace)
- `embed-english-v3` (Cohere) - tuned for RAG
- Embedding dimensions - tradeoff between quality and storage
- Batch embedding for efficiency
- Embedding similarity: cosine, dot product, Euclidean

### 8.3 Chunking Strategies

- Fixed-size chunking - simple but naive
- Sentence-based chunking - respects natural boundaries
- Recursive character text splitting - LangChain default
- Semantic chunking - split on topic change
- Document-based chunking - by headers, sections
- Chunk size vs overlap tradeoff
- Chunk metadata - source, page, section

### 8.4 Vector Databases

| DB | Type | Best For |
|---|---|---|
| **FAISS** | Local | Prototyping, research |
| **Chroma** | Local / Cloud | Early production |
| **Pinecone** | Managed | Production scale |
| **Weaviate** | Self-hosted | Metadata filtering |
| **Qdrant** | Self-hosted | High performance |
| **LanceDB** | Embedded | Serverless apps |
| **pgvector** | PostgreSQL ext | Existing Postgres users |
| **MongoDB Atlas** | Managed | Full-stack apps |
| **Supabase** | Managed | Postgres + vectors |

**Vector DB Operations**
- Indexing - storing embeddings with metadata
- Similarity search - finding nearest neighbors
- Filtered search - metadata + vector similarity
- Hybrid search - keyword + vector (BM25 + embeddings)
- Namespace/collection isolation - multi-tenant
- HNSW index - Hierarchical Navigable Small World (algorithm behind most vector DBs)

### 8.5 RAG Pipeline Implementation

**Basic RAG**
```
Document → Chunk → Embed → Store in Vector DB
                                    ↓
User Query → Embed → Retrieve Top-K Chunks
                                    ↓
            Chunks + Query → LLM → Answer
```

**Advanced RAG Techniques**
- **Hypothetical Document Embeddings (HyDE)** - generate hypothetical answer, embed it for retrieval
- **Query expansion** - generate multiple query variants
- **Reranking** - use a cross-encoder to rerank retrieved chunks (Cohere Rerank, BGE Reranker)
- **Multi-query retrieval** - decompose complex question into sub-queries
- **Self-querying** - LLM generates structured filter from natural language
- **Contextual compression** - compress retrieved context before sending to LLM
- **Parent document retriever** - retrieve small chunks, return parent document
- **Multi-vector retriever** - multiple embeddings per document (summary + full text)

**RAG Evaluation**
- Faithfulness - is the answer grounded in retrieved context?
- Answer relevance - does the answer address the question?
- Context precision - are the retrieved chunks relevant?
- Context recall - did we retrieve all necessary information?
- Tools: RAGAs framework, LangSmith, TRULENS

### 8.6 Production RAG Considerations

- Incremental indexing - adding new documents without reindexing
- Document versioning - handling document updates
- Multi-tenant isolation - per-user, per-org vector spaces
- Caching - cache embeddings, cache query results
- Monitoring - retrieval quality, latency, hit rates
- Fallback - "I don't know" when context is insufficient

---

### 📦 Phase 8 Projects

**🟢 Easy: Chat with Your PDF**
- Upload a PDF, chunk and embed it, ask questions
- Stack: LangChain, OpenAI, Chroma, Streamlit

**🟡 Medium: Multi-Document Knowledge Base**
- Ingest multiple documents (PDF, DOCX, TXT, web pages)
- Hybrid search: BM25 + vector similarity
- Source attribution in answers
- Stack: LlamaIndex, Qdrant, Cohere Rerank, FastAPI, React

**🔴 Hard: Enterprise RAG System (RoadmapAI Context)**
- Multi-tenant RAG with namespace isolation
- Incremental document ingestion pipeline
- Advanced retrieval: HyDE + reranking + contextual compression
- RAG evaluation dashboard with RAGAs
- Production deployment with Redis caching and monitoring
- Stack: LangChain, Pinecone, Cohere, FastAPI, Redis, PostgreSQL, Grafana, Docker

---

## 🗺️ PHASE 9 - AI Agents & Agentic Systems

> **Goal:** Build autonomous AI systems that can reason, plan, and take actions.

### 9.1 What Are AI Agents

- Agent = LLM + Tools + Memory + Planning
- Difference between chain and agent - agents decide dynamically
- Types: ReAct, Plan-and-Execute, Multi-agent
- When to use agents vs chains
- Risks: cost, hallucination, infinite loops

### 9.2 Agent Components

**Tools / Functions**
- Web search tools (Tavily, SerpAPI, Bing)
- Code interpreter / execution
- Calculator
- Database query tool
- File read/write tool
- API call tools
- Web scraping tools
- Calendar, email, calendar tools (via MCP)

**Memory Systems**
- In-context memory - conversation history in prompt
- External memory - vector store of past interactions
- Entity memory - tracking mentioned entities
- Summary memory - compress old conversation
- Episodic memory - remember specific past events

**Planning Strategies**
- ReAct (Reason + Act) - interleave thinking and action
- Plan-and-execute - generate full plan first, then execute
- Tree of Thoughts - explore multiple reasoning paths
- MRKL (Modular Reasoning, Knowledge, Language)

### 9.3 Function Calling / Tool Use

**OpenAI Tool Use**
- Define tools as JSON schemas
- Attach to API call
- Parse tool call responses
- Execute tool, return result
- Continue conversation with tool result
- Parallel tool calls

**Anthropic Tool Use**
- Tool definition format
- Tool result format
- Multi-tool usage

**Building Robust Tool Systems**
- Tool validation - input schema validation
- Tool error handling - graceful failure
- Tool timeouts
- Tool authorization - what can the agent do?
- Sandboxed code execution

### 9.4 Multi-Agent Systems

**Patterns**
- Supervisor → Worker agents (hierarchical)
- Peer-to-peer agents (collaborative)
- Pipeline agents (sequential specialists)
- Adversarial agents (critic + generator)

**LangGraph for Multi-Agent**
- Stateful graphs with shared state
- Conditional edges - dynamic routing
- Parallel execution of agents
- Human-in-the-loop checkpoints
- Agent communication protocols

**Real-World Multi-Agent Use Cases**
- Code review system: Writer + Reviewer + Tester agents
- Research system: Planner + Researcher + Synthesizer agents
- Software development: PM + Engineer + QA agents (Devin-style)
- Customer support: Classifier + Specialist + Escalation agents

### 9.5 Agentic AI (AskAI Framework)

**Agentic Principles**
- Autonomy - agents make decisions without human input per step
- Goal-directedness - agents work toward specified objectives
- Persistence - agents maintain state across interactions
- Adaptability - agents adjust based on feedback

**Production Agentic Systems**
- Task decomposition - breaking complex tasks into subtasks
- Progress tracking - monitoring multi-step completion
- Error recovery - retrying failed steps
- Human escalation - when to pause and ask for input
- Audit trails - logging every agent decision

**Safety in Agents**
- Action confirmation for irreversible operations
- Scope limitation - what agents can and cannot do
- Cost controls - maximum spend per agent run
- Sandboxing code execution
- Input/output validation

---

### 📦 Phase 9 Projects

**🟢 Easy: ReAct Agent with Web Search**
- Build an agent that can search the web to answer current events questions
- Tools: Tavily search, calculator, current date
- Stack: LangChain, OpenAI, Tavily API

**🟡 Medium: Code Review Agent**
- Multi-agent: Reviewer (finds issues), Improver (suggests fixes), Tester (writes tests)
- Supports Python and JavaScript
- Stack: LangGraph, OpenAI, Docker (sandboxed execution)

**🔴 Hard: Autonomous Research Agent (AskAI)**
- Given a research question, agent: decomposes into sub-questions, searches web + internal knowledge base, reads papers, synthesizes findings, writes a structured report
- Features: parallel research, source citation, confidence scoring, human approval checkpoints
- Stack: LangGraph, OpenAI + Claude, Tavily, Pinecone, FastAPI, React, Redis for state

---

## 🗺️ PHASE 10 - Fine-Tuning & Model Customization

> **Goal:** Customize models for your specific domain and use case.

### 10.1 When to Fine-Tune

**Fine-tune when:**
- You need consistent output format that prompt engineering can't achieve
- You have domain-specific knowledge (medical, legal, code)
- You need to reduce prompt length (bake instructions into model)
- You need better performance on a specific task

**Don't fine-tune when:**
- RAG can solve the problem cheaper
- You don't have enough quality data (< 50-100 examples is usually not enough)
- The task is easily solved with prompt engineering
- You need latest knowledge (fine-tuning doesn't update knowledge)

### 10.2 Full Fine-Tuning

- Understanding the fine-tuning pipeline
- Data preparation - instruction format: `{"prompt": "...", "completion": "..."}`
- OpenAI fine-tuning API (GPT-3.5, GPT-4o-mini)
- HuggingFace `Trainer` API
- Training data quality > quantity
- Validation set - monitoring overfitting
- Hyperparameters: learning rate, epochs, batch size

### 10.3 Parameter-Efficient Fine-Tuning (PEFT)

**LoRA (Low-Rank Adaptation)**
- Intuition - inject small trainable matrices into attention layers
- Rank (r) - tradeoff between efficiency and capacity
- Alpha (scaling factor)
- Which layers to apply LoRA to
- Merging LoRA weights into base model

**QLoRA (Quantized LoRA)**
- 4-bit quantization of base model
- LoRA on top of quantized model
- Fine-tune 70B models on consumer GPU
- NF4 quantization (Normal Float 4)

**Other PEFT Methods**
- Prefix Tuning - trainable prefix tokens
- Prompt Tuning - soft prompts
- IA3 - inject trainable vectors into attention and FFN

### 10.4 Fine-Tuning Tools

- **HuggingFace PEFT library** - standard for LoRA/QLoRA
- **TRL (Transformer Reinforcement Learning)** - SFT, RLHF, DPO
- **Unsloth** - 2x faster fine-tuning, less memory
- **Axolotl** - production fine-tuning framework
- **LLaMA-Factory** - easy fine-tuning UI
- **Weights & Biases** - experiment tracking
- **MLflow** - model versioning

### 10.5 Dataset Preparation

- Instruction-following format (Alpaca format)
- Chat format (ShareGPT format)
- DPO format: chosen vs rejected responses
- Data cleaning and deduplication
- Data augmentation techniques
- Quality filtering - removing low-quality examples
- Data mixing strategies

### 10.6 Evaluation After Fine-Tuning

- Task-specific metrics (BLEU, ROUGE, F1, accuracy)
- Benchmark suites: MMLU, HumanEval, MT-Bench
- Human evaluation
- LLM-as-judge evaluation
- Regression testing - ensure you didn't degrade on other tasks

---

### 📦 Phase 10 Projects

**🟢 Easy: Fine-tune GPT-3.5 on Custom Q&A**
- Prepare 100 high-quality Q&A pairs in your domain
- Fine-tune via OpenAI API
- Compare base vs fine-tuned model performance
- Stack: OpenAI Fine-tuning API, Python

**🟡 Medium: LoRA Fine-tune LLaMA on Code**
- Fine-tune LLaMA 3 8B with LoRA for code generation in a specific language/framework
- Use HuggingFace PEFT + TRL
- Evaluate on HumanEval
- Stack: HuggingFace PEFT, TRL, Unsloth, W&B

**🔴 Hard: Full RLHF Pipeline (CodeLLM Context)**
- Collect preference data (chosen vs rejected code completions)
- Train reward model
- Apply DPO to fine-tune base model
- Evaluate on custom benchmark
- Stack: TRL, HuggingFace, PyTorch, Axolotl, W&B, Docker

---

## 🗺️ PHASE 11 - Generative AI (Beyond Text)

### 11.1 Variational Autoencoders (VAEs)

- Encoder → latent space → decoder
- KL divergence loss + reconstruction loss
- Reparameterization trick
- Applications: image generation, anomaly detection

### 11.2 Generative Adversarial Networks (GANs)

- Generator vs Discriminator
- Minimax game
- Mode collapse - the main challenge
- Conditional GANs (cGAN)
- StyleGAN, DCGAN
- Applications: image synthesis, style transfer

### 11.3 Diffusion Models

- Forward process - adding noise to data
- Reverse process - learning to denoise
- DDPM (Denoising Diffusion Probabilistic Models)
- Score matching
- DDIM - faster sampling
- Classifier-free guidance
- Stable Diffusion architecture
- ControlNet - conditional generation

### 11.4 Text-to-Image APIs

- DALL-E 3 API - OpenAI
- Stable Diffusion via Replicate / HuggingFace
- Midjourney (no API, UI-based)
- Ideogram, Flux - newer models
- Prompt engineering for image generation
- Negative prompts

### 11.5 Multimodal AI

- Vision-Language Models (VLMs)
- GPT-4V / GPT-4o - text + image input
- Claude 3 Vision
- Gemini (text + image + video + audio)
- LLaVA - open-source VLM
- CLIP - connecting text and images
- Applications: image captioning, visual QA, document understanding

### 11.6 Audio AI

- OpenAI Whisper - speech-to-text
- TTS: OpenAI TTS, ElevenLabs, Coqui
- Music generation: Suno, Udio
- Voice cloning
- Real-time speech processing

### 11.7 Video AI

- Sora (OpenAI) - text-to-video
- Runway ML, Pika Labs
- Video understanding with Gemini
- Frame-by-frame analysis

---

### 📦 Phase 11 Projects

**🟢 Easy: Image + Text Multi-Modal QA**
- Build an app: upload an image, ask a question about it
- Use GPT-4V or Claude Vision
- Stack: FastAPI, OpenAI Vision API, React

**🟡 Medium: AI Image Generation Pipeline**
- Build a text-to-image app with style controls
- Add image-to-image transformation
- Add safety filtering with moderation API
- Stack: DALL-E 3 API, Stable Diffusion (Replicate), FastAPI, React

**🔴 Hard: Voice AI Assistant (Full Pipeline)**
- Voice input → Whisper STT → LLM processing → TTS output
- Features: streaming audio, wake word detection, multi-language support
- Stack: OpenAI Whisper, GPT-4, ElevenLabs TTS, FastAPI, React Native

---

## 🗺️ PHASE 12 - MLOps, LLMOps & Production Systems

> **Goal:** Ship AI to production reliably, cheaply, and scalably.

### 12.1 Data Management & Versioning

- DVC (Data Version Control) - versioning datasets and models
- Data validation - Great Expectations, Pandera
- Data lineage - tracking data origins
- Feature stores - Feast, Tecton
- Data pipelines - Airflow, Prefect, Luigi

### 12.2 Experiment Tracking

- Weights & Biases (W&B) - industry standard
- MLflow - open source alternative
- What to track: hyperparameters, metrics, artifacts, code version
- Comparing runs and reporting

### 12.3 Model Development & Training Infrastructure

- GPU cloud: AWS (SageMaker, EC2), GCP (Vertex AI), Azure ML
- Distributed training: PyTorch DDP, DeepSpeed, FSDP
- Mixed precision training (FP16, BF16)
- Model checkpointing
- Training monitoring and alerting

### 12.4 Model Evaluation & Testing

**Offline Evaluation**
- Task-specific benchmarks
- Human evaluation with guidelines
- LLM-as-judge (GPT-4 evaluating other models)
- Red teaming - adversarial testing

**Online Evaluation**
- A/B testing models in production
- Shadow deployment - run new model in parallel
- Canary releases - gradual traffic shifting
- User feedback collection (thumbs up/down)

### 12.5 Model Deployment & Serving

**API Serving**
- FastAPI - the standard for ML APIs
- Flask - simpler, less performant
- gRPC - for high-throughput internal services
- BentoML - ML-specific serving framework
- Ray Serve - distributed serving

**Model Optimization for Serving**
- Quantization - INT8, INT4 (reduce model size)
- Pruning - removing unnecessary weights
- Knowledge distillation - smaller student model
- ONNX - framework-agnostic model format
- TensorRT - NVIDIA optimized inference

**Inference Backends**
- Ollama - local model serving
- vLLM - high-throughput LLM serving (PagedAttention)
- TGI (Text Generation Inference) - HuggingFace
- LiteLLM - unified API for all providers
- NVIDIA NIM - production-grade inference

### 12.6 Containerization & Orchestration

- Docker - containerize everything
- `Dockerfile` for ML services
- Multi-stage builds for smaller images
- Docker Compose - local multi-service development
- Kubernetes (K8s) - production orchestration
- Helm charts - K8s app packaging
- Horizontal Pod Autoscaler (HPA) - scale based on load
- GPU scheduling in K8s

### 12.7 Cloud Deployment

**AWS**
- EC2 + SageMaker for ML
- Lambda for lightweight AI functions
- ECS / EKS for containers
- S3 for model/data storage
- CloudWatch for monitoring

**GCP**
- Vertex AI - full ML platform
- Cloud Run - serverless containers
- GKE - managed Kubernetes
- BigQuery for ML data

**Azure**
- Azure ML
- Azure OpenAI Service - enterprise OpenAI
- AKS - managed Kubernetes

### 12.8 Monitoring & Logging

**LLM-Specific Monitoring**
- Token usage per user/feature (cost)
- Latency (p50, p95, p99)
- Error rates by provider
- Prompt quality monitoring
- Response quality scores
- Hallucination detection
- Drift detection - model behavior changes

**Tools**
- **LangSmith** - LangChain observability
- **Helicone** - OpenAI proxy with analytics
- **Langfuse** - open-source LLM observability
- **Prometheus + Grafana** - general metrics
- **Datadog** - full-stack monitoring
- **Sentry** - error tracking

### 12.9 CI/CD for AI

- GitHub Actions / GitLab CI for AI pipelines
- Automated testing for ML (pytest + model tests)
- Model validation before deployment
- Prompt regression testing
- Automated model evaluation in CI
- Feature flags for AI features
- Blue-green deployments

### 12.10 LLM Security & Safety

**Prompt Injection Defense**
- System/user role separation
- Input sanitization - blocking override phrases
- Output validation
- Logging suspicious prompts
- File injection scanning (PDFs, DOCX)

**Content Moderation**
- OpenAI Moderation API
- Pre-screening user input
- Post-screening model output
- Category-based blocking: hate, self-harm, NSFW
- Custom classifiers for domain-specific content

**Data Privacy**
- PII detection and masking before sending to APIs
- Data residency requirements (EU, US, India)
- On-premise deployment for sensitive data
- Audit logs for compliance

---

### 📦 Phase 12 Projects

**🟢 Easy: Dockerize an AI API**
- Containerize your FastAPI + OpenAI app
- Add health checks, proper logging, env var management
- Deploy to a cloud provider (Railway, Render, or AWS)
- Stack: Docker, FastAPI, GitHub Actions

**🟡 Medium: LLMOps Monitoring Dashboard**
- Instrument your AI API with Langfuse or Helicone
- Track: token usage, latency, error rates, cost per user
- Build alert rules for anomalies
- Stack: FastAPI, Langfuse/Helicone, Grafana, PostgreSQL

**🔴 Hard: Production AI Platform on Kubernetes**
- Multi-service AI platform: API gateway, router service, LLM proxy, monitoring
- Kubernetes deployment with HPA for auto-scaling
- CI/CD pipeline with GitHub Actions
- Full observability: Prometheus, Grafana, Langfuse
- Stack: FastAPI, Redis, PostgreSQL, Docker, Kubernetes, Helm, GitHub Actions, Prometheus, Grafana

---

## 🗺️ PHASE 13 - AI System Design

> **Goal:** Design AI systems at scale for real-world products and interviews.

### 13.1 AI System Design Framework

**How to approach any AI system design question:**
1. **Clarify requirements** - functional + non-functional
2. **Identify AI components** - what tasks need AI?
3. **Data flow design** - how does data move through the system?
4. **Model selection** - which LLM/model is best for each task?
5. **Scalability** - how does it handle 10x, 100x load?
6. **Cost optimization** - what's the cost per user?
7. **Reliability** - what happens when AI fails?
8. **Monitoring** - how do you know it's working?

### 13.2 Classic AI System Designs

**AI Chatbot with Memory**
```
Frontend (Chat UI) → Backend API → Session Manager (Redis)
→ Context Builder → LLM → Response → Cache → Return
Fallback: if LLM fails → cached response or template
```

**RAG Knowledge Base**
```
Documents → Ingestion Pipeline → Chunker → Embedder → Vector DB
User Query → Embed → Retrieve Top-K → Rerank → LLM → Answer
```

**Multi-LLM Recommendation System**
```
User Profile → Embedding → Vector DB Similarity
→ GPT scoring → Re-rank → Personalized Results
Feedback loop → Update embeddings
```

**PDF Q&A at Scale (10K users)**
```
Upload → Hash check → Queue → Text Extract → Chunk → Embed → Store
Query → Embed → Retrieve → Rerank → GPT → Stream Response
Cache: query-level caching with semantic similarity
```

**AI Customer Support**
```
Message → Intent classifier → Router
Low confidence → Human escalation
High confidence → RAG knowledge base → LLM response
Track: session state in Redis, conversation in PostgreSQL
```

### 13.3 Inference Placement Strategy

| Placement | Pros | Cons | Use When |
|---|---|---|---|
| Backend API | Secure, logging, easy scaling | Higher latency | Most cases |
| Client-side (browser) | Ultra-low latency, offline | Exposes model, limited | Small models |
| Edge (Cloudflare Workers) | Low latency + secure | Complex, model limits | Search autocomplete |
| Async Queue | Handle spikes, cheap | Delayed response | Long tasks |

### 13.4 Caching Strategies

**Exact Match Caching**
- SHA-256 hash of prompt → Redis key
- Best for: template-based prompts with limited variation

**Semantic Caching**
- Embed the query → find similar cached queries (cosine similarity)
- Return cached answer if similarity > threshold
- Best for: conversational apps with similar questions

**Prompt Template Caching**
- Cache at the template level, not instance level
- Best for: structured generation with variable substitution

### 13.5 Async AI Architecture

**When to use async:**
- Model latency > 2-3 seconds
- Processing expensive (PDF analysis, batch jobs)
- User doesn't need immediate response

**Async pattern:**
```
Frontend → POST /task → Task ID returned immediately
Worker → processes → updates DB
Frontend → polls GET /task/{id} or receives webhook
```

### 13.6 Cost-Aware Architecture

**Per-feature model selection:**
```
Autocomplete    → GPT-3.5 Turbo ($0.001/1K)
Summarization   → Claude Haiku  ($0.00025/1K)
Complex QA      → GPT-4o        ($0.01/1K)
Embeddings      → text-embedding-3-small ($0.00002/1K)
Classification  → Fine-tuned GPT-3.5 ($0.003/1K)
```

**Cost reduction strategies:**
- Prompt compression - remove unnecessary tokens
- Output length limits - `max_tokens` parameter
- Caching (50-70% reduction for typical apps)
- Model downgrade for free tier users
- Async batching - bundle requests
- Context window optimization

---

### 📦 Phase 13 Projects

**🟢 Easy: Design Doc for AI Feature**
- Write a 5-page design doc for an AI feature (e.g., AI writing assistant)
- Cover: architecture, data flow, model choice, cost estimate, fallback
- Get feedback from the community

**🟡 Medium: Cost Calculator Tool**
- Build a tool that estimates AI API costs given usage patterns
- Supports OpenAI, Anthropic, Gemini, Cohere pricing
- Shows cost breakdown by model, feature, user tier
- Stack: React, FastAPI

**🔴 Hard: Full AI System Design Implementation**
- Implement the complete architecture for one of the classic designs above
- Focus: production-grade, scalable, monitored, cost-aware
- Write ADRs (Architecture Decision Records) for key decisions
- Stack: Full production stack of your choice

---

## 🗺️ PHASE 14 - SQL & Databases for AI Engineers

> **Goal:** Query data confidently and design databases that support AI systems.

### 14.1 Core SQL

- `SELECT`, `FROM`, `WHERE`, `ORDER BY`, `LIMIT`, `DISTINCT`
- `AND`, `OR`, `NOT`, `IN`, `BETWEEN`, `LIKE`, `IS NULL`
- `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`, `SELF JOIN`
- `GROUP BY`, `HAVING`
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`

### 14.2 Advanced SQL

- CTEs (Common Table Expressions) - `WITH` clauses
- Window functions: `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `LAG()`, `LEAD()`
- `PARTITION BY` vs `GROUP BY`
- `SUM() OVER`, `AVG() OVER` - running totals
- Recursive CTEs - hierarchical data
- Subqueries: correlated vs non-correlated
- `CASE WHEN` conditional logic
- `COALESCE` for NULL handling

### 14.3 AI-Specific SQL Patterns

- Feature engineering queries (ratios, rolling averages)
- Pivoting data for ML features
- Sampling: `ORDER BY RANDOM() LIMIT n`
- JSON columns (`JSON_EXTRACT`, `->` in Postgres)
- **pgvector** - vector similarity search in PostgreSQL
  - `<->` cosine distance operator
  - `<#>` negative inner product
  - `<=>` L2 distance
  - Creating vector indexes (HNSW, IVFFlat)

### 14.4 Database Design for AI Applications

- Schema design for conversation history
- Schema for prompt versions and results
- Schema for token usage tracking
- Schema for user preferences/memory
- Indexing for AI workloads

### 14.5 NoSQL for AI

- **Redis** - session state, caching, rate limiting, pub/sub for streaming
- **MongoDB** - flexible document storage for AI outputs
- **DynamoDB** - serverless, high-throughput
- When to use SQL vs NoSQL for AI applications

---

### 📦 Phase 14 Projects

**🟢 Easy: AI Usage Analytics Dashboard**
- Design and query a database tracking AI API usage
- Build queries: cost per user, top features, error rates
- Stack: PostgreSQL, Python, Metabase/Grafana

**🟡 Medium: pgvector Semantic Search**
- Implement semantic search using pgvector in PostgreSQL
- Store embeddings alongside metadata
- Build efficient HNSW index
- Stack: PostgreSQL + pgvector, FastAPI, OpenAI Embeddings

**🔴 Hard: Complete Database Architecture for AI Platform**
- Design full schema for a multi-tenant AI platform
- Includes: users, conversations, tokens, embeddings, prompt versions, A/B tests
- Implement migrations, indexes, partitioning
- Stack: PostgreSQL, pgvector, Redis, Alembic (migrations)

---

## 🗺️ PHASE 15 - Quantization, Optimization & Efficiency

> **Goal:** Run models efficiently at scale.

### 15.1 Model Quantization

- What is quantization - reducing precision of weights
- FP32 → FP16 → BF16 → INT8 → INT4
- Post-Training Quantization (PTQ)
- Quantization-Aware Training (QAT)
- GPTQ - accurate quantization method for LLMs
- AWQ (Activation-aware Weight Quantization)
- GGUF - format for llama.cpp (local inference)
- Using `bitsandbytes` library for 4-bit/8-bit

### 15.2 Inference Optimization

- KV Cache - avoiding recomputation
- Continuous batching - dynamic batching of requests (vLLM's approach)
- Speculative decoding - use small draft model to speed up large model
- Flash Attention v2 - memory-efficient attention
- Tensor parallelism - splitting model across GPUs
- Pipeline parallelism - pipelining layers across GPUs

### 15.3 Small Language Models (SLMs)

- Phi-3 / Phi-4 (Microsoft) - powerful small models
- Gemma 2 2B (Google) - efficient small model
- Mistral 7B - best open-source small model
- Qwen 2.5 1.5B, 3B - multilingual SLMs
- SmolLM - tiny models for edge
- When SLMs beat LLMs (specific tasks, fine-tuned)
- On-device AI with SLMs

### 15.4 Knowledge Distillation

- Teacher-student training
- Soft labels from teacher
- Intermediate layer distillation
- DistilBERT - distilled BERT
- TinyLlama - distilled LLaMA
- Applications: deploy 7B capability in 1B parameters

### 15.5 Model Serving Efficiency

- **vLLM** - PagedAttention, continuous batching, 24x throughput
- **TGI (Text Generation Inference)** - HuggingFace production server
- **Ollama** - local model serving
- **llama.cpp** - CPU inference, GGUF format
- **ONNX Runtime** - cross-platform inference
- **TensorRT-LLM** - NVIDIA optimized

---

### 📦 Phase 15 Projects

**🟢 Easy: Local LLM Setup**
- Set up Ollama with multiple models (LLaMA 3, Mistral, Gemma)
- Build a simple chat interface connecting to local models
- Benchmark: latency, memory usage per model

**🟡 Medium: Model Quantization Comparison**
- Take LLaMA 3 8B, quantize to 8-bit and 4-bit (GPTQ, AWQ)
- Benchmark: perplexity, speed, memory, task performance
- Stack: bitsandbytes, GPTQ, HuggingFace

**🔴 Hard: High-Throughput Inference Server (CodeLLM)**
- Deploy vLLM with multiple models
- Implement request batching, model switching, load balancing
- Benchmark against naive implementation
- Stack: vLLM, Docker, Kubernetes, Prometheus, Grafana

---

## 🗺️ PHASE 16 - Reinforcement Learning for AI Engineers

> **Goal:** Understand RL enough to work with RLHF, PPO, and agentic training.

### 16.1 RL Fundamentals

- Markov Decision Processes (MDPs)
- Agent, Environment, State, Action, Reward
- Policy - mapping states to actions
- Value function - expected cumulative reward
- Q-function - value of taking action in state
- Exploration vs exploitation (epsilon-greedy, UCB)
- Discount factor (γ)

### 16.2 Value-Based Methods

- Q-learning
- DQN (Deep Q-Network)
- Double DQN, Dueling DQN, Prioritized Experience Replay

### 16.3 Policy-Based Methods

- REINFORCE (Policy Gradient)
- Actor-Critic methods
- PPO (Proximal Policy Optimization) - used in RLHF
- GRPO (Group Relative Policy Optimization) - used in DeepSeek R1

### 16.4 RL for LLMs (RLHF & Beyond)

- RLHF pipeline: SFT → Reward Model → PPO
- Reward model training on human preferences
- PPO with KL divergence constraint (preventing collapse)
- DPO (Direct Preference Optimization) - simpler RLHF alternative
- RLAIF (RL from AI Feedback) - using LLM as evaluator
- Constitutional AI (Claude's approach)
- Process Reward Models (PRMs) - reward at each reasoning step
- Outcome Reward Models (ORMs) - reward only at final answer

### 16.5 Multi-Agent RL

- Cooperative vs competitive agents
- Game theory basics
- Self-play training
- Multi-agent communication

---

### 📦 Phase 16 Projects

**🟢 Easy: Train a CartPole Agent**
- Implement Q-learning and PPO on CartPole-v1
- Compare convergence, stability
- Stack: gymnasium, stable-baselines3, PyTorch

**🟡 Medium: Reward Model Training**
- Collect preference data (A vs B responses)
- Train a reward model using Bradley-Terry model
- Stack: PyTorch, HuggingFace Transformers, TRL

**🔴 Hard: DPO Fine-tuning Pipeline**
- Collect a preference dataset for a specific task
- Fine-tune a 7B model using DPO
- Evaluate against SFT baseline
- Stack: TRL, HuggingFace PEFT, Axolotl, W&B

---

## 🗺️ PHASE 17 - AI Ethics, Safety & Governance

> **Goal:** Build AI responsibly. This is increasingly a job requirement.

### 17.1 AI Safety Fundamentals

- Types of AI harm: immediate, systemic, long-term
- Alignment problem - AI doing what we want
- Hallucination - why models make things up
- Bias and fairness in AI systems
- Dual-use concerns

### 17.2 Prompt Injection & Security

- Direct prompt injection - user manipulates model
- Indirect prompt injection - malicious content in retrieved data
- Defense strategies: role separation, input validation, output filtering
- Jailbreaking patterns and mitigations
- Adversarial testing / red teaming

### 17.3 Bias & Fairness

- Sources of bias: training data, labeling, model design
- Types: demographic, representation, measurement bias
- Fairness metrics: demographic parity, equalized odds
- Bias detection tools: Fairlearn, AI Fairness 360
- Mitigation: reweighting, resampling, constraint-based training

### 17.4 Privacy & Data Governance

- PII in training data and inference
- GDPR compliance for AI systems
- Data minimization principle
- Right to erasure in ML systems
- Differential privacy basics
- Federated learning - train without centralizing data

### 17.5 AI Transparency & Explainability

- Model cards - documenting model capabilities and limitations
- System cards - documenting AI system behavior
- SHAP - SHapley Additive exPlanations
- LIME - Local Interpretable Model-agnostic Explanations
- Attention visualization
- Chain of thought as explainability

### 17.6 Responsible AI in Production

- Content moderation architecture
- Safety classifiers
- Human-in-the-loop for high-stakes decisions
- Audit trails and logging
- Incident response for AI failures
- AI governance frameworks: EU AI Act, NIST AI RMF

---

## 🗺️ CAPSTONE - Build Your Production AI System

> **The final phase: build a complete production AI system that demonstrates all skills**

### Capstone Project: Multi-LLM AI Platform (PrinceSinghAI/PrinceSinghDev Vision)

**System Overview:**
Build a production-grade, multi-tenant AI platform that serves as the foundation for all your AI products.

**Core Components:**
1. **API Gateway** - Authentication, rate limiting, request routing
2. **Multi-LLM Router** - Intelligent routing across OpenAI, Claude, Gemini, Mistral
3. **RAG Engine** - Multi-document, multi-tenant knowledge retrieval
4. **Agent Orchestrator** - Multi-agent workflow execution
5. **MCP Integration** - Tool connectivity via Model Context Protocol
6. **Observability Stack** - Langfuse, Prometheus, Grafana
7. **Admin Dashboard** - Usage analytics, cost tracking, model performance
8. **CI/CD Pipeline** - Automated testing and deployment

**Technical Stack:**
- **Backend:** FastAPI (Python), async everywhere
- **Databases:** PostgreSQL (+ pgvector), Redis, Chroma/Qdrant
- **LLM Providers:** OpenAI, Anthropic, Google AI, Mistral (via LiteLLM)
- **Orchestration:** LangChain + LangGraph
- **Infrastructure:** Docker, Kubernetes, GitHub Actions
- **Monitoring:** Langfuse, Prometheus, Grafana
- **Frontend:** React + TypeScript

**Features to Implement:**
- Multi-tenant user management
- Per-user API key management
- Intelligent model routing with cost optimization
- RAG pipeline with multiple document types
- Streaming responses
- Conversation memory (Redis)
- Prompt version management
- A/B testing for prompts and models
- Cost tracking dashboard
- Usage limits and billing
- Admin panel with full observability

---

## 📚 Resources Reference

### Foundational

| Topic | Resource |
|---|---|
| Linear Algebra | 3Blue1Brown - Essence of Linear Algebra (YouTube) |
| Calculus | 3Blue1Brown - Essence of Calculus (YouTube) |
| Probability & Stats | Statistics 110 - Joe Blitzstein (Harvard, YouTube) |
| Math for ML | Mathematics for Machine Learning - Deisenroth (free PDF) |
| Python basics | Automate the Boring Stuff (free online) |
| NumPy & Pandas | Python for Data Analysis - Wes McKinney |

### Deep Learning

| Topic | Resource |
|---|---|
| Deep Learning | Andrej Karpathy - Neural Networks: Zero to Hero (YouTube) |
| PyTorch | fast.ai Practical Deep Learning |
| Build GPT | Andrej Karpathy - Let's build GPT (YouTube) |
| Deep Learning Book | deeplearningbook.org (free) |

### LLMs & AI Engineering

| Topic | Resource |
|---|---|
| LLMs | Hugging Face NLP Course (free) |
| Transformers | Natural Language Processing with Transformers - Tunstall |
| Prompt Engineering | Anthropic Prompt Engineering Guide |
| LangChain | LangChain documentation + LangSmith |
| RAG | LlamaIndex documentation |
| Agents | LangGraph documentation |
| Fine-tuning | HuggingFace PEFT documentation |

### Production AI

| Topic | Resource |
|---|---|
| MLOps | Made With ML (madewithml.com) |
| LLMOps | LangSmith + Langfuse documentation |
| System Design | Designing ML Systems - Chip Huyen |
| AI Engineering | AI Engineering - Chip Huyen (new book) |

### Stay Current

| Resource | What for |
|---|---|
| Papers With Code | Latest research benchmarks |
| Hugging Face Blog | New models and techniques |
| OpenAI Blog | New APIs and capabilities |
| Anthropic Research | Safety and new Claude features |
| Twitter/X: @karpathy, @sama, @emollick | Industry leaders |
| r/LocalLLaMA | Open-source model news |
| LLM News (newsletter) | Weekly digest |

---

## 🎯 Skills Summary (Market Demand 2026)

### Tier 1 - Must Have (Every AI Engineer Job)

- Python (advanced async, clean code)
- OpenAI API (GPT-4, embeddings, function calling)
- Anthropic API (Claude, long context, tool use)
- Prompt engineering (structured, production-safe)
- RAG architecture (chunking, embeddings, vector DBs)
- FastAPI (building AI APIs)
- Docker (containerize everything)
- Git/GitHub (version control, CI/CD)
- PostgreSQL + Redis (databases for AI apps)
- LangChain or LlamaIndex basics

### Tier 2 - Highly Valued (Stand Out)

- Multi-LLM orchestration (routing, fallbacks, cost optimization)
- LangGraph (agentic systems)
- Fine-tuning with LoRA/QLoRA
- HuggingFace ecosystem
- Kubernetes (production deployment)
- LLMOps (Langfuse, Helicone)
- Model Context Protocol (MCP)
- Vector databases (Pinecone, Qdrant, Weaviate)
- vLLM / TGI (inference optimization)
- Multimodal AI (vision, audio)

### Tier 3 - Expert Level (Senior/Principal)

- Custom RLHF / DPO pipelines
- Distributed training (DeepSpeed, FSDP)
- Custom model architectures
- Advanced RAG (HyDE, reranking, contextual compression)
- AI system design at scale
- ML infrastructure (GPUs, serving)
- AI safety and red teaming
- Business impact measurement

---

## 🛤️ Learning Paths by Goal

### Path A: AI Engineer (Product-Focused)
```
Phase 0 → 1 → 2(lite) → 6 → 7 → 8 → 9 → 12 → 13 → Capstone
Timeline: 6-9 months
```

### Path B: ML Engineer (Research-Focused)
```
Phase 0 → 1 → 2 → 3 → 4 → 5 → 10 → 15 → 16 → Capstone
Timeline: 9-12 months
```

### Path C: AI Architect (Systems-Focused)
```
Phase 0 → 1(lite) → 6 → 7 → 8 → 9 → 12 → 13 → 14 → 15 → Capstone
Timeline: 6 months (experienced engineers)
```

### Path D: Complete Full Stack AI Engineer (You)
```
All Phases → All Projects → Capstone
Timeline: 12-18 months
Focus: PrinceSinghAI · Multi-LLM · AskAI · CodeLLM · RoadmapAI
```

---

## 🏆 Portfolio Projects (Ship These)

1. **Multi-LLM Router** - Route queries across GPT-4, Claude, Gemini with cost tracking
2. **RAG Knowledge Base** - Multi-document, multi-tenant with advanced retrieval
3. **AI Agent Platform** - Multi-agent workflow with LangGraph + MCP
4. **Fine-tuned Domain Model** - LoRA fine-tune on your domain, deploy with vLLM
5. **AI System Design Doc** - Published design for a complex AI system
6. **Open Source Contribution** - Contribute to LangChain, LlamaIndex, or vLLM
7. **Capstone: PrinceSinghAI Platform** - Full production multi-LLM platform

---

*Last Updated: 2026 | Built for the AI-powered era*
*"The best AI Engineers don't just use models - they architect systems around them."*
