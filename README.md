# TOPSIS-Based AI Model Ranking

## Overview
This project implements the **TOPSIS (Technique for Order Preference by Similarity to Ideal Solution)** method to evaluate and rank AI models based on multiple performance criteria. The method helps identify the best AI model by comparing its distance from the ideal and negative-ideal solutions.

## Features
- **Normalization**: Converts raw scores into a comparable scale.
- **Weighting**: Assigns importance to each criterion.
- **Ideal Solutions**: Identifies the best and worst values for each criterion.
- **Distance Calculation**: Measures how close each model is to the ideal solution.
- **Ranking**: Models are ranked based on their TOPSIS scores.
- **Result Storage**: Saves rankings in a CSV file.
- **Graphical Representation**: Generates a bar chart for easy visualization.


## Example Output
### Ranked AI Models
| Model   | TOPSIS Score |
|---------|-------------|
| GPT-4   | 0.66711        |
| Claude  | 0.51792        |
| Gemini  | 0.52480        |
| Mistral | 0.48227        |
| LLaMA   | 0.26997        |

### Visualization
A **bar chart**  is generated to visually compare the AI model rankings, helping users make informed decisions.


![topsis_ranking](https://github.com/user-attachments/assets/c88f7a66-05a0-463b-a465-63d442addb79)
