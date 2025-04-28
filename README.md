# HighRiskProject-SimplifiedSummarizationOfSyntheticClinicalNotes
Using GPT for Simplified Summarization of Synthetic Clinical Notes

This project uses OpenAI's GPT models (zero-shot, few-shot, chain-of-thought, and tree-of-thought prompting) to simplify synthetic clinical notes for patient understanding.

## Project Overview

- Synthetic clinical notes are generated using conditions, observations, and medications.
- Different prompt engineering strategies (Zero-Shot, Few-Shot, Chain-of-Thought, Tree-of-Thought) are applied.
- The GPT model outputs simplified versions of complex medical notes.
- Results are stored in a CSV file.

## How to Run

1. Install required packages:
- pandas
- openai
- google-colab

2. Upload the following CSV files into your Colab session:
   - conditions.csv
   - observations.csv
   - medications.csv

3. Set your OpenAI API Key when prompted.

4. Run the notebook to:
- Generate clinical notes
- Summarize them using multiple GPT prompting techniques
- Save the results to final_gpt_summarization_results.csv

5. Output:

   The script generates a CSV file (final_gpt_summarization_results.csv) containing:
- Original clinical notes
- Summarized notes for each prompting strategy.

6. Notes:

   This project uses synthetic data.

   API key security: Do not hardcode your API key. It is securely entered during runtime.
