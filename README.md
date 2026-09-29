# 🧬 BioPrompt Lab

### Biomedical LLM Prompt Evaluation & Quality Assessment Workspace

BioPrompt Lab is an interactive AI product prototype designed to evaluate prompt strategies for biomedical Large Language Models (LLMs).

The product focuses on a key challenge in biomedical AI applications: **how to improve response quality while reducing hallucination and unsupported scientific claims.**

🌐 **Live Demo:**  
https://mengheguo8-cell.github.io/bioprompt-lab/

---

## 🎯 Product Problem

Large Language Models can generate fluent biomedical answers, but scientific applications require more than fluency.

Common risks include:

- Unsupported biomedical claims
- Hallucinated evidence or citations
- Weak reasoning structure
- Poor distinction between evidence and interpretation
- Inconsistent response quality across prompt strategies

BioPrompt Lab explores how prompt design can influence these dimensions through a structured evaluation workflow.

---

## 💡 Product Solution

BioPrompt Lab provides a lightweight evaluation workspace where users can:

1. Enter a biomedical research question
2. Select a prompt strategy
3. Run a standardized evaluation
4. Compare quality metrics
5. Assess hallucination risk
6. Review an evaluation insight

The goal is to make prompt quality **visible, comparable and measurable**.

---

## 🧠 Prompt Strategies

### Zero-shot

Provides a direct baseline prompt without additional reasoning or evidence constraints.

### Structured Reasoning

Introduces structured instructions to improve logical organization, completeness and interpretability.

### Evidence-aware

Encourages the model to distinguish established evidence from interpretation, acknowledge uncertainty and avoid unsupported citations.

---

## 📊 Evaluation Framework

BioPrompt Lab evaluates prompt strategies across six dimensions:

| Metric | Purpose |
|---|---|
| Scientific Accuracy | Measures scientific correctness |
| Evidence Awareness | Assesses evidence-grounded reasoning |
| Completeness | Evaluates coverage of relevant information |
| Reasoning Structure | Measures organization and logical clarity |
| Citation Safety | Assesses risk of unsupported references |
| Overall Score | Provides a combined quality indicator |

The interface also displays a **Hallucination Risk** indicator.

---

## 🔄 Product Workflow

```text
Biomedical Question
        ↓
Prompt Strategy Selection
        ↓
Run Evaluation
        ↓
Six-Dimension Quality Assessment
        ↓
Hallucination Risk
        ↓
Evaluation Insight
