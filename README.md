
# Enhancing Generative AI Output on Rare Diseases

This repository contains the research paper and presentation slides for the project:

**"Enhancing Generative AI Output on Rare Diseases: Development of a Database for Retrieval-Augmented Generation System"**  
Presented at an international conference by Teppei Okazaki, Toyofumi Fujiwara, and Atsuko Yamaguchi (Tokyo City University, DBCLS ROIS).

---

## 📄 Contents

```
📁 paper/
   └── iiai2025_okazaki.pdf     # Full paper PDF

📁 slides/
   └── Presentation.pdf         # Conference presentation slides
```

---

## 🧠 Overview

This study addresses the challenge of improving generative AI output quality in the field of rare diseases. It proposes a Retrieval-Augmented Generation (RAG) system combined with a curated rare disease database to support more accurate, current, and comprehensive responses from language models (LLMs) like GPT-4o.

---

## 🔁 System Flow

1. User inputs a disease name.
2. System retrieves relevant PubMed articles from the database.
3. Articles are sorted by evidence tier.
4. Top articles are passed to the GPT-4o via OpenAI Assistant API.
5. GPT-4o generates a structured explanation of the disease.
6. Output is evaluated on:
   - Correctness
   - Comprehensiveness
   - Currentness

---

## 📊 Results Summary

- 38 rare diseases tested.
- RAG-based GPT-4o outperformed standard GPT-4o in **31/38** cases.
- Especially strong in **comprehensiveness** and **currentness**.

---

## 🚧 Limitations & Future Work

- ✖ GUI/web interface not yet implemented (currently CLI-based).
- ✖ Literature limited to PubMed 2023 data.
- ✖ No symptom-based input or interactive medical interview features.
- ✖ Evaluation bias due to LLM-based grading.
- ✔ Plan to expand the database and system usability.

---

## 📚 Citation

```
@inproceedings{okazaki2025enhancing,
  title={Enhancing Generative AI Output on Rare Diseases: Development of a Database for Retrieval-Augmented Generation System},
  author={Okazaki, Teppei and Fujiwara, Toyofumi and Yamaguchi, Atsuko},
  year={2025},
  booktitle={International Conference on Artificial Intelligence and Applications}
}
```

---

## 📝 License

This repository is for academic sharing only. For reuse or distribution, please contact the authors.

---

## 🔗 Contact

- Teppei Okazaki: g2581412@tcu.ac.jp
- Atsuko Yamaguchi: atsuko@tcu.ac.jp
- Toyofumi Fujiwara: fujiwara@dbcls.rois.ac.jp
