# Dynamic Survey Framework

**Agentic AI framework for continuously maintaining survey papers as living documents.**

This repository accompanies the paper  
**Agentic AI-Empowered Dynamic Survey Framework**, which reframes survey writing as a long-horizon maintenance problem rather than a one-time generation task.

---

## 📘 Overview

Survey papers play a central role in synthesizing scientific knowledge, yet they rapidly become outdated as new research appears. This often leads to redundancy, fragmentation, and the proliferation of highly overlapping surveys.

We propose treating surveys as **living documents** that evolve over time. Instead of regenerating surveys from scratch, our framework incrementally integrates new research into an existing survey while preserving its structure, scope, and writing style.

The Dynamic Survey Framework uses a collection of specialized, agentic components to:
- analyze newly published papers,
- decide whether they belong in a survey,
- determine *where* they should be integrated, and
- perform conservative, localized updates that minimize unnecessary disruption.


<p align="center">
  <img src="assets/framework_overview.png" width="800">
</p>

<p align="center">
  <em>Overview of the agentic Dynamic Survey Framework. Incoming papers are analyzed,
  routed, and conservatively integrated into an existing survey.</em>
</p>

---

## 🔑 Key Ideas

- **Surveys as persistent document states**  
  Surveys are maintained over time rather than regenerated.

- **Agentic decomposition**  
  Analysis, abstention, routing, and synthesis are handled by specialized agents.

- **Conservative updates**  
  Changes are localized to relevant sections; unrelated content remains untouched.

- **Abstention as a first-class outcome**  
  Papers can be explicitly rejected to avoid forced or low-value updates.

- **Structure preservation**  
  Survey structure is frozen during automated maintenance to prevent drift.

---

## 🛣️ Roadmap

🚧 *Code and data are currently being prepared for release.*

Planned contents include:

- Reference implementation of the Dynamic Survey Framework
- Modular agent implementations:
  - Paper analysis agent
  - Abstention agent
  - Section routing agent
  - Table routing agent
  - Text and table synthesis agents
- Retrospective survey maintenance benchmark
- Evaluation scripts for:
  - update quality
  - semantic alignment
  - local coherence
  - disruption and edit locality
- Example pipelines for maintaining real survey papers
- Documentation and usage tutorials

---

## 🚧 Status

This repository currently serves as a project page for the arXiv preprint.  
The initial public release of code and benchmarks will follow soon.

---

## 📄 Paper

**Agentic AI-Empowered Dynamic Survey Framework**  
arXiv: *to appear*

A BibTeX entry will be added once the arXiv identifier is available.

---

## 📌 Citation

If you find this work useful, please cite the paper:

```bibtex
@article{mumcu2026dynamicsurvey,
  title   = {Agentic AI-Empowered Dynamic Survey Framework},
  author  = {Mumcu, Furkan and Bekit, Lokman and Jones, Michael J. and Cherian, Anoop and Yilmaz, Yasin},
  journal = {arXiv preprint},
  year    = {2026}
}
