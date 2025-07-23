# Agent-Guided Ad Generation
**Personalizing Promotional Content with LLMs**  
Team 6: Robert Hortua Leal, Zhenziye Lin

---

## 🌟 Project Overview

In the era of behavioral targeting and personalized marketing, AI-driven advertising plays an increasingly critical role in influencing consumer decisions. Large Language Models (LLMs) now make it possible to automatically generate tailored advertisements based on a user's behavior, profile, or even a few lines of input.

This project builds a lightweight agent-guided text generation system that creates short, personalized advertisements using LLMs like GPT-3.5 or Mistral. Inspired by Agentic AI, we simulate simple agent-like logic to dynamically tailor ad copy for different user personas.

---

## 🧠 Motivation

This project is a natural extension of our seminar on behavioral targeting and dynamic pricing.

- **Zhenziye Lin** explores how AI systems understand user behavior and personalize content, combining business and CS perspectives.
- **Alex** is passionate about how AI agents can empower startups and local businesses with personalized marketing—democratizing access to powerful ad tools.

---

## 🛠️ Scope of the Project

We aim to:

- 🎯 Generate ad copy using LLMs based on product, tone, and user mood.
- 🤖 Simulate simple agent-like logic (e.g., adapt tone for budget-conscious users).
- 📝 Use prompt engineering to design ad styles: **luxury**, **playful**, **minimalist**.
- 🔬 Compare model outputs with different tones and sampling parameters.

---

## 🗓️ Milestone Timeline

### ✅ Week 1: Project Setup & Research
- Define features: input types, ad styles, tone variations.
- Evaluate LLM options: GPT-3.5 (OpenRouter), Mistral, HuggingFace.
- Choose stack: Python, Gradio/Streamlit for UI.
- Set up GitHub repo & file structure.
- Draft initial prompt templates.

### ✅ Week 2: Core LLM Integration
- Integrate one LLM API (e.g., GPT-3.5 or Mistral).
- Build basic generation pipeline (input → prompt → output).
- Add temperature, top-p controls.
- Test tone variations: playful, luxury, minimalist.

### ✅ Week 3: Agent-Like Personalization Logic
- Build persona handler (mood, behavior, brand tone).
- Create dynamic prompt wrappers.
- Simulate behavior (e.g., if budget-conscious → minimalist tone).
- Expand tone-persona combinations.

### ✅ Week 4: UI, Testing & Demo
- Develop frontend with Gradio/Streamlit.
- Allow user selection of tone, mood, product type.
- Run model comparison experiments.
- Prepare final presentation and demo.

---

## 📦 Tech Stack

- **Language Models**: GPT-3.5 (via OpenRouter), Mistral
- **Frontend**: Streamlit / Gradio
- **Backend**: Python
- **APIs**: OpenRouter, HuggingFace
- **Version Control**: GitHub

---

## 🔮 Future Work

- Expand agent logic to include learning from feedback.
- Add multilingual ad generation support.
- Explore full agent autonomy for real-time campaign adaptation.

---

## 📄 License

MIT License

---

## 🙌 Acknowledgments

This project was developed as part of CS7180: Generative AI coursework.
