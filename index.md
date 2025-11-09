## DSC 180A Methodology Assignment 4 ##

- Rahul Sengupta (rasengupta@ucsd.edu)
- DSC 180A Section A07; Mentor: Ryan Lingo

# Questions #
1. One of the most interesting topics covered in our domain this quarter has been the challenge of evaluating LLMs beyond traditional benchmark scores. I found it fascinating how evaluation itself is an open research problem – particularly how we can design metrics that capture qualitative aspects like factual accuracy, coherence, and completeness in generated summaries.
2. For Quarter 2, I’d like to explore how different evaluation strategies affect our understanding of LLM summarization performance. Specifically, I’m interested in comparing automated evaluation metrics (ex: ROUGE, BERTScore, and GPT-based grading) with human evaluation to determine how well these metrics align. The goal would be to identify which automated metrics best correlate with human judgment when evaluating the quality of lecture slide summaries.
3. In Quarter 1, our project primarily focused on using lecture slides as the dataset and summarization as the evaluation context. A potential change I’d make is to expand beyond one summarization task and incorporate multiple text-generation settings, such as short-answer grading or question-answering. This would allow us to test whether certain evaluation metrics are consistent across different natural language generation tasks.
4. I’d be interested in incorporating few-shot or chain-of-thought prompting techniques to analyze whether different prompting styles influence the model’s output quality and how that interacts with various evaluation metrics. Additionally, I’d like to explore embedding-based similarity methods and statistical correlation analyses to better understand metric reliability and inter-rater agreement. I finally try to see how we could evaluate our evaluators and see how many layers we could use to achieve satisfaction (given that it is logically ambiguous to do so).
