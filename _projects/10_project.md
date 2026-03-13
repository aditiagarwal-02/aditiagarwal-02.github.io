---
layout: page
title: What’s the SoTA – Autonomous Deep Research Agent
description: A multi-agent system that automates literature reviews to discover research gaps and surface the state of the art.
img: assets/img/project_sota_agent.png
importance: 10
category: personal
# github: https://github.com/your-username/sota-agent  # uncomment and update when public
---

# Project Description

“What’s the SoTA” is an autonomous deep research agent designed to continuously track and summarize the state of the art in a given topic. It orchestrates multiple agents to: parse PDFs, extract structured knowledge, detect conflicting claims, and iteratively refine its understanding of a research area.

The system is built using LangGraph and DeepSeek-R1 and runs primarily on local artifacts so that large batches of PDFs can be explored offline. It is backed by a high-fidelity PDF-to-Markdown pipeline and a vector store, enabling rich, citation-aware answers instead of generic text summaries.

## Visual Overview

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/project_sota_agent.png" title="Autonomous research agent architecture" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
      Conceptual architecture of the SoTA agent: PDFs flow through a PDF-to-Markdown pipeline, populate a vector store, and are analyzed by a LangGraph-based multi-agent system that surfaces research gaps and reconciles conflicting results.
    </div>
  </div>
</div>

> Tip: add an architecture diagram or abstract agent illustration at `assets/img/project_sota_agent.png` so the project card has a strong, visual thumbnail.

## Technical Highlights

- Engineered a multi-agent system in LangGraph and DeepSeek-R1 to autonomously traverse, summarize, and cross-reference academic literature.  
- Implemented a self-correction loop that flags conflicting empirical results and triggers targeted re-search to resolve discrepancies.  
- Built a robust PDF-to-Markdown pipeline using Marker and ChromaDB for semantic retrieval across 1,000+ local research papers.  
- Designed query workflows that move from high-level mapping (surveys, taxonomies) to fine-grained question answering with explicit citations.  
- Supports topic tracking over time (e.g., “How have rectified flows evolved since 2022?”) using time-aware filtering and snapshot comparisons.

