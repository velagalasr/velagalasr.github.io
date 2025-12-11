---
title: Failure Claims Assessment
type: project
draft: false
featured_image: ""
summary: "Small Language Model fine-tuned for specialized tasks"
weight: 2
authors: []
show_authors: false
show_date: false
show_reading_time: false
show_related: false
show_comments: false
hide_image: true
---

An AI-powered web application that analyzes equipment failure claims and generates detailed assessments using a fine-tuned GPT-2 Large language model. Built with Python and Streamlit, the system leverages PEFT (Parameter-Efficient Fine-Tuning) with LoRA adapters to provide intelligent claim analysis while maintaining a small model footprint (~10-20MB adapters). The model was trained on 3,000 synthetic claims covering various equipment types, failure modes, and scenarios. Deployed on Hugging Face Spaces with Docker, demonstrating end-to-end ML workflow from data generation and model training to production deployment. Technologies: Python, Transformers, PEFT/LoRA, Streamlit, Docker, Git LFS, Hugging Face Spaces.

## Demo 
https://velagalasr-failure-claims-assessment.hf.space
<iframe
	src="https://velagalasr-failure-claims-assessment.hf.space"
	frameborder="0"
	width="950"
	height="850"
></iframe>
