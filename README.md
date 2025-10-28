# NLP
# Mini Project: Influence of System Prompts on Bias in Language Models

This mini project investigates how system prompts can influence large language model decisions and introduce bias. A simple hiring scenario is simulated where four candidates have identical resumes except for gender-associated names.

Two types of evaluation prompts are used:

1. Neutral prompt  
2. Biased prompt that favors male candidates  

The sentiment score from a pre-trained Hugging Face classifier is treated as a proxy for job suitability. Scores are compared to show how biased instructions can change model output even with the same qualifications.

------------------------------------------------------------------------------------------------------------------

## Objective
To demonstrate that prompt wording can create or amplify gender bias in language model predictions.

## Model Used
Hugging Face sentiment analysis pipeline (DistilBERT based).

## Steps
1. Install required libraries
2. Simulate candidate profiles with identical skills
3. Evaluate them using neutral and biased prompts
4. Compare predictions using tables and a bar chart
5. Analyze bias reflected in score differences

------------------------------------------------------------------------------------------------------------------

## Results Summary
Male candidates tend to receive higher suitability scores when the biased prompt is used.  
Female candidates show a decrease in score under the same condition.  
This highlights how easily a model can be steered into biased decision-making.

------------------------------------------------------------------------------------------------------------------

## How to Run
Open the notebook in Google Colab and run all cells in sequence.  
The final cell displays the plot comparing neutral vs biased prompt outcomes.

------------------------------------------------------------------------------------------------------------------

Output Interpretation:
The results show a clear difference between neutral and biased prompt conditions. Identical candidate profiles receive different suitability scores depending only on the framing of the prompt. This confirms that system prompts have a measurable influence on model bias and decision-making behavior.


<img width="550" height="500" alt="image" src="https://github.com/user-attachments/assets/98293dec-efad-4e58-ae1c-c58d376a2c0b" />


