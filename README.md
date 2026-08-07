<!-- =========================================================
     ALHARETH AL-DAHIYA — GITHUB PROFILE
     Engineering Portfolio · Systems · AI · Computer Vision
========================================================== -->

<div align="center">

# Alhareth Al-Dahiya

### Information Technology Student · Software Engineering · AI & Computer Vision

**I learn systems by understanding them, designing them, building them, and measuring them.**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/Alhareith)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/%D8%A7%D9%84%D8%AD%D8%A7%D8%B1%D8%AB-%D8%A7%D9%84%D8%AF%D8%A7%D9%87%D9%8A%D8%A9-95b4a831a)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge\&logo=huggingface\&logoColor=black)](https://huggingface.co/Alhareth7790)

</div>

---

## 01 — About

I am an **Information Technology student** focused on understanding how software systems and intelligent systems are designed, built, evaluated, and evolved.

My interests have gradually moved beyond writing code toward the engineering questions behind the code:

* How should a problem be defined before implementation?
* How should requirements become a system architecture?
* Where should complexity exist — and where should it not?
* How should data move through a system?
* How do we measure whether a system actually works?
* How can a prototype evolve into a maintainable product?

My current technical direction sits at the intersection of:

**Software Engineering × System Design × Artificial Intelligence × Computer Vision × Document AI**

> [!IMPORTANT]
> I am more interested in understanding **why a system is designed a certain way** than simply learning another framework.

---

## 02 — Engineering Direction

My development is organized around three connected layers.

<table>
<tr>
<td width="33%" valign="top">

### 🏛️ Software Engineering

* Requirements Engineering
* System Analysis
* Software Architecture
* Modular Design
* Separation of Concerns
* API & Client/Server Concepts
* Databases
* Git & Collaborative Workflows

</td>

<td width="33%" valign="top">

### 👁️ AI & Computer Vision

* Digital Image Processing
* Computer Vision
* Object Detection
* OCR
* Document AI
* Synthetic Data
* Dataset Curation
* Model Training
* Evaluation & Error Analysis

</td>

<td width="33%" valign="top">

### ⚙️ System Foundations

* Operating Systems
* Computer Networks
* Algorithms & Data Structures
* Programming Languages
* Data Flow
* Performance
* Reliability
* Engineering Trade-offs

</td>
</tr>
</table>

---

# 03 — Selected Projects

These are the projects that best represent the direction I am currently developing.

---

## 01 / Tibetan OCR & Document AI

### `Historical Tibetan Document Recognition`

**Status:** Active Research & Development

A computer vision and OCR research project focused on recognizing **printed Old Tibetan/Uchen documents**.

The project is not treated as simply "training an OCR model". It is being designed as a complete engineering pipeline:

```text
Real Documents
      │
      ▼
Data Acquisition & Curation
      │
      ▼
Synthetic Data Generation
      │
      ▼
Preprocessing
      │
      ▼
Layout / Line Detection
      │
      ▼
Text Recognition
      │
      ▼
Evaluation
      │
      ▼
Error Analysis
      │
      ▼
Iterative Improvement
```

### Engineering Focus

* Synthetic dataset generation
* Real-data curation
* Tibetan Uchen typography
* Document preprocessing
* Layout and line detection
* YOLO-based detection/segmentation
* Sequence recognition
* Syllable / grapheme-cluster tokenization
* CER / WER evaluation
* Controlled experimentation
* Real-vs-synthetic data analysis

### Current Architecture Direction

```text
                 DOCUMENT
                     │
                     ▼
        ┌────────────────────────┐
        │ Layout / Line Detection │
        │       YOLO-based        │
        └────────────┬───────────┘
                     │
                     ▼
              Line Cropping
                     │
                     ▼
        ┌────────────────────────┐
        │   Text Recognition      │
        │     CRNN / TrOCR        │
        └────────────┬───────────┘
                     │
                     ▼
              Tibetan Text
                     │
                     ▼
          Evaluation & Analysis
```

### Core Technologies

`Python` · `PyTorch` · `YOLO` · `OpenCV` · `Pillow` · `Albumentations`

---

## 02 / Human Proctoring Assistant

### `Computer Vision Assistant for Exam Monitoring`

**Status:** Project Development

A computer-vision-based system designed to **assist a human proctor** in identifying potentially suspicious examination behavior.

The objective is not to replace the human decision-maker.

The system is designed around the principle:

> **Computer Vision detects signals; the human makes the final decision.**

### Initial Detection Scope

* Mobile phone detection
* Cheat-sheet / paper detection
* Extreme head-pose estimation

### Engineering Focus

```text
Camera Input
     │
     ▼
Frame Processing
     │
     ├── Phone Detection
     │
     ├── Paper Detection
     │
     └── Head Pose Analysis
              │
              ▼
       Suspicion Signals
              │
              ▼
        Human Review
```

The project therefore combines:

`Computer Vision` · `Object Detection` · `Image Processing` · `Human-in-the-Loop Systems`

---

## 03 / Masar — Adaptive Workflow Management

### `Smart Adaptive Workflow Management`

A broader software-system concept exploring how organizational workflows can become more structured, observable, and adaptable.

The project examines ideas around:

* Workflow modeling
* Process orchestration
* Decision points
* Human tasks
* Automation
* Process state
* Business rules
* System integration

The architectural challenge is deliberately treated as an engineering problem:

> **Do not introduce enterprise-level complexity unless the business problem actually requires it.**

This project is therefore also an exploration of the boundary between:

`Simple Modular Systems → Workflow Engines → Process Orchestration Platforms`

---

## 04 / Interactive Computer Vision & Image Processing Platform

### `Computer Vision Learning & Experimentation Platform`

A long-term direction for building an educational and experimental platform centered around:

* Computer Vision
* OCR
* Image Processing
* Document AI

The intended system goes beyond conventional course content.

The long-term concept includes:

```text
Knowledge
   │
   ├── Concepts
   ├── Algorithms
   ├── Papers
   ├── Books
   ├── Tools
   └── Projects
          │
          ▼
      Interactive Labs
          │
          ▼
      Experiments
          │
          ▼
      AI Assistance
          │
          ▼
      Learning Path
```

The long-term goal is to connect **knowledge, experimentation, projects, and intelligent learning assistance** within one coherent system.

---

# 04 — Technical Foundation

My current stack is intentionally broader than a list of frameworks.

### Languages

`Python` · `C++` · `C#` · `JavaScript` · `HTML` · `CSS` · `SQL`

### AI / Machine Learning

`PyTorch` · `Scikit-learn` · `Pandas`

### Computer Vision

`OpenCV` · `YOLO` · `Albumentations`

### Data & Experimentation

`NumPy` · `Pandas` · `Jupyter` · `Google Colab`

### Software Engineering

`OOP` · `Data Structures & Algorithms` · `REST Concepts` · `Client/Server Architecture` · `Database Design`

### Development Tools

`Git` · `GitHub` · `VS Code` · `Visual Studio`

---

# 05 — What I Am Currently Building

My current learning is not organized around collecting technologies.

It is organized around **capabilities**.

```text
                    ENGINEERING
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
   SOFTWARE            AI / CV        SYSTEMS
   ENGINEERING
        │                │                │
        ▼                ▼                ▼
 Requirements       Data Pipelines   Networking
 Architecture       Image Processing Operating Systems
 APIs               OCR             Performance
 Databases          Detection       Reliability
 Testing            Evaluation      Deployment
        │                │                │
        └────────────────┼────────────────┘
                         ▼
                 COMPLETE SYSTEMS
```

Current areas of deeper study include:

* Software Architecture
* System Design
* Client/Server Architecture
* APIs and Data Flow
* Computer Networks
* Operating Systems
* Digital Image Processing
* Computer Vision
* OCR Architecture
* Dataset Engineering
* Model Evaluation
* Engineering Trade-offs
* Git-based collaboration

---

# 06 — Engineering Principles

> [!NOTE]
> These principles describe how I approach engineering problems, not claims that I have already mastered every area listed above.

### 01 — Understand Before Implementing

A technically impressive solution is still a bad solution if the problem was misunderstood.

### 02 — Architecture Before Complexity

Architecture exists to manage complexity.

It should not become complexity itself.

### 03 — Evidence Over Assumptions

Performance claims should come from measurements.

Model improvements should come from experiments.

Architectural decisions should have reasons.

### 04 — Build Small, Learn Fast

A system should earn its complexity through real requirements.

Start with a coherent foundation and evolve it deliberately.

### 05 — Data Is Part of the System

In AI projects, the model is only one component.

Dataset quality, labeling, preprocessing, evaluation, and error analysis are equally important.

### 06 — Failure Is Information

A failed experiment is useful when it explains something about the system.

### 07 — Document Decisions

Knowing **what** was built is not enough.

A maintainable system should also preserve **why** it was built that way.

---

# 07 — Learning Architecture

My long-term learning path is structured around foundations rather than isolated technologies.

```text
                    SOFTWARE ENGINEERING
                             │
             ┌───────────────┼───────────────┐
             ▼               ▼               ▼
        Requirements     Architecture      Design
             │               │               │
             └───────────────┼───────────────┘
                             ▼
                         Development
                             │
                             ▼
                    Testing & Evaluation
                             │
                             ▼
                     Deployment & Ops


                    ARTIFICIAL INTELLIGENCE
                             │
             ┌───────────────┼───────────────┐
             ▼               ▼               ▼
           Data        Computer Vision      Models
             │               │               │
             └───────────────┼───────────────┘
                             ▼
                       Experiments
                             │
                             ▼
                     Evaluation & Errors
                             │
                             ▼
                        Improvement
```

The goal is not to become dependent on a particular framework.

The goal is to understand the principles well enough to **learn new tools quickly and make sound engineering decisions**.

---

# 08 — Selected Areas of Practice
```
| Area                    | Current Direction                                        |
| ----------------------- | -------------------------------------------------------- |
| Software Engineering    | System design, architecture, requirements, modularity    |
| Artificial Intelligence | Machine learning, model evaluation, experimentation      |
| Computer Vision         | Detection, preprocessing, document analysis              |
| OCR                     | Recognition pipelines, synthetic data, evaluation        |
| Image Processing        | Enhancement, filtering, segmentation, feature extraction |
| Data Engineering        | Dataset construction, preprocessing, curation            |
| Systems                 | Client/server, networking, operating-system foundations  |
| Collaboration           | Git, GitHub, structured workflows and documentation      |
```
---

# 09 — Beyond Tools

Frameworks change.

Libraries change.

Model architectures change.

The engineering fundamentals remain.

What I am deliberately trying to build is the ability to:

* Decompose ambiguous problems.
* Discover and formalize requirements.
* Design systems before implementing them.
* Understand trade-offs instead of following trends.
* Build experiments that answer specific questions.
* Evaluate systems with meaningful metrics.
* Analyze failures instead of hiding them.
* Document architectural decisions.
* Turn knowledge into working systems.

> [!TIP]
> The real objective is not to know more technologies.
>
> It is to become better at **learning, designing, building, evaluating, and improving systems**.

---

# 10 — Long-Term Direction

My long-term direction is toward **software and intelligent systems engineering**, with particular interest in:

```text
Software Engineering
        +
System Architecture
        +
Artificial Intelligence
        +
Computer Vision
        +
Document AI
        +
Research & Experimentation
```

I am especially interested in problems where software engineering and AI meet:

* Intelligent document processing
* OCR systems
* Computer vision pipelines
* Human-in-the-loop systems
* Data-centric AI
* Knowledge and learning systems
* Scalable software platforms

The objective is not to build projects for the sake of having projects.

It is to use projects as increasingly difficult engineering problems through which deeper understanding is developed.

---

<div align="center">

### Understand → Design → Build → Measure → Improve

<br>

**Alhareth Al-Dahiya**

*Software Engineering · AI · Computer Vision · Systems*

</div>
