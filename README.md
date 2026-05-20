# Глубокое обучение в науках о данных

Решённые домашние задания по университетскому курсу «Глубокое обучение
в науках о данных» (2026). Восемь работ: от математики отдельного нейрона
до RAG-пайплайнов и прогнозирования временных рядов.

Каждое задание — отдельная папка с Jupyter-блокнотом (`homework.ipynb`)
и кратким описанием темы (`README.md`). Программа курса — в файле
[`syllabus-2026.pdf`](syllabus-2026.pdf).

## Задания

| № | Тема | Папка | Ключевые методы |
|---|------|-------|-----------------|
| 1 | Базовые компоненты нейронных сетей | [`01-neural-network-basics`](01-neural-network-basics/) | Нейрон, функции активации, forward pass, CrossEntropyLoss / BCEWithLogitsLoss / HuberLoss |
| 2 | Регуляризация и контроль сложности | [`02-regularization`](02-regularization/) | Переобучение, L1/L2-регуляризация, `weight_decay` |
| 3 | Свёрточные нейронные сети | [`03-cnn`](03-cnn/) | Свёртки, pooling, padding/stride, классификация, детекция, сегментация |
| 4 | Внимание и архитектура Transformer | [`04-attention-transformers`](04-attention-transformers/) | Scaled dot-product attention, multi-head, позиционное кодирование, decoder-only LM |
| 5 | Генеративные модели | [`05-generative-models`](05-generative-models/) | Autoencoder, VAE, ELBO, латентное пространство, интерполяция |
| 6 | Графовые нейронные сети | [`06-graph-neural-networks`](06-graph-neural-networks/) | GCN, message passing, GraphSAGE, классификация узлов и графов |
| 7 | Обучение с подкреплением | [`07-reinforcement-learning`](07-reinforcement-learning/) | MDP, динамическое программирование, Monte Carlo, TD, SARSA, Q-learning |
| 8 | Глубокое обучение на практике | [`08-applied-deep-learning`](08-applied-deep-learning/) | FAISS, RAG, bi-encoder + cross-encoder, TimeSeriesTransformer, pass@k |

## Стек

Python · PyTorch · NumPy · pandas · scikit-learn · matplotlib / seaborn ·
Hugging Face Transformers и Datasets · sentence-transformers · FAISS · GluonTS · Jupyter

## Как запустить

```bash
git clone <repo-url>
cd deep-learning-in-data-science

python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux / macOS:
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
```

Затем откройте `homework.ipynb` в нужной папке. Задания 4 и 8 заметно тяжелее
по вычислениям — для них желателен GPU.

## Структура репозитория

```
.
├── 01-neural-network-basics/   ДЗ 1 + README
├── 02-regularization/          ДЗ 2 + README
├── ...                         ДЗ 3–7
├── 08-applied-deep-learning/   ДЗ 8 + README
├── syllabus-2026.pdf           программа курса
├── requirements.txt            зависимости
└── README.md
```

## Автор

Вольхин Сергей Александрович

---

# Deep Learning in Data Science

Completed homework for the university course "Deep Learning in Data Science"
(2026). Eight assignments, from the math of a single neuron to RAG pipelines
and time series forecasting.

Each assignment lives in its own folder with a Jupyter notebook
(`homework.ipynb`) and a short topic description (`README.md`). The course
program is in [`syllabus-2026.pdf`](syllabus-2026.pdf).

## Assignments

| # | Topic | Folder | Key methods |
|---|-------|--------|-------------|
| 1 | Building blocks of neural networks | [`01-neural-network-basics`](01-neural-network-basics/) | Neuron, activations, forward pass, CrossEntropyLoss / BCEWithLogitsLoss / HuberLoss |
| 2 | Regularization and model complexity | [`02-regularization`](02-regularization/) | Overfitting, L1/L2 regularization, `weight_decay` |
| 3 | Convolutional neural networks | [`03-cnn`](03-cnn/) | Convolutions, pooling, padding/stride, classification, detection, segmentation |
| 4 | Attention and the Transformer | [`04-attention-transformers`](04-attention-transformers/) | Scaled dot-product attention, multi-head, positional encoding, decoder-only LM |
| 5 | Generative models | [`05-generative-models`](05-generative-models/) | Autoencoder, VAE, ELBO, latent space, interpolation |
| 6 | Graph neural networks | [`06-graph-neural-networks`](06-graph-neural-networks/) | GCN, message passing, GraphSAGE, node and graph classification |
| 7 | Reinforcement learning | [`07-reinforcement-learning`](07-reinforcement-learning/) | MDP, dynamic programming, Monte Carlo, TD, SARSA, Q-learning |
| 8 | Applied deep learning | [`08-applied-deep-learning`](08-applied-deep-learning/) | FAISS, RAG, bi-encoder + cross-encoder, TimeSeriesTransformer, pass@k |

## Stack

Python · PyTorch · NumPy · pandas · scikit-learn · matplotlib / seaborn ·
Hugging Face Transformers and Datasets · sentence-transformers · FAISS · GluonTS · Jupyter

## How to run

```bash
git clone <repo-url>
cd deep-learning-in-data-science

python -m venv .venv
# Windows:
.venv\Scripts\activate
# Linux / macOS:
source .venv/bin/activate

pip install -r requirements.txt
jupyter notebook
```

Open `homework.ipynb` in the folder you need. Assignments 4 and 8 are the
heaviest to compute and benefit from a GPU.

## Author

Sergey Volkhin

## License

MIT — see [`LICENSE`](LICENSE).
