---
permalink: /research/
title: "Research Experiences"
author_profile: true
redirect_from:
  - /research/
  - /research.html
---

### Diffusion Guided Language Modeling

**Research Assistant @ Prof. Kilian Weinberger's Lab**  
_Ithaca, NY_ | _Oct 2023 - May 2024_

- Developed a novel framework using diffusion that combines the strengths of auto-regressive language models and diffusion models to improve controllable text generation while maintaining the fluency of auto-regressive models and the flexibility of diffusion models.
- Independently constructed classifiers, including training logistic regression and multi-layer perceptron models with residual connections. This lightweight classifier allows plug-and-play guidance for diffusion.
- Evaluated the perplexity, MAUVE Score, and diversity of generated text with different levels of prefix guidance.

---

### Retrospective Learning from Interactions

**Research Assistant @ Prof. Yoav Artzi's Lab**  
_New York, NY_ | _May 2023 - Nov 2023_

- Built MultiRef, a referencing game with multiple tangram images, where the speaker uses language to guide the listener to correctly select the target tangrams within a few turns of interactions.
- Developed an interactive web interface for the "multiple-reference game" using Empirica (React + MongoDB), featuring functionalities like lobby formation, game initiation, and bonus calculations.
- Analyzed linguistic features from speakers' messages and trained multi-modal models to participate as a listener (and later a speaker) using implicit reasoning from human feedback during interaction.
- Deployed RESPECT as a listener in this scenario, decoding implicit feedback from past interactions to improve task completion rate from 31% to 82%, all without any external annotation.

---

### Semantic Change Replication Study

**Research Assistant @ Prof. Lillian Lee's Lab**  
_Ithaca, NY_ | _Sep 2024 - Present_

- Replicated experiments of "Statistically significant detection of semantic shifts using contextual word embeddings" by Liu et al. (2021), following methods of Martinc et al. (2019).
- Fine-tuned BERT on the LiverpoolFC dataset and extracted embeddings for words from two different time ranges (13 and 17) respectively.
- Compared semantic shifts and implemented permutation studies to confirm statistical significance.

---

### Unfactual Outputs Related to Word Co-occurrence Frequency

**Research Assistant @ Prof. Tanya Goyal's Lab**  
_Ithaca, NY_ | _Sep 2024 - Present_

- Examined unfactual outputs from Factscore labeled data and hypothesized a relationship to commonly associated words in the training data (examining Wikipedia text).
- Identified frequent words for occupations in Factscore as features and calculated feature correlation changes from Wikipedia text to generated outputs.
- Simulated synthetic data to confirm correlation changes.

---

### IOLing Problems Dataset and Benchmark

**Research Assistant @ Prof. Yoav Artzi's Lab**  
_New York, NY_ | _May 2024 - Jul 2024_

- Independently developed a novel dataset featuring International Olympiad of Linguistics problems to benchmark LLMs on inductive reasoning and generalization capabilities, especially in low-resource languages.
- Designed and implemented algorithms to generate linguistic data based on IPA permutations, ensuring sound features were preserved while creating new, scalable problem sets.
- Conducted experiments with GPT-4, LlaMA, Claude, and Bard, evaluating their performance on complex linguistic tasks, and refined model interaction strategies to enhance consistency and hypothesis testing.

---

### Probing Vision and Language Models

**Research Assistant @ Prof. Yoav Artzi's Lab**  
_New York, NY_ | _Jul 2024 - Aug 2024_

- Investigated biases towards text tokens over image tokens in multimodal vLLMs, focusing on the underutilization of image tokens and exploring the dynamics of information flow within these models.
- Implemented methods to visualize various kinds of attention maps for PaliGemma and LlaVA Next, experimenting with the complexity of sentences and images in the NLVR task.
- Explored positional bias, commonly found in LLMs, and experimented with metrics other than attention to show token contributions.
