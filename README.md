# GROW Phase Text Classifier

This project implements a Natural Language Processing (NLP) based system that classifies user input into one of the four stages of the **GROW coaching model**:  
**Goal**, **Reality**, **Options**, and **Will**.

It aims to enable intelligent AI-driven coaching systems by automatically identifying the coaching stage from conversational text, making it useful for digital coaching assistants, self-reflection tools, or productivity apps.

---

## What is the GROW Model?

The **GROW model** is a structured framework used in coaching and mentorship. It guides users through:

- **G (Goal):** What do you want to achieve?
- **R (Reality):** What is the current situation?
- **O (Options):** What are the possible solutions or strategies?
- **W (Will):** What actions will you commit to taking?

This classifier helps map user responses or journaling entries into these categories.

---

## Features

- Classifies text into GROW phases using NLP techniques
- Simple API-ready prediction logic
- Easy to integrate into chatbots, coaching platforms, or journaling apps
- Compatible with both traditional ML and transformer-based models

---

## Example

```python
from grow_classifier import predict_phase

text = "I want to improve my public speaking confidence."
phase = predict_phase(text)
print("GROW Phase:", phase)
# Output: GROW Phase: Goal
