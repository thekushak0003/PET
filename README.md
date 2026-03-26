readme = """# 🎓 Placement Preparation Guide

> A complete, interactive revision suite for campus placements — covering everything from SQL to Case Studies. All guides are self-contained HTML files that run directly in the browser with no dependencies.

---

## 📁 Files in This Repository

| # | File | Topic | Sections |
|---|------|-------|----------|
| 1 | [`sql.html`](./sql.html) | SQL — Basic to Advanced | 22 |
| 2 | [`python.html`](./python.html) | Python — Basic to Advanced | 21 |
| 3 | [`ml.html`](./ml.html) | Machine Learning | 21 |
| 4 | [`consulting.html`](./consulting.html) | Consulting Frameworks | 21 |
| 5 | [`misc.html`](./misc.html) | Data Science Libraries | 23 |
| 6 | [`pm.html`](./pm.html) | Product Management Methodologies | 19 |
| 7 | [`cs.html`](./cs.html) | Case Study Mastery | 25 |
| 8 | [`apti.html`](./apti.html) | Aptitude — Verbal & Non-Verbal | 33 |

---

## 📘 Guide Summaries

### 1. 🗄️ SQL Revision Guide
**File:** `sql.html`

A complete SQL reference from basics to advanced, organized by difficulty level with a dark GitHub-inspired theme.

**Covers:**
- DDL, DML, DCL, TCL commands & SQL execution order
- Data types, Constraints (PRIMARY KEY, FOREIGN KEY, CHECK, UNIQUE)
- SELECT, WHERE, ORDER BY, GROUP BY, HAVING, NULL handling
- All JOIN types (INNER, LEFT, RIGHT, FULL OUTER, CROSS, SELF)
- Subqueries (scalar, correlated, EXISTS, derived tables)
- Set operations (UNION, INTERSECT, EXCEPT)
- String & Date functions, CASE expressions, Views & Indexes
- Normalization (1NF → BCNF), Window Functions (ROW_NUMBER, RANK, LAG, LEAD)
- CTEs & Recursive queries, Stored Procedures, Triggers
- Transactions & ACID properties, Query Optimization
- **Top 7 classic placement interview questions with solutions**

---

### 2. 🐍 Python Revision Guide
**File:** `python.html`

Full Python reference from fundamentals to advanced topics, in a dark GitHub-flavored theme.

**Covers:**
- Core model (interpreted, dynamically typed, GIL, mutability)
- Data types, type conversion, truthiness, LEGB scope
- Strings — all methods, slicing, f-string formatting
- Operators — floor division, walrus `:=`, identity vs equality, integer interning
- Control flow — `for...else`, `while...else`, match statement (3.10+)
- Functions — `*args`, `**kwargs`, keyword-only args, lambdas, type hints
- Lists & Tuples — all methods with Big-O, namedtuples, starred unpacking
- Dictionaries & Sets — `defaultdict`, `Counter`, set algebra
- Comprehensions (list, dict, set, generator), OOP with all dunder methods
- Exception handling, File I/O, Iterators & Generators, `itertools`
- Functional programming — `map/filter/reduce`, `lru_cache`, closures
- Decorators (from scratch, with arguments, `@wraps`)
- Concurrency (GIL, threading, multiprocessing, asyncio)
- Memory management, profiling, DSA in Python
- **Top 5 placement interview questions**

---

### 3. 🤖 Machine Learning Revision Guide
**File:** `ml.html`

Comprehensive ML placement guide covering math foundations through deep learning.

**Covers:**
- ML types, workflow, Bias-Variance tradeoff, parametric vs non-parametric
- Math — Linear algebra (eigenvalues, SVD), Calculus (chain rule, Hessian), Probability (Bayes, MLE, MAP, entropy, KL divergence)
- Data preprocessing — missing values, scaling, encoding, train/val/test splits
- Evaluation metrics — confusion matrix, F1, ROC-AUC, PR-AUC, regression metrics
- Linear Regression (OLS, Ridge, Lasso, Elastic Net)
- Logistic Regression (sigmoid, cross-entropy, softmax)
- Decision Trees (Gini, Entropy, Information Gain)
- Ensemble methods (Bagging, Random Forest, XGBoost, LightGBM, CatBoost)
- SVM (hard/soft margin, kernel trick, RBF)
- KNN, Naive Bayes, Clustering (K-Means, DBSCAN, GMM)
- PCA, t-SNE, UMAP, Dimensionality Reduction
- Neural Networks (backprop, activations, He/Xavier init)
- CNNs (conv arithmetic, ResNet skip connections)
- LSTMs & GRUs (all gates with formulas)
- Transformers (attention math, BERT vs GPT)
- Regularization, Optimization (Adam, AdamW), Loss functions
- Feature engineering & selection, Hyperparameter tuning
- **8 classic interview Q&As**

---

### 4. 💼 Consulting Frameworks Guide
**File:** `consulting.html`

Complete consulting & case interview framework reference with interactive visuals.

**Covers:**
- Structured thinking, Pyramid Principle, SCR storytelling
- MECE principle — examples, splitting approaches, pitfalls
- Issue Trees — Logic Tree vs Issue Tree vs Hypothesis Tree, visual profit decline tree
- Hypothesis-led thinking, 80/20 rule
- SWOT analysis + TOWS Matrix (SO/ST/WO/WT strategies)
- Porter's Five Forces with strength interpretation table
- BCG Growth-Share Matrix (Stars, Cash Cows, Question Marks, Dogs)
- Ansoff Matrix (risk gradient with examples)
- McKinsey 7-S Framework
- Value Chain Analysis (Porter's primary + support activities)
- 4 Ps / 7 Ps Marketing Mix
- STP Framework — segmentation variables, MADS criteria, positioning template
- Product Life Cycle — all 4 stages with strategy implications
- Profitability Framework — full visual tree
- Market Entry Framework — TAM/SAM/SOM, entry modes
- M&A Framework — synergy equation, 6-step evaluation
- Pricing strategies (9 types), PESTLE Analysis
- Case Interview Structure — 4-step format, recommendation template
- Case types & Fermi estimation (top-down vs bottom-up)
- **Top 6 interview Q&As + quick-fire reference**

---

### 5. 📊 Data Science Libraries Guide
**File:** `misc.html`

Hands-on reference for 7 essential data science libraries with syntax-highlighted code examples.

**Covers:**

**NumPy (4 sections)**
- Arrays & creation, indexing/slicing, broadcasting, math & linear algebra

**Pandas (5 sections)**
- Series & DataFrame, loc vs iloc, data cleaning, GroupBy/Merge/Pivot, apply/map/I/O

**Matplotlib (2 sections)**
- Figures & Axes (OO API), all plot types & styling

**Seaborn (2 sections)**
- Statistical plots, themes/palettes, pairplot/clustermap/jointplot/FacetGrid

**Scikit-learn (3 sections)**
- Preprocessing (scalers, encoders, imputers), models & evaluation, Pipeline + GridSearchCV

**NLTK (3 sections)**
- Tokenization, stopwords, stemming vs lemmatisation, POS tagging, NER, VADER sentiment, TF-IDF

**Power BI / Tableau (4 sections)**
- Power BI architecture, Power Query (M language), DAX measures, Tableau essentials, BI concepts & interview Q&A

---

### 6. ⚙️ Product Management Methodologies Guide
**File:** `pm.html`

Complete PM methodologies reference for placements in tech and consulting.

**Covers:**
- Predictive vs Adaptive spectrum, methodology selection guide
- **Agile** — 4 Manifesto values, 12 principles, mindset vs process
- **Scrum** — 3 pillars (TIA), 3 roles (PO, SM, Developers), 3 artifacts, 5 events with timebox durations, sprint cycle, estimation (Planning Poker, Fibonacci), velocity/burndown/burnup, anti-patterns
- **Kanban** — 6 core properties, WIP limits, visual board, Little's Law, Cumulative Flow Diagram
- **Waterfall** — 7 phases with outputs, phase gate reviews, Boehm's Cost of Change curve
- Lean (7 principles, 7 wastes TIMWOOD, Lean Startup)
- SAFe & scaled Agile (LeSS, Nexus, Spotify Model)
- XP, DSDM, Scrumban, PRINCE2
- Roadmaps (Now-Next-Later), backlog hierarchy, user stories (INVEST), personas, JTBD
- OKRs, RICE/MoSCoW/Kano prioritisation, AARRR metrics, North Star Metric
- **Top 8 interview Q&As**

---

### 7. 🎯 Case Study Mastery Guide
**File:** `cs.html`

Complete case study preparation guide for consulting, strategy, and PM roles.

**Covers:**
- What is a case study, evaluation dimensions, where cases appear
- Case types (8) & formats (6: interviewer-led, candidate-led, written, group, AI-led, technical)
- The case mindset — hypothesis-first, breadth before depth, 80/20, answer-first
- The 6-phase universal arc + recommendation template
- Clarifying questions — what to ask, what NOT to ask, reading between the lines
- Framework selection guide (all 8 case types), building custom frameworks
- Synthesis vs summary, handling pushback (3-step response)
- **Deep-dives:** Profitability, Market Entry (TAM/SAM/SOM), Growth Strategy, M&A, Pricing, Operations
- Fermi estimation (top-down + bottom-up worked examples, India reference numbers)
- Case maths — mental calculation shortcuts, key financial formulas
- **4 fully worked cases:** BrewPoint Coffee (profitability), TelcoVision (market entry), Volta Motors EV (pricing), MediCore Hospital (operations)
- Communication & signposting, chart reading (TLDR method), written case structure
- The 12 most common mistakes
- 6-week practice plan + pre-interview checklist
- **Top 8 interview Q&As + quick-fire reference**

---

### 8. 🧠 Aptitude Mastery Guide
**File:** `apti.html`

The most comprehensive aptitude preparation guide covering verbal, non-verbal, logical, and quantitative sections.

**Covers:**

**Overview & Strategy**
- Company-specific focus (TCS, Infosys, Wipro, Cognizant, Accenture, AMCAT)
- 3-Pass exam strategy, time allocation, section-wise quick wins

**Verbal Aptitude (7 topics)**
- Reading Comprehension (7 question types, SQR3 method)
- Vocabulary & Word Power (18 word roots, 24 high-frequency synonyms/antonyms)
- Verbal Analogies (14 relationship types)
- Sentence Completion (signal words, double blanks)
- Error Spotting (10 error types: subject-verb, pronouns, tense, prepositions)
- Para Jumbles & Para Completion (5-step strategy)
- Critical Reasoning (Negation Test for assumptions)

**Non-Verbal Reasoning (8 topics)**
- Number & Letter Series (10 pattern types)
- Figure Analogy (6-property checklist)
- Classification / Odd One Out
- Mirror & Water Images (clock mirror formula)
- Paper Folding & Cutting (2ⁿ holes rule)
- Cubes & Dice (painting formulas, Common Face Method)
- Venn Diagrams (all set formulas)
- Coding-Decoding (7 pattern types)

**Logical Reasoning (5 topics)**
- Directions & Distances (shadow trick)
- Blood Relations (25+ relation chart, family tree method)
- Seating Arrangement (linear vs circular)
- Syllogisms (Venn approach + 5 shortcut rules)
- Statements, Arguments & Conclusions

**Quantitative Aptitude (8 topics)**
- Number System & HCF/LCM (divisibility rules 2–25)
- Percentages (fractions table, speed tricks)
- Profit, Loss & Discount (equal SP trap formula)
- Time, Speed & Distance (harmonic mean trap, train problems)
- Time & Work (LCM method, MDH/W formula)
- Ratio, Proportion & Mixtures (alligation visual method)
- Permutation, Combination & Probability (8 formulas)
- Data Interpretation (4-step strategy, 6 question types)

**Practice & Revision**
- Master Formula Sheet (all formulas, squares to 25, cubes to 15, first 25 primes)
- Mixed Practice Questions (7 questions with full worked solutions)
- Placement Q&A + 12-point night-before checklist

---

## 🚀 How to Use

1. **Clone the repo:**
```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
```

2. **Open any guide directly in your browser:**
```bash
   # On Mac
   open sql_revision_guide.html

   # On Linux
   xdg-open sql_revision_guide.html

   # On Windows
   start sql_revision_guide.html
```

3. **No installation needed** — all guides are self-contained HTML files with zero external dependencies.

---

## 📌 Features

- ✅ **Interactive sidebar** with section navigation
- ✅ **Progress tracker** — colour-coded bar shows visited sections
- ✅ **Dark theme** optimised for long study sessions
- ✅ **Syntax-highlighted code** blocks throughout
- ✅ **Practice questions** with hidden answers
- ✅ **Worked examples** and real interview Q&As
- ✅ **Mobile-responsive** layout
- ✅ **Zero dependencies** — pure HTML/CSS/JS, works offline

---

## 🗺️ Study Roadmap
```
Week 1–2  │ SQL + Python fundamentals
Week 3    │ ML concepts + DS Libraries
Week 4    │ Aptitude (Verbal + Quant + Non-Verbal)
Week 5    │ Consulting Frameworks + Case Studies
Week 6    │ PM Methodologies + Full mock tests
```

---

## 📄 License

This repository is for personal educational use. All content is original study material compiled for placement preparation.

---

<div align="center">
  <sub>Built for placement preparation. Good luck! 🎓</sub>
</div>
"""

with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme)

print("✅ README.md created successfully!")
