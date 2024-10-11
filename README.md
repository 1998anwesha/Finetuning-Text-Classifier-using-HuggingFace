# Finetuning-Text-Classifier-using-HuggingFace

I selected a pre-trained HuggingFace model, DistillBERT to replicate for fine-tuning. I implemented a custom training script by creating a CustomTrainer class, which inherits from the default Trainer while incorporating my own inner training loop. 
I utilized tools like Weights & Biases to track training progress and visualize learning curves. After evaluating the model's performance on the test set, I analyzed errors and compared my finetuned model's sentiment analysis predictions (positive /negative) predictions with those from ChatGPT for additional insights.

## Dataset used

SST2 movie reviews dataset
