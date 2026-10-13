WEEK 7
# Constraint Specification and Iterative Prompt Refinement

## Aim
To practice constraint specification and iterative refinement
by improving an LLM's compliance with specified output constraints.

## Problem Statement
Generate a smartwatch description of no more than 60 words
using exactly three bullet points. Each bullet must start with a
verb, and the prohibited word must not appear in the response.

## Constraints
1. Exactly three bullet points.
2. Each bullet starts with a verb.
3. The prohibited word is not used.
4. The description contains no more than 60 words.

## Methodology
1. Define the initial prompt.
2. Generate a response using Gemini.
3. Check the response for constraint violations.
4. Refine the prompt using explicit instructions and an example.
5. Generate a second response.
6. Compare compliance before and after refinement.

## Technologies Used
- Python
- Google Gemini API
- Google Gen AI SDK
- Google Colab

## Repository Structure
- experiment.py: Experiment implementation
- requirements.txt: Required package
- outputs/: Execution results and screenshots
- README.md: Documentation

## How to Run
1. Install dependencies:
   pip install -r requirements.txt
2. Set your Gemini API key securely.
3. Run:
   python experiment.py

## Results
Execution screenshots and output files are available in the
outputs folder.

## Conclusion
The experiment evaluates whether clearer instructions and
examples improve LLM adherence to formatting and vocabulary
constraints.
