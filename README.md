<div align="center">

# 🧠 LangGraph Concepts

### Hands-on notebooks exploring agentic workflow patterns

<p>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="jupyter"/>
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white" alt="python"/>
  <img src="https://img.shields.io/badge/LangGraph-Concepts-1C3C3C?style=flat-square" alt="langgraph"/>
  <img src="https://img.shields.io/badge/Pydantic-validated-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="pydantic"/>
</p>

</div>

<br/>

## 📖 About

**LangGraph Concepts** is a learning repo of self-contained Jupyter notebooks, each one demonstrating a specific **agentic AI workflow pattern** — from simple prompt chaining to iterative, multi-step agent loops. It's a hands-on reference for understanding how these patterns are built from scratch before wiring them into a larger system.

Each notebook is standalone: open it, run the cells top to bottom, and see the pattern in action.

<br/>

## 📓 Notebooks

| # | Notebook | Concept |
|---|---|---|
| 1 | [`1.tempconversion.ipynb`](./1.tempconversion.ipynb) | Basic workflow scaffolding — a simple task graph, using unit conversion as the toy example |
| 2 | [`2.qabot.ipynb`](./2.qabot.ipynb) | A minimal question-answering bot workflow |
| 3 | [`3.promptchaining.ipynb`](./3.promptchaining.ipynb) | Chaining multiple prompts together, passing output from one step as input to the next |
| 4 | [`4.empanalytics.ipynb`](./4.empanalytics.ipynb) | Applying a workflow to structured data analysis (employee analytics) |
| 5 | [`5.essayworkflow.ipynb`](./5.essayworkflow.ipynb) | A multi-stage writing workflow with **Pydantic**-validated structured outputs |
| 6 | [`6.contentmod.ipynb`](./6.contentmod.ipynb) | Content moderation as an agentic pipeline step |
| 7 | [`7.reviewworkflow.ipynb`](./7.reviewworkflow.ipynb) | A review/approval-style workflow with conditional branching |
| 8 | [`8.iterativeworkflows.ipynb`](./8.iterativeworkflows.ipynb) | Iterative, loop-based agent workflows (retry / refine until a condition is met) |

> Notebooks are numbered in the order they're best explored — concepts build on each other, from linear chains to conditional and iterative graphs.

<br/>

## 🖥️ Getting Started

### Prerequisites

- Python **3.10+**
- Jupyter (Notebook or Lab)

### 1. Clone the repo

```bash
git clone https://github.com/harshadpy/lgconcepts.git
cd lgconcepts
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Open any notebook and run the cells in order. Most notebooks expect an LLM API key (e.g. `OPENAI_API_KEY`) set as an environment variable — check the first cell of each notebook for specifics.

<br/>

## 📂 Project Structure

```
lgconcepts/
├── 1.tempconversion.ipynb
├── 2.qabot.ipynb
├── 3.promptchaining.ipynb
├── 4.empanalytics.ipynb
├── 5.essayworkflow.ipynb
├── 6.contentmod.ipynb
├── 7.reviewworkflow.ipynb
├── 8.iterativeworkflows.ipynb
├── requirements.txt
└── README.md
```

<br/>

## 🤝 Contributing

This is primarily a personal learning repo, but suggestions and fixes are welcome — feel free to open an issue or PR.

<br/>

## 📄 License

No license specified yet — all rights reserved by default until one is added.

---

<div align="center">

Made with 🧠 by [harshadpy](https://github.com/harshadpy)

</div>
