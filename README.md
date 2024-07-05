# Enhancing Text Summarization Accuracy using NLP and LLMS

## Project Overview
This project focuses on improving the accuracy of text summarization through advanced generative AI models. We employ DistilBERT, T5-Small, and BART models, extensively fine-tuned for the abstractive summarization of text.

### Dataset
The CNN/Daily Mail dataset was employed, well-known for its extensive collection of news articles paired with summaries, providing a robust benchmark for training and evaluating the summarization models.

![dataset distribution](https://github.com/Maryam189/Enhancing-Text-Summarization-Accuracy-using-NLP-and-LLMS/assets/76420523/f7cda25d-f3ed-422c-b2ff-58c05e9dc853)


## Models Description
### DistilBERT
Optimized for faster performance and reduced resource consumption, DistilBERT effectively distills crucial elements from texts, crafting brief, precise summaries.

![distillbert_output](https://github.com/Maryam189/Enhancing-Text-Summarization-Accuracy-using-NLP-and-LLMS/assets/76420523/7d1baca4-88bd-410a-b800-e9ea4f009c7c)

### T5-Small
Part of the T5 model family, T5-Small treats text-based tasks as conversions from one form of text to another, balancing computational demands and performance.

![t5_output](https://github.com/Maryam189/Enhancing-Text-Summarization-Accuracy-using-NLP-and-LLMS/assets/76420523/e846a3e8-e119-4c16-be96-babd3ef1bbe7)

### BART
Renowned for text generation and comprehension, BART is fine-tuned to generate concise summaries that capture the essence and tone of the original text.

![bart_output](https://github.com/Maryam189/Enhancing-Text-Summarization-Accuracy-using-NLP-and-LLMS/assets/76420523/fd5183dc-5136-45f5-ad15-97f40ef7673e)


Models were fine-tuned on the CNN/Daily Mail dataset using NVIDIA Tesla T4 GPUs and evaluated using ROUGE-L, METEOR, and BERTScore to enhance summarization quality.

## Tech Stack
- **Python**: Primary programming language.
- **Hugging Face Transformers**: For implementing and managing pre-trained models.
- **PyTorch 1.7.1**: Used for model training and evaluation.
- **Google Colab**: Provides free GPU access for large-scale computations.

## Experimental Setup

![image](https://github.com/Maryam189/Enhancing-Text-Summarization-Accuracy-using-NLP-and-LLMS/assets/76420523/fb5c42b3-40a3-47c8-bf20-071a9372ec27)

## Methodology
### Data Preprocessing
Extensive preprocessing techniques to optimize model input, including tokenization and sequence length adjustment.

### Model Training
Utilizes NVIDIA Tesla T4 GPUs, ensuring efficient model training and execution.

### Hyperparameter Tuning
Detailed tuning of model parameters like learning rate and batch size to maximize performance.

## Results
### Performance Metrics
Evaluation using ROUGE-L, METEOR, and BERTScore to assess the effectiveness of the summarization models.

### Model Comparison
Comparative analysis of the different models have been done to determine the most effective configuration for text summarization tasks.

![image](https://github.com/Maryam189/Enhancing-Text-Summarization-Accuracy-using-NLP-and-LLMS/assets/76420523/f804dad4-3890-4e2a-a343-2d4cbaeb84e5)

## Future Work
### Model Enhancements
Explore additional models and configurations to further improve summarization accuracy.

### Dataset Expansion
Consider the inclusion of more diverse datasets to generalize model capabilities across different text types.

### Real-time Application
Implementation of the models in real-time applications for dynamic summarization needs.

## Usage
To use or contribute to this project:
1. Clone the repository.
2. Install required libraries: `pip install -r requirements.txt`.
3. Execute the Jupyter notebooks in Google Colab with GPU acceleration enabled for optimal performance.

## Contributing
Contributions to this project are welcome! Fork the repository, make your changes, and submit a pull request with your improvements.

## License
This project is available under the MIT License. Refer to the LICENSE file in the repository for more details.
