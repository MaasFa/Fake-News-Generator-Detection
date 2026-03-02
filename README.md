📰 Fake News: GPT-2 Generator & BERT Detector
This Jupyter Notebook contains the end-to-end implementation of a dual-purpose AI system. It explores the "Dual Role of AI" in modern media: using Generative AI to synthesize realistic misinformation and Discriminative AI to identify it.

🎯 Project Overview
In an era of rapid information dissemination, distinguishing between fact and fiction is a critical challenge. This project implements:

Generation: Leveraging GPT-2 (Causal Language Model) to create coherent news-style paragraphs based on a user's prompt.

Detection: Fine-tuning BERT (Bidirectional Encoder Representations from Transformers) for binary sequence classification to flag articles as "Real" or "Fake."

Live Analysis: A built-in web scraper using newspaper3k to fetch and analyze real-time news articles from any URL.

🛠️ Key Features in this Notebook
Automated Web Scraping: Integrated logic to extract clean text from messy HTML news sites.

Custom Dataset Pipeline: Implementation of a PyTorch Dataset class for efficient BERT tokenization and batching.

Model Fine-Tuning: A complete training loop using the Hugging Face Trainer API, optimized for text classification.

Interactive UI: A local web dashboard built with Gradio, allowing users to generate and detect news side-by-side.

Confidence Scoring: Probability-based output that indicates how certain the model is about its verdict.

📦 Dependencies
To run this notebook, ensure you have the following libraries installed:
pip install transformers torch pandas gradio newspaper3k lxml_html_clean scikit-learn

Conclusion: 
This project demonstrates the successful deployment of a dual-purpose AI system for the generation and detection of fake news. By combining GPT-2 and BERT, the system highlights the power of transformer models in understanding and creating complex natural language. The integration of URL scraping proves that such models are not just theoretical but can be applied to real-world internet content

Developed as part of the IBM PBEL (Project Based Experiential Learning) Program.
