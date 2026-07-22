---
layout: post
title: "Building Research Compass: A Modular AI Platform for Literature Review"
date: 2026-07-21 10:00:00 +0800
categories: [AI, RAG, Research]
tags: [ai, rag, llm, research, literature-review]
author: pHX
---

Research Compass is an in-progress project I'm building to make literature review less painful. The goal is a modular AI platform that helps with three core steps: **retrieving** relevant papers, **evaluating** their quality and relevance, and **assisting** with synthesis and writing.

## Why I started this

While self-teaching myself about quantum computing, besides of structured materials like IBM Quantum Learning that providing a strong foundation, but deeper exploration of topics like surface code in QEC, parameter optimziation in QKD etc requires engaging with research literatures. Papers are one of the most valuable sources for understanding technical details, following new progress, and building connections between different concepts. However, it is not easy to navigate the rapidly growing volume of quantum computing research, with thousands of new papers published every year alongside foundational papers from earlier work. 

I wanted something that could:
- Pull from multiple sources (arXiv, Semantic Scholar, OpenReview, conference proceedings)
- Filter and rank by relevance to a specific research question
- Summarize, compare, and surface contradictions across papers
- Stay modular so each component can be swapped out as better models appear

## Current architecture (high level)

1. **Document Module** - upload pdfs, text chunking, indexing
2. **Retrieval Module** - semantic search, vector retrieval etc
3. **LLM Module** - one unified interface for LLM
4. **Evaluation Module** - evaluate generated responses based on automated or pre-defined metrics
5. **Memory Module** - store long-term research context (optimization)
6. **Research Notebook** - store user-generated context (like summaries, notes)
7. **Research Intelligence Module** - most important capability (paper comparison, research gap identification, knowledge graph, trend analysis etc)

## Status

This is an in-progress project. I'll share more concrete updates (and code) as components stabilize.

Repo: [github.com/changbai-phu/ResearchCompass](https://github.com/changbai-phu/ResearchCompass)
