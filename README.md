# AgriPestDatabase: A Text Database for LLM Training (USDA Funded Project)

## Purpose

This repository contains a curated text database based on USDA Priority Pest information. The data is sourced from official pest documentation and is intended to support:

- **Fine-tuning** Large Language Models (LLMs) on pest-related agricultural knowledge
- **Retrieval-Augmented Generation (RAG)** pipelines that require domain-specific context about priority pests

The repository provides both PDF and DOCX versions of pest fact sheets, making it easy to extract structured text for various NLP and ML workflows.

## Insects / Pests Covered

The following insects and pests are currently included in this database:

1. Six-toothed bark beetle (*Ips sexdentatus*)
2. Asian citrus psyllid (*Diaphorina citri*)
3. Citrus longhorned beetle (*Anoplophora chinensis*)
4. Cotton cutworm (*Spodoptera litura*)
5. Emerald ash borer (*Agrilus planipennis*)
6. Large pine weevil (*Hylobius abietis*)
7. Red palm weevil (*Rhynchophorus ferrugineus*)
8. Red ring nematode (*Bursaphelenchus cocophilus*)
9. Redheaded pine sawfly (*Neodiprion lecontei*)
10. European Grapevine Moth (*Lobesia botrana*)
11. Pale Cyst Nematode (*Globodera pallida*)
12. Small Brown Planthopper (*Laodelphax striatellus*)
13. Citrus Fruit Borer (*Gymnandrosoma aurantianum*)
14. Coconut Rhinoceros Beetle (*Oryctes rhinoceros*)
15. Giant African Snail (*Lissachatina fulica*)
16. Golden Twin-Spot Moth (*Chrysodeixis chalcites*)
17. New Guinea Sugarcane Weevil (*Rhabdoscelus obscurus*)
18. Oak Splendour Beetle (*Agrilus biguttatus*)
19. Spotted Lanternfly (*Lycorma delicatula*)

## Data Files

| Format | Location |
|--------|----------|
| PDF    | `pdf files/` |
| DOCX   | `docx files/` |

## Future Data

A **JSONL file** containing Question & Answer (QA) pairs derived from these pest documents is planned and will be made available in a future update for direct use in LLM fine-tuning and evaluation workflows.

## Disclaimer: This data is currently under review and should be considered as draft information. Please verify all details independently before use. Use of this information is at your own risk.

## Cite our work:
-- Durak, Yagizhan Bilal, Ahsan Ul Islam, Shahidul Islam, Ashley Morgan-Olvera, Iftekhar Ibne Basith, and Syed Hasib Akhter Faruqui. "AgriPestDatabase-v1. 0: A Structured Insect Dataset for Training Agricultural Large Language Model." arXiv preprint arXiv:2603.22777 (2026). Link: https://arxiv.org/abs/2603.22777
