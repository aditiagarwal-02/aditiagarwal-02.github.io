---
layout: page
title: Project Dwiti – Localized Multimodal Digital Twin
description: Fine-tuning a VLM on personal multimodal archives to build a private, on-device digital twin.
img: assets/img/project_dwiti.png
importance: 9
category: personal
# github: https://github.com/your-username/project-dwiti  # uncomment and update when public
---

# Project Description

Project Dwiti is a localized multimodal digital twin built on top of a vision–language model. The goal is to create a private, on-device assistant that understands years of personal data—emails, photos, videos, and authored documents—without ever sending raw content to the cloud.

The system fine-tunes Qwen 2.5-VL on a multi-year archive of personal data using parameter-efficient techniques (via Unsloth), compressing VRAM usage by ~29% and enabling experimentation on commodity GPUs. It then exposes a retrieval-augmented interface for search, reflection, and question answering over a person’s life log.

## Visual Overview

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/project_dwiti.png" title="Project Dwiti overview" class="img-fluid rounded z-depth-1" %}
    <div class="caption">
      High-level view of Project Dwiti: personal archives (email, images, video, documents) are embedded, indexed, and fed into a fine-tuned multimodal model that powers a private digital twin interface.
    </div>
  </div>
</div>

> Tip: place a custom illustration or architecture diagram for the project at `assets/img/project_dwiti.png` to replace the placeholder thumbnail.

## Technical Highlights

- Fine-tuned Qwen 2.5-VL on a heterogeneous personal dataset spanning email threads, photos, videos, and authored documents.  
- Used Unsloth-style efficient fine-tuning to reduce VRAM requirements by ~29%, enabling local experimentation on smaller GPUs.  
- Designed a multimodal retrieval pipeline that unifies text, image, and metadata embeddings into a common vector space.  
- Implemented guardrails and redaction rules so that sensitive entities (e.g., phone numbers, addresses) are never surfaced directly in responses.  
- Built an interactive interface for temporal browsing (by year, event, or topic) and reflective prompts (e.g., “What did I learn about diffusion models this year?”).

