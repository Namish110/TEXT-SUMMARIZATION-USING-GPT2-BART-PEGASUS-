**About the Project**
Due to the rapid expansion of CNN daily News , keeping  the latest research and news has become more challenging for professionals. To overcome this challenge, effective text summarization is crucial for improving access to knowledge, enhancing the the article faster, and ultimately benifit for us. In this study, a news text summarization system that open large language models (LLMs) is fine-tuned and evaluated with the objective of generating precise, logical, and brief summaries of news article, emphasizing news relevance and ease of understanding. The projects focus on evaluating the performance of GPT2, BART and Pegasus model trained on the standard CNN dailynews dataset using standard evaluation metrics(ROUGE).
**Evaluation Metrics**
The standard evaluation metrics used for summarization tasks include ROUGE scores are used for evaluation purpose. The above mentioned metrics captures the structural and semantic similarity between the generated and reference summary. 
**Results Obtained**
From the 'cnn daily news' dataset I observed that bart is giving the best rouge score in the performance evaluation for large input like 2000 rows and above it but when we are taking 1000 rows as input from the article than it is giving pegasus ast best.
It means that for short data input pegasus is the best model for cnn daily news dataset and for large data input bart is giving the best model according to rouge score.
**Files Structure**
