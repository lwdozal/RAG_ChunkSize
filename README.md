# A Comparison of Dynamic Chunk Size Methods
Initial Project Description of dynamic text-segmentation methods project at LAS-SCADS\
Jonathan Roig, Laura W. Dozal, Melissa J. Evans, and Lane Harrison

**Personal Contribution:** Foundational implementation of the RAG model and evaluation

*Abstract:* Sentences, paragraphs, and documents are often used as the standard chunk size for text embedding, but are any the optimal size for summarization and RAG tasks? We address this question in three parts: the creation of a summarization UI that allows users to compare the quality of summaries side-by-side with different chunk size methods on the backend, as well as the quantitative ROUGE scores compared to ground truth summaries; a simulation of RAG evaluation with vector databases created from different chunk size methods, evaluated with RAGAs; and a task given to analysts asking them to break down text into chunks of information to determine if any patterns might suggest a novel chunk size method. We find that most chunk size methods do not significantly influence the output of summarization using occams but overlapping 10 sentence chunks perform worse than others. We find that paragraph and semantic methods perform similarly for RAG, but the recursive method performs worse. Finally, we conclude that analysts widely vary in their perception of information chunks.
