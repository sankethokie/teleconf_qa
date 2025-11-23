# teleconf_qa
AI &amp; NLP for improved Question / Answer sessions in teleconferences

This project implements an Augmented Intelligence system for improving virtual meeting user experience.

It processes meeting transcripts (CSV/Pandas DataFrame) and automatically generates:

Meeting summary (Extractive TextRank)
Action items (regex + heuristic AI detection)
Keywords & important topics (TF-IDF scoring)
Speaker statistics (talk-time, sentiment, turns)
Follow-up suggestions based on detected tasks
Saves JSON + CSV outputs
Shows a complete summary directly in your Jupyter Notebook

This edition is designed to work 100% offline and inside corporate firewalls, with no spaCy, no NLTK downloads, no HuggingFace, and no external dependencies beyond lightweight Python libraries.



This README matches the exact offline code I provided — fully spaCy-free, NLTK-free, HuggingFace-free, corporate-safe, Jupyter-ready.

AI + NLP System for Improved Q/A Sessions in Teleconferences (spaCy-free, NLTK-free, Fully Offline Edition)

Artificial Intelligence (AI) and Natural Language Processing (NLP) for Improved Question/Answer Sessions in Teleconferences.

This project implements an end-to-end AI system that analyzes teleconference transcripts to improve Question/Answer (Q/A) clarity and stakeholder experience.

It detects:
User questions
System-selected best answers
Unanswered questions
Low-confidence answers
Q/A linking
Priority ranking for follow-up actions
All processing is offline, safe for corporate laptops, and runs with no external downloads, no spaCy, no transformers, and no NLTK models.

Features
Automatic Question Detection
Regex + pattern-based detection of interrogative sentences.
Answer Matching via Semantic Similarity
TF-IDF vectorization
Cosine similarity
Local window search + global fallback
Unanswered Question Identification
If no candidate sentence meets the semantic threshold → flagged for follow-up.
Priority Ranking of Questions

Factors considered:
Whether unanswered
Speaker type (e.g., clients)
Negative sentiment
Question length/complexity
Semantic confidence
Detailed CSV + JSON Outputs
Q/A pairs with confidence
Unanswered list
Prioritized questions
Summary report
Office-Friendly
No API calls, no internet, no external models — ideal for restricted laptops.
