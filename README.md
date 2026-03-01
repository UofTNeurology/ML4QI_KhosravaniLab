# ML4QI Lab -- [Stroke Innovation Lab](https://strokeinnovationlab.ca/)

**Machine Learning for Quality Improvement in Neurology and Stroke Care**
PI: Dr. Houman Khosravani, MD PhD FRCPC | Division of Neurology, University of Toronto | Sunnybrook Health Sciences Centre

---

## Mission

The ML4QI Lab applies machine learning to elevate quality improvement in acute stroke care and neurology. We specialize in **Sonic Diagnosis** -- using voice as a biomarker through deep learning and spectral analysis of audio signals to transform clinical assessments at the bedside.

---

## Research Areas

### ML4QI: Machine Learning for Quality Improvement

Our core research leverages machine learning to enhance standards of care in the inpatient stroke setting. With support from T-CAIREM and Sunnybrook Health Sciences Centre, we develop AI-driven tools using bedside physiologic recordings.

#### Project MASA (Machine Learning Assisted Swallowing Assessment)

**Dysphagia** is one of the most common and dangerous complications of acute stroke. MASA applies ML to voice biomarkers during swallowing assessments to improve screening accuracy and efficiency:

- Spectral analysis (Mel spectrograms, Superlet transforms) of voice recordings
- CNN-based classification (DenseNet) aligned with the TOR-BSST screening protocol
- Published in **Frontiers in Neuroscience** (2023): [masa-open-source](https://github.com/UofTNeurology/masa-open-source)
- "Analysis of Audio Classifier Performance in Clinical Settings with Limited Data" -- **CHIL 2024**, NYC ([arXiv:2402.10100](https://arxiv.org/abs/2402.10100))

#### Pal-MASA (2025)

Expanding ML-based dysphagia screening **beyond stroke** to all clinical settings. Funded by AFP MD Funding. Applying voice analysis to detect swallowing impairment regardless of underlying etiology.

#### Contrastive Learning for Audio Classification

Implementation of SoundCLR contrastive learning framework for audio signal classification, building transferable methodology for clinical voice diagnostics. See [contrastive_learning_torch](https://github.com/UofTNeurology/contrastive_learning_torch).

#### SEE-2-SOUND

Spatial audio generation from visual media using generative AI. Accepted to **SIGGRAPH 2025**. Applications for patients with vision loss. Led by Rishit Dagli. ([arXiv:2406.06612](https://arxiv.org/abs/2406.06612))

---

### Stroke Resuscitation and Simulation

We originated the concept of **stroke resuscitation** and pioneered the application of resuscitation science to acute stroke care:

- **Protected Code Stroke** -- developed during COVID-19, integrated into national/international guidelines, >47,000 downloads from AHA *Stroke*
- **Crisis Resource Management (CRM) in Stroke** -- first reframing of CRM for stroke care
- **Neurovascular Resuscitation** -- applying medical and trauma resuscitation principles to stroke, reinstating the "code" in code stroke
- **Zero Point Survey (STEP Framework)** -- structured code stroke activation and team workflow

#### Simulation Program

We run an **active code stroke simulation program** using CRM principles and a pit crew model:
- Team communication and role clarity training
- Door-to-needle and door-to-puncture time optimization
- Hot debriefing and continuous performance improvement
- Human factors in high-stakes neurovascular emergencies

#### NICE (Neurovascular Innovations CollaborativE)

Co-founded in 2023 by Dr. Khosravani and Dr. Christine Hawkes to advance neurovascular care education through simulation and innovation.

---

### Palliative Care in Acute Stroke

Developing evidence-based protocols for **routine integration of palliative care** into acute stroke treatment, expanding the confluence of palliative medicine and stroke care.

---

## Lab Members

### 2025-2026

| Member | Role | Institution | Focus |
|--------|------|-------------|-------|
| Dr. B. Tilley | PGME Neurology | U of T | LLMs in EHRs |
| Dr. E. Adegunna | PGME Neurology | U of T | Palliative Care, Pal-MASA |
| D. Ahmed | UGME | U of T Medicine | QI in Neurology |
| R. Saab | Medical Student | U of T Medicine | MASA |
| Dr. A. Balachandar | PhD Candidate (Independent Investigator & Collaborator) | U of T Neurology | MASA |

### 2024-2025

| Member | Role | Institution | Focus |
|--------|------|-------------|-------|
| Dr. A. Balachandar | Movement Disorders Fellow / PhD Candidate | U of T Neurology | MASA |
| R. Saab | Medical Student | U of T Medicine | MASA |
| E. Nashnoush | MSc Data Science | U of T / Sunnybrook / T-CAIREM | MASA |
| H. Mahdi | Medical Student | Western University | MASA |
| R. Dagli | Computer Science (NVIDIA Fellow, T-CAIREM 2024 Award) | U of T | ML4QI, MASA, SEE-2-SOUND |
| Dr. B. Tilley | PGME Neurology | U of T | LLMs in EHRs |
| Dr. E. Adegunna | PGME Neurology | U of T | Palliative Care, Pal-MASA |
| D. Ahmed | UGME | U of T Medicine | QI in Neurology |
| R. Wu | UGME | U of T Medicine | LLMs in Neurology |
| G. Khalaf | CREMS | U of T | MASA |

### 2023-2024
Dr. B. Sivanandan (Palliative Care), Dr. M. Mahendiran (Family Medicine)

### 2022-2023
M. Panchal (CREMS)

---

## Repositories

| Repository | Description |
|------------|-------------|
| [masa-open-source](https://github.com/UofTNeurology/masa-open-source) | ML-Assisted Swallowing Assessment for dysphagia screening |
| [contrastive_learning_torch](https://github.com/UofTNeurology/contrastive_learning_torch) | Contrastive learning for audio classification |
| [UofTNeurology.github.io](https://github.com/UofTNeurology/UofTNeurology.github.io) | Lab website ([strokeinnovationlab.ca](https://strokeinnovationlab.ca)) |

---

## Affiliations

- Division of Neurology, University of Toronto
- Sunnybrook Health Sciences Centre / Sunnybrook Research Institute
- T-CAIREM (Toronto Centre for AI in Research, Ethics and Medicine)
- Neurology Quality and Innovations Lab (NQIL)

---

## Student Recruitment

We accept approximately 1 T-CAIREM student and 1 additional student (via SRI or CREMS) per year. Seeking students with QI/research experience, or engineering/CS/MD backgrounds interested in clinical applications of machine learning in neurology.

Contact: houman [at] neurovascular [dot] ca

---

## Disclaimer

This repository is for educational and research purposes only and does not represent expert medical judgment or assessment. The tools and information provided are not intended for clinical use and should not be relied upon for medical decision-making. No duty of care is assumed by the contributors. The views expressed do not reflect the official stance of any affiliated academic institutions or hospitals.
