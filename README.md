# 102117161-topsis-text_generation
# Topsis to compare different pretrained text generation models

This repository contains code for comparing five different pretrained hugging face text generation models using various metrics such as BLEU score, ROUGE score, perplexity. They have been evaluated on basis of their performance and ranked using TOPSIS (Technique for Order Preference by Similarity to Ideal Solution).    
Overview: Text generation models have become increasingly popular in natural language processing tasks such as chatbots, language translation and content generation. However, evaluating the performance of these models is essential to understand their effectiveness and suitability for specific tasks.In this project, several pre-trained text generation models have been evaluated using multiple metrics:  

BLEU Score: Measures the similarity between the generated text and the reference text based on n-gram overlap.  
ROUGE Score: Evaluates the overlap between generated and reference text using recall, precision and F1 score.  
Perplexity: Indicates the uncertainty or entropy of the generated text given the input.   
Models Used:   
"gpt2"  
    "gpt2-medium" (Best)  
    "openai-gpt"  
    "facebook/bart-large"  
    "sshleifer/tiny-gpt2"  
    "microsoft/CodeGPT-small-py"    
Process  
Data Preparation: Defining a reference text and sample input text for evaluation.  
Model Evaluation: Loading pre-trained text generation models and using them to generate text based on the input. BLEU score, ROUGE score and perplexity has been calculated for each generated text.  
TOPSIS Analysis: Computing the TOPSIS score for each model based on its performance across the metrics. This helps in ranking the models to identify the most suitable one.  
Visualization: Visualizing the TOPSIS scores using a bar graph and a heat map for easy comparison between models.    

The evaluation results are presented in the 102117161-TopsisTextGeneration-results.csv file which includes the performance metrics,TOPSIS scores and rank for each evaluated model.To visualise the results comparison charts have been prepared for topsis score and other evaluation parameters for each model. Further, a heat map has been used to show the correlation between different parameters used for evaluation.
