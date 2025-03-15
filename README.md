# Finance-Chatbot
**Code:** [financechatbot](https://github.com/Yanjun-Zhou-Clivia/Finance-Chatbot/blob/main/finance%20chatbot.ipynb)
This project fine-tunes OpenFinAL/GPT2_FINGPT_QA, a pre-trained finance-focused GPT-2 model, to enhance its ability to generate domain-specific financial responses. The model is trained on the Financial PhraseBank dataset to improve performance in financial sentiment interpretation, stock market analysis, and investment strategy guidance.

---

🛠️ **Tools & Libraries**
- **Python**
- **Hugging Face Transformers**: Model loading, tokenization, and fine-tuning
- **Datasets (Hugging Face)**: Managing financial text data
- **PyTorch**: Training deep learning models
- **Evaluate**: Perplexity and BLEU score calculations
- **NumPy & Pandas**: Data preprocessing and manipulation
- **Matplotlib & Plotly**: Training visualization and results analysis

---

📊 **Dataset**
- **Financial PhraseBank**: A dataset containing financial news sentences labeled by sentiment (positive, negative, neutral)
- **Variant Used**: "sentences_allagree"
- **Purpose**: Improves financial text comprehension for NLP tasks such as sentiment analysis

---

📌 **Key Features**
- **Preprocessing & Tokenization**: Prepares financial text data for training with optimized tokenization.
- **Fine-Tuning Process**: Enhances GPT-2’s financial domain knowledge through supervised learning.
- **Hyperparameter Optimization**: 
  - Learning Rate: `2e-5`
  - Optimizer: `AdamW` with weight decay (`0.01`)
  - Batch Size: `4` (adjusted for GPU constraints)
  - Training Epochs: `5` (to balance learning and overfitting prevention)
- **Evaluation Metrics**: 
  - **📉 Perplexity (PPL)**: Measures language model uncertainty—lower values indicate better performance.
  - **📈 BLEU Score**: Evaluates generated text similarity to reference responses.
- **💾 Model Saving & Deployment**: Saves the best-performing model checkpoint for future use.

💡 Explore the fine-tuned financial chatbot and see how it enhances domain-specific text generation with GPT-2!

