# Comparing the Four Generative AI Tools: ChatGPT, DeepSeek, Gemini, and Copilot

## Project Overview

This project was developed during a one-day hackathon focused on evaluating the effectiveness of four generative AI tools—ChatGPT, DeepSeek, Gemini, and Copilot—in assisting with a full machine learning workflow. The challenge involved working with a given dataset to perform either a classification, regression, or time series task, while leveraging each AI tool throughout the process.

## Objectives

* Analyze and process a real-world dataset using all four AI tools
* Apply data preprocessing, feature engineering, model training, and evaluation
* Compare each tool based on:

  * Code generation quality
  * Explanation clarity
  * Efficiency and usefulness during different stages

## Technologies Used

* Python
* Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/Keras
* Google Colab (for development and documentation)

## Project Structure

```
├── Dataset/                   # Provided dataset
├── Colab_Notebook.ipynb       # Main notebook with full implementation
├── AI_Comparisons/            # AI prompt-response logs and notes
│   ├── ChatGPT/
│   ├── DeepSeek/
│   ├── Gemini/
│   └── Copilot/
├── README.md                  # Project documentation
```

## Workflow Steps

1. **Dataset Selection and Exploration**

   * Loaded and explored dataset
   * Identified data types, missing values, and summary statistics

2. **Data Preprocessing and Feature Engineering**

   * Handled missing data and encoded categorical features
   * Scaled numerical features
   * Created new features to enhance performance
   * Decomposed time series components where applicable

3. **Transfer Learning (for Image Data)**

   * Used pre-trained deep learning models such as VGG16 or ResNet
   * Fine-tuned the model on the given dataset
   * Addressed overfitting and underfitting using regularization and early stopping

4. **Model Selection and Training**

   * Chose suitable models based on task type
   * Trained models using AI tool suggestions
   * Compared model performance

5. **Hyperparameter Tuning**

   * Performed tuning using grid search or random search
   * Adjusted parameters to improve model performance

6. **Model Evaluation and Interpretation**

   * Evaluated model using metrics like Accuracy, Precision, Recall, RMSE, etc.
   * Generated reports such as confusion matrix or error plots
   * Compared tool suggestions for improvements

7. **AI Tool Comparison**

   * Documented all prompts and responses
   * Compared AI tools on clarity, correctness, and usefulness
   * Summarized strengths and limitations of each tool

## Key Findings

* ChatGPT was the most well-rounded tool for explanations and structured code
* DeepSeek provided efficient and accurate suggestions with minimal input
* Gemini was helpful in model training but lacked depth in technical explanations
* Copilot was strong in code completion but required developer supervision for logic

## Final Deliverables

* Google Colab notebook including:

  * Full implementation
  * Prompt logs and AI outputs
  * Code for preprocessing, modeling, evaluation
  * Comparative analysis of AI tools

## Conclusion

This project showcases the practical value of generative AI tools in data science workflows. By using ChatGPT, DeepSeek, Gemini, and Copilot in parallel, we observed distinct strengths in how each tool supports coding, learning, and problem-solving in real-time machine learning tasks.

## Author

**Vinay Kotadiya**
MSc Data Science, University of Hertfordshire
GitHub: [vinaykotadiya](https://github.com/vinaykotadiya)

---
