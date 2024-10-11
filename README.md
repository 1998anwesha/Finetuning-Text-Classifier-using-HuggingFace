# Finetuning-Text-Classifier-using-HuggingFace

Performed binary sentiment classification using the Stanford Sentiment Treebank (SST-2) dataset. I fine-tuned the DistilBERT base model (uncased) of HuggingFace on this dataset, achieving a validation accuracy of 90.37% after one training epoch. I utilized a custom training script, tracking loss and accuracy metrics with Weights & Biases for visualization.

I performed a detailed analysis of incorrectly predicted samples, identifying issues related to contextual misunderstandings and sarcasm. I suggested potential improvements, including aspect-based sentiment analysis and enhanced contextual training, to enhance the model's performance. Additionally, I created a t-SNE visualization of the model's predictions to analyze the clustering of classes. I utilized tools like Weights & Biases to track training progress and visualize learning curves.

## Dataset used

[SST2 movie reviews dataset] (https://huggingface.co/datasets/stanfordnlp/sst2)
