# AraGenEval NLP Shared Task

This repository contains our team’s solutions and experiments for the [AraGenEval Shared Task](https://ezzini.github.io/AraGenEval/), which focuses on **Arabic text generation evaluation**.
The project addresses multiple subtasks, including **style transfer**, **style classification**, and **AI/human text detection**.

## 📂 Repository Structure

```
notebooks/
├── AraGenEval_arabic_author_layer_wise_analysis.ipynb
├── AraGenEval_shared_task_1_Authorship_Style_Transfer.ipynb
├── AraGenEval_shared_task_2_arabic_author_style_classification.ipynb
└── AraGenEval_shared_task_3_AI_human_classification.ipynb
```

* **AraGenEval\_arabic\_author\_layer\_wise\_analysis.ipynb**
  Analysis of Arabic author representation across model layers.

* **AraGenEval\_shared\_task\_1\_Authorship\_Style\_Transfer.ipynb**
  Experiments and approach for authorship style transfer.

* **AraGenEval\_shared\_task\_2\_arabic\_author\_style\_classification.ipynb**
  Solution for Arabic author style classification.

* **AraGenEval\_shared\_task\_3\_AI\_human\_classification.ipynb**
  Approach for distinguishing between AI-generated and human-written Arabic texts.

## 📝 Task Description

The **AraGenEval** shared task aims to evaluate and improve NLP systems for Arabic text generation, covering:

1. **Authorship Style Transfer** – changing writing style while preserving meaning.
2. **Arabic Author Style Classification** – predicting the author’s style from text.
3. **AI/Human Classification** – detecting whether a text is machine- or human-generated.

Full task details are available on the [official website](https://ezzini.github.io/AraGenEval/).

## ⚙️ Setup & Requirements

Clone this repository:

```bash
git clone https://github.com/mtami/AraGenEval2025.git
cd notebooks/
```



## 🚀 Usage

Run the notebooks in `notebooks/` to reproduce results:

```bash
jupyter notebook notebooks/<notebook_name>.ipynb
```
