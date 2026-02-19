# USDA Text Database for LLM Training

## Purpose

This repository contains a curated text database based on USDA Priority Pest information. The data is sourced from official pest documentation and is intended to support:

- **Fine-tuning** Large Language Models (LLMs) on pest-related agricultural knowledge
- **Retrieval-Augmented Generation (RAG)** pipelines that require domain-specific context about priority pests

The repository provides both PDF and DOCX versions of pest fact sheets, making it easy to extract structured text for various NLP and ML workflows.

## Insects / Pests Covered

The following insects and pests are currently included in this database:

1. *Ips sexdentatus* (Six-toothed bark beetle)
2. Asian citrus psyllid (*Diaphorina citri*)
3. Citrus longhorned beetle (*Anoplophora chinensis*)
4. Cotton cutworm (*Spodoptera litura*)
5. Emerald ash borer (*Agrilus planipennis*)
6. Large pine weevil (*Hylobius abietis*)
7. Red palm weevil (*Rhynchophorus ferrugineus*)
8. Red ring nematode (*Bursaphelenchus cocophilus*)
9. Redheaded pine sawfly (*Neodiprion lecontei*)

## Data Files

| Format | Location |
|--------|----------|
| PDF    | `pdf files/` |
| DOCX   | `docx files/` |

## Future Data

A **JSONL file** containing Question & Answer (QA) pairs derived from these pest documents is planned and will be made available in a future update for direct use in LLM fine-tuning and evaluation workflows.

## Disclaimer: This data is currently under review and should be considered as draft information. Please verify all details independently before use. Use of this information is at your own risk.
