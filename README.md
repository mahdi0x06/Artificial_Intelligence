# 🧠 Artificial Intelligence — Course & Laboratory Repository

<div align="center">

![Language](https://img.shields.io/badge/Language-Python%203.12%20%7C%20Jupyter-blue?style=for-the-badge&logo=python&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Machine%20Learning%20From%20Scratch%20%7C%20RL%20%7C%20CSPs-brightgreen?style=for-the-badge)
![Course](https://img.shields.io/badge/Course-Artificial%20Intelligence-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

*A rigorous academic portfolio of Artificial Intelligence algorithms, custom machine learning models built from scratch, probabilistic sequence classifiers, and reinforcement learning agents.*

</div>

---

## 📖 Table of Contents
1. [Overview](#-overview)
2. [Repository Architecture](#-repository-architecture)
3. [Practical Implementations & Homework Series](#-practical-implementations--homework-series)
   - [HW1: Uninformed & Informed Search](#1-hw1-uninformed--informed-search)
   - [HW2: Adversarial Search (Minimax) & CSP Nonogram Solver](#2-hw2-adversarial-search-minimax--csp-nonogram-solver)
   - [HW3: Probabilistic Modeling & HMM DNA Analysis](#3-hw3-probabilistic-modeling--hmm-dna-analysis)
   - [HW4: Machine Learning From Scratch (Decision Trees & Random Forests)](#4-hw4-machine-learning-from-scratch-decision-trees--random-forests)
   - [HW5: Markov Decision Processes (MDP), Q-Learning & SARSA](#5-hw5-markov-decision-processes-mdp-q-learning--sarsa)
4. [Continuous Assessment (Quizzes & Exams)](#-continuous-assessment-quizzes--exams)
5. [Tech Stack & Prerequisites](#-tech-stack--prerequisites)
6. [Persian Summary for Students (راهنمای فارسی)](#-persian-summary-for-students-راهنمای-فارسی)
7. [License & Author](#-license--author)

---

## 🔭 Overview
This repository contains the complete algorithmic coursework, laboratory projects, and theoretical evaluations for the **Artificial Intelligence (AI)** course. Unlike standard introductory repositories that rely entirely on high-level APIs, this collection emphasizes **implementing core AI engines and machine learning algorithms from scratch** using object-oriented Python and vectorized numerical linear algebra.

The portfolio is structured to demonstrate end-to-end algorithmic mastery—ranging from state-space constraint satisfaction and alpha-beta pruning in adversarial environments to temporal probability models and reinforcement learning in stochastic domains.

---

## 📂 Repository Architecture

Based on the version-controlled structure (excluding archived and ignored materials), the repository is organized into four primary academic directories:

```text
📦 Artificial_Intelligence
 ┣ 📂 Hws/             # 5 Comprehensive homework series (Practical notebooks + Theoretical proofs)
 ┃ ┣ 📂 1/             # Search strategies, heuristics, and state-space exploration
 ┃ ┣ 📂 2/             # Minimax Tic-Tac-Toe agent & Object-Oriented CSP Nonogram solver
 ┃ ┣ 📂 3/             # Financial Bayesian Networks & HMM sequence decoding for DNA data
 ┃ ┣ 📂 4/             # Core ML from scratch: Decision Trees, Random Forests, & Tabular NLP
 ┃ ┗ 📂 5/             # Bellman MDP iterations, Q-Learning, & SARSA reinforcement learning
 ┣ 📂 Quiz/            # 6 Series of continuous assessment quizzes and analytical solutions
 ┃ ┣ 📂 1/ to 📂 6/
 ┣ 📂 exams/           # Midterm and Final examination problems, evaluations, and solutions
 ┃ ┣ 📂 midterm/
 ┃ ┗ 📂 final/
 ┗ 📂 slides/          # Complete slide deck across 27 lecture sessions (Session 1 to 27)
```

---

## 🚀 Practical Implementations & Homework Series

### 1. HW1: Uninformed & Informed Search
Exploration of classical graph and tree search algorithms:
* Implementation and comparative analysis of Breadth-First Search (BFS), Depth-First Search (DFS), and Iterative Deepening Search (IDS).
* **A\* Search Engine:** Designing admissible and consistent heuristics for optimal pathfinding in complex spatial maps.

### 2. HW2: Adversarial Search (Minimax) & CSP Nonogram Solver
Focuses on decision-making in competitive environments and constraint satisfaction:
* **Adversarial Gaming (`Tic-Tac-Toe.ipynb`):** Building an autonomous game agent utilizing the **Minimax algorithm with Alpha-Beta Pruning** to explore decision trees and guarantee optimal game-theoretic play.
* **CSP Nonogram Solver (`CSP_Nonogram_Student.ipynb`, `models.py`):** An object-oriented Constraint Satisfaction Problem solver designed to reconstruct pixel-art visual grids (Nonograms) from row and column clues. Implements backtracking search enhanced by domain pruning, forward checking, and constraints propagation.

```
       [ Row / Column Clues ] ---> [ Backtracking Engine ] ---> [ Constraint Propagation ]
                                                                           |
       [ Solved Nonogram Grid ] <--- [ MRV & Degree Heuristics ] <---------+
```

### 3. HW3: Probabilistic Modeling & HMM DNA Analysis
Handling uncertainty, temporal reasoning, and sequential state estimation:
* **Bayesian Financial Modeling (`fmapp.ipynb`):** Constructing conditional probability tables and Bayesian networks to perform probabilistic inference over historical financial market data (`fmapp_historical_data.csv`).
* **Hidden Markov Models for Bioinformatics (`hmm_dna.ipynb`):** Implementing HMM evaluation and decoding algorithms (such as the Viterbi algorithm) to classify and predict sequence variations in biological DNA datasets (`dna_dataset.csv`).

### 4. HW4: Machine Learning From Scratch (Decision Trees & Random Forests)
A core portfolio showcase located in `ml_core.ipynb` and `westeros.ipynb`, moving beyond black-box libraries to construct predictive models from foundational mathematical equations:
* **Decision Tree from Scratch:** Custom object-oriented implementation calculating dynamic splitting criteria via **Information Gain (Shannon Entropy)** and **Gini Impurity**. Supports recursive tree partitioning and depth stopping criteria.
* **Random Forest Ensemble:** Building a Bootstrap Aggregating (Bagging) classifier over the custom decision tree modules, introducing feature subsampling to reduce variance and combat overfitting.
* **Applied Regression & Tabular Modeling:** Feature engineering, data normalizations, and predictive modeling on structured datasets (`westeros_records.csv`).

### 5. HW5: Markov Decision Processes (MDP), Q-Learning & SARSA
Implementing decision-making frameworks in stochastic environments:
* **Markov Decision Processes (`MDP.ipynb`):** Applying Value Iteration and Policy Iteration algorithms by iteratively computing the Bellman optimality equations over discrete state spaces.
* **Model-Free Reinforcement Learning (`qlearning_sarsa.ipynb`):** Implementing **Q-Learning** (off-policy TD control) and **SARSA** (on-policy TD control) agents to autonomously learn optimal policies through environmental trial, error, and reward shaping:

> **Q(s, a) ← Q(s, a) + α · [ r + γ · max Q(s', a') − Q(s, a) ]**

---

## 📊 Continuous Assessment (Quizzes & Exams)

* **Quizzes (`Quiz/1` to `Quiz/6`):** Six rapid-assessment problem sets covering mathematical derivations of probability distributions, admissibility proofs for heuristics, neural network backpropagation mechanics, and logic propositions.
* **Midterm & Final Examinations (`exams/`):** Rigorous theoretical evaluations synthesizing graph search theory, computational complexity, constraint satisfaction mathematics, and statistical learning theory.

---

## 🛠️ Tech Stack & Prerequisites

The algorithmic implementations across this repository utilize Python 3.12+ and core scientific computing libraries:

* **Core Language & Runtime:** Python 3.12, Jupyter Notebooks (`.ipynb`)
* **Numerical Linear Algebra:** `NumPy` (vectorized matrix computations, gradient calculations)
* **Data Manipulation & Ingestion:** `Pandas` (tabular data processing for bioinformatics and financial datasets)
* **Visualization & Diagnostics:** `Matplotlib`, `Seaborn` (plotting learning curves, state-space explorations, and decision boundaries)
* **Baseline Benchmarking:** `Scikit-learn`, `SciPy` (used strictly for preprocessing and performance comparison against custom-built models)

To set up the local development environment:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

---

## 🇮🇷 Persian Summary for Students (راهنمای فارسی)

<details>
<summary><strong>کلیک کنید: معرفی دقیق ساختار مخزن و تمرین‌های عملی هوش مصنوعی برای دانشجویان</strong></summary>

<br>

### درباره این ریپازیتوری
این مخزن (Repository) یک آرشیو جامع، سطح بالا و کاملاً اصولی از تمرین‌های عملی (Practical)، پاسخ‌های تحلیلی (Theoretical)، کوئیزها (۶ سری) و امتحانات درس **هوش مصنوعی (Artificial Intelligence)** است. نقطه قوت اصلی این مخزن، **پیاده‌سازی الگوریتم‌های یادگیری ماشین و هوش مصنوعی از پایه (From Scratch)** به زبان پایتون است.

### معرفی دقیق پروژه‌ها و پوشه‌ها براساس ساختار واقعی
* **پوشه `Hws/1/` (جستجوی آگاهانه و ناآگاهانه):** پیاده‌سازی و مقایسه الگوریتم‌های BFS، DFS، IDS و طراحی هیوریستیک‌های بهینه برای الگوریتم *A.
* **پوشه `Hws/2/` (بازی رقابتی و ارضای محدودیت CSP):**
  * پیاده‌سازی عامل هوشمند بازی دوز (`Tic-Tac-Toe.ipynb`) با استفاده از الگوریتم **Minimax و هرس آلفا-بتا (Alpha-Beta Pruning)**.
  * حل‌کننده پازل تصویری **Nonogram** (`CSP_Nonogram_Student.ipynb` و `models.py`) با طراحی شیءگرا، الگوریتم Backtracking، هرس دامنه و مکانیزم Forward Checking.
* **پوشه `Hws/3/` (مدل‌های احتمالی و فرآیندهای تصادفی):**
  * تحلیل احتمالی داده‌های مالی بازار (`fmapp.ipynb`) با استفاده از شبکه‌های بایزی (Bayesian Networks).
  * پیاده‌سازی مدل‌های پنهان مارکوف (HMM) برای تحلیل و رمزگشایی توالی‌های بیوانفورماتیک و DNA (`hmm_dna.ipynb`).
* **پوشه `Hws/4/` (پیاده‌سازی ماشین لرنینگ از پایه):** یکی از مهم‌ترین بخش‌های رزومه‌ای مخزن در فایل `ml_core.ipynb`؛ شامل کدنویسی کامل و بدون استفاده از Scikit-Learn برای مدل‌های **درخت تصمیم (Decision Tree)** (با محاسبه آنتروپی و شاخص جینی) و **جنگل تصادفی (Random Forest)** با مکانیزم Bagging.
* **پوشه `Hws/5/` (یادگیری تقویتی و MDP):** پیاده‌سازی تکرار ارزش و سیاست در فرآیند تصمیم‌گیری مارکوف (`MDP.ipynb`) و کدنویسی عامل‌های یادگیری تقویتی **Q-Learning** و **SARSA** در محیط‌های تصادفی (`qlearning_sarsa.ipynb`).
* **پوشه‌های `Quiz/`، `exams/` و `slides/`:** آرشیو کامل ۶ کوئیز ارزیابی مستمر، سوالات و پاسخنامه‌های میان‌ترم و پایان‌ترم، و ۲۷ جلسه اسلاید کامل تدریس درس.

### اهمیت برای رزومه مهندسی نرم‌افزار و اپلای
کدنویسی تمیز شیءگرا در حل‌کننده Nonogram و پیاده‌سازی ریاضیاتی الگوریتم‌های Decision Tree و Q-Learning بدون وابستگی به کتابخانه‌های آماده، نشان‌دهنده درک عمیق محاسباتی است که یکی از کلیدی‌ترین معیارها در ارزیابی رزومه مهندسان و پژوهشگران هوش مصنوعی به شمار می‌رود.
</details>

---

## 📄 License & Author

This repository is open-source and released under the [MIT License](LICENSE). Feel free to explore the implementations and use them as study references for algorithmic Artificial Intelligence and Machine Learning.

<div align="center">
  <sub>Developed and maintained with precision by <b>M. Mahdi Moradi</b> (@mahdi0x06).</sub>
</div>
