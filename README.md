# Input Matters: Evaluating Input Structure’s Impact on LLM Summaries of Sports Play-by-Play

**Authors:** Barkavi Sundararajan, Somayajulu (Yaji) Sripada, Ehud Reiter   
**Affiliation:** University of Aberdeen
**Accepted at:** INLG 2025

**[Project Page](https://barkavisj.github.io/nba-input-matters/)** | **[Paper](https://2025.inlgmeeting.org/accepted-papers.html)** | **Poster**

This repository provides the structured NBA play-by-play input data in CSV (row-structured) and hierarchical JSON for the latest season NBA games.

## Overview
A major concern when deploying large language models (LLMs) in accuracy-critical domains such as sports reporting is that the generated text may not faithfully reflect the underlying data. This project quantifies how **input structure** affects hallucinations and other factual errors in LLM-generated summaries of **NBA play-by-play** data. We compare three input formats: **unstructured**, **row-structured**, and **hierarchical JSON**, and evaluate game summaries with a **human error-annotation protocol** spanning seven categories (`NUMBER`, `NAME`, `WORD_OBJECTIVE`, `WORD_SUBJECTIVE`, `CONTEXT`, `NOT_CHECKABLE`, `OTHER`). Across **180 summaries**, we labeled **3,312** errors and found that **structured inputs substantially reduce error rates.**

## Dataset

- Row-structured play-by-play NBA data: [Google Drive link](https://drive.google.com/drive/folders/12WhYIkPkP4MasOU7Dg2k-nr8Kxi5UM_X?usp=sharing)

- JSON-structured play-by-play NBA data: [Google Drive link](https://drive.google.com/drive/folders/1rXU1QeRyjJcI-B1i4RTIDufUU5DT0tXA?usp=drive_link)

## Citation
To be included
