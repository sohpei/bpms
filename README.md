# The Language of Interoception: Examining Embodiment and Emotions Through a Corpus of Body Part Mentions

**Code and data for the paper:**  
*The Language of Interoception: Examining Embodiment and Emotions Through a Corpus of Body Part Mentions*  
(Wu, Wahle, & Mohammad, EMNLP Findings 2025, Suzhou, China)

---

## What is Interoception?

Interoception refers to the sense of the internal physiological state of the body — such as heartbeat, breathing, temperature, or gut sensations. It underlies our ability to detect, interpret, and respond to signals from within our bodies.  

Research shows that interoceptive awareness is **strongly linked to emotional regulation, mental health, and decision-making**. According to the **Theory of Constructed Emotion (Barrett, 2017)**, emotions arise when the brain interprets bodily sensations in context:

> External situation → bodily signals → interpretation as emotion

For instance, a racing heart may be experienced as **anxiety** or **excitement**, depending on the situation.

---

## Language as a Window into Interoception

Language provides an accessible and powerful window into interoception.  
Phrases like *“my heart sank”* or *“my stomach turns”* reflect embodied experiences — how people perceive and communicate their bodily and emotional states.

This project explores how **everyday body-related language** reveals patterns of **embodiment and emotion** in large-scale natural language corpora.

We ask:  
> **How do people talk about their bodies in everyday language, and what does this reveal about emotion and well-being?**

---

## Body Part Mentions (BPMs)

We define **Body Part Mentions (BPMs)** as instances in text where words referring to body parts occur, such as:

- “I have a pain in my **chest**.”
- “He put his **hand** on my **shoulder**.”

BPMs serve as linguistic indicators of **embodied experience** — bridging physical sensation, emotional expression, and language.

---

## Datasets

We construct two novel corpora of body-related language:

- **TUSC<sub>BPM</sub>** — 6.9M tweets from the **TUSC** (Tweets from the US and Canada) dataset  
- **Spinn3r<sub>BPM</sub>** — 8.3K blog sentences from the **Spinn3r** weblog corpus  

These datasets enable quantitative investigations into how people use body-related words across **contexts, time, and regions**.

---

## Research Questions

We examine three main dimensions of embodied language:

### 1. Body Language Use
- How frequently are body parts mentioned in everyday language?  
- How do possessives (“my head”, “his hand”) and gendered references vary?  
- Are there **temporal** or **regional** trends in body-related expression?

**Findings:**
- Body-related words are **common** and **systematically structured**.
- “My <BPM>” constructions dominate, followed by “his” > “her”.
- Tweets emphasize **appearance and grooming**, while blogs emphasize **sensory experiences**.
- BPM usage shows **seasonal and regional variation**, with statistically significant geographic effects.

---

### 2. Body–Affect Relationships
- How does body-related language co-occur with emotional language?  
- Are certain body parts linked to particular emotions?

**Findings:**
- Sentences containing BPMs co-occur significantly more with **emotion-associated words**, particularly with **negative emotions** (low valence, low dominance).  
- Specific body parts show distinct emotional profiles:
  - **Stomach** → sadness  
  - **Chest** → anger  
  - **Heart** → love, longing  
  - **Head** → stress, confusion

---

### 3. Body Language and Health Outcomes
- Is there a link between body-related language and health indicators?

**Findings:**
- Using geo-tagged tweets and public health data from the **City Health Dashboard**, regional BPM frequency is an **extremely statistically significant predictor** of:
  - Frequent mental distress  
  - Frequent physical distress  
  - Shorter life expectancy  
  - Physical inactivity  

This suggests that **embodied language patterns** may reflect population-level well-being and health disparities.

---

## Summary and Future Directions

- **Simple lexical methods** (body word detection) uncover rich, interpretable patterns in embodied language.
- **Body part words** co-occur with emotional expressions, forming consistent **body–emotion associations**.
- **Regional BPM frequency** correlates with health outcomes, suggesting embodied language as a **linguistic marker of well-being**.

**Future work will explore:**
- **Cross-linguistic and cross-cultural** comparisons  
- Contextual and genre-based variation in embodiment  
- Links between **socioeconomic factors**, **emotion**, and **health** in embodied language use

---

## Citation

If you use the data or findings from this work, please cite:

```bibtex
@inproceedings{wu2025languageinteroception,
  title = {The Language of Interoception: Examining Embodiment and Emotions Through a Corpus of Body Part Mentions},
  author = {Wu, Sophie and Wahle, Jan P. and Mohammad, Saif M.},
  booktitle = {Findings of the Association for Computational Linguistics: EMNLP 2025},
  address = {Suzhou, China},
  year = {2025},
  publisher = {Association for Computational Linguistics}
}

```

## Authors

Sophie Wu – McGill University

Jan P. Wahle – University of Göttingen

Saif M. Mohammad – National Research Council Canada

For any queries, contact:
📧 sophie.wu@mail.mcgill.ca
