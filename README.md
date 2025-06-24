# Fine-Tuning-For-Text-Summarization
Utilized Hugging Face Transformers library for text summarization task. Performed inference, and then fine-tune one of the models on a custom dataset to improve quality of summary

# Problem Statement
In this assignment, you will gain hands-on experience with the Hugging Face Transformers library, one of the most popular and powerful tools in NLP. You will work with pre-trained
models for a text summarization task, use them for inference, and then fine-tune one of the models on a custom dataset. The dataset you will use for the summarization task is the SAMSum corpus developed by Samsung, which contains about 16,000 messenger-like dialogues and their corresponding summaries.
1. Exploratory Data Analysis:
  - Conduct an initial exploration of the SAMSum dataset to gain insights into the characteristics of the dialogues and summaries.
  - Plot the length distribution of dialogues and summaries in the training set.
2. Inference with Pre-trained Models:
  - Choose at least three pre-trained summarization models from the Hugging Face model hub, such as facebook/bart-large-cnn or t5-large.
  - Use the models to generate summaries for a few randomly selected dialogues. An- alyze the quality of these summaries: Are they coherent? Do they capture the essential points in the conversation?
3. Fine-Tuning:
  - Choose one of the pre-trained summarization models from the previous part.
  - Preprocess the dataset to fit it to the input format required by the chosen model, which may include tokenizing the dialogues and their summaries.
  - Train the model on the SAMSum corpus, monitoring its performance on the vali- dation set, and adjust its hyperparameters as needed.
  - Employ appropriate metrics for evaluating summarization quality, such as ROUGE scores, which compare the generated summaries against the reference summaries.
4. Evaluation and Analysis:
  - Evaluate the fine-tuned model’s performance on the test set. Compare these results to the model’s pre-fine-tuning performance using the same dialogues to assess the impact of fine-tuning.
  - Analyze the generated summaries for improvements in capturing key points, co- herence, and fluency. Discuss the fine-tuning’s impact on the model’s ability to summarize dialogues
