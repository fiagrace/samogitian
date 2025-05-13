# samogitian

fine-tuning language model with with XLM-RoBERTa architecture to classify Samogitian dialect

crawl.ipynb: targeted web crawler with language detection using fastText.

preprocessing.ipynb: 
Quality filtering (length, repetition, toxic content removal)
Language verification
Boilerplate removal
Deduplication
Dataset creation

finetuning.ipynb: 
Tokenizes and fine-tunes model on masked language modeling using:
Weighted random sampling
Curriculum learning
Visualizations


classifier.ipynb: 
Binary dialect identification model (Lithuanian vs Samogitian) with balanced sampling

analysis.ipynb:
Investigates ability to predict masked words

The output files created by preprocessing are very large and not kept here. They will made available upon request.

Project created for Neuro 140/240.
