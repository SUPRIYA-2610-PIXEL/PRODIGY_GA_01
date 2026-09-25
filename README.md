# Task-01: GPT-2 Text Generation using Fine-Tuning

## 📌 Objective

The objective of this task is to fine-tune a pre-trained GPT-2 transformer model on a custom dataset and generate coherent and contextually relevant text based on a given prompt.

## 🧠 Project Description

In this project, a pre-trained **GPT-2** language model was fine-tuned using a custom dataset containing text related to Artificial Intelligence, Machine Learning, Generative AI, Python, and Natural Language Processing.

After fine-tuning, the model was tested with different prompts to generate new text based on the learned patterns from the custom dataset.

## 🛠️ Technologies Used

* Python
* Google Colab
* Hugging Face Transformers
* Hugging Face Datasets
* GPT-2
* PyTorch

## ⚙️ Project Workflow

1. Set up Google Colab with a T4 GPU.
2. Installed the required Python libraries.
3. Loaded the pre-trained GPT-2 model and tokenizer.
4. Created a custom text dataset.
5. Loaded and tokenized the dataset.
6. Prepared the data for causal language modeling.
7. Fine-tuned GPT-2 using the Hugging Face Trainer.
8. Generated text using different prompts.
9. Saved the generated results and fine-tuned model.

## 📂 Custom Dataset

The custom dataset contains short text samples related to:

* Artificial Intelligence
* Machine Learning
* Generative AI
* Python
* Natural Language Processing
* Deep Learning
* Large Language Models

The dataset is included in the repository as:

`custom_dataset.txt`

## 🤖 Model

The project uses the pre-trained:

**GPT-2**

GPT-2 is a transformer-based causal language model capable of generating text based on a given context or prompt.

## ✨ Text Generation Experiments

The fine-tuned model was tested using the following prompts:

### Experiment 1

**Prompt:**

```text
Artificial intelligence
```

### Experiment 2

**Prompt:**

```text
Machine learning
```

### Experiment 3

**Prompt:**

```text
Generative AI
```

The generated outputs are saved in:

`generation_results.txt`

## 📊 Results

The fine-tuned GPT-2 model successfully generated text based on the provided prompts.

The generated text reflects patterns and topics learned from the custom training dataset.

## 📁 Project Structure

```text
PRODIGY_GA_01/
│
├── Task-01_GPT2_Text_Generation_Fine_Tuning.ipynb
├── custom_dataset.txt
├── generation_results.txt
└── README.md
```

## 💻 How to Run

1. Open the notebook in Google Colab.
2. Enable a GPU runtime such as T4 GPU.
3. Install the required libraries.
4. Load the GPT-2 model and tokenizer.
5. Load the custom dataset.
6. Run the fine-tuning process.
7. Provide a text prompt.
8. Generate text using the fine-tuned GPT-2 model.

## 📚 References

* Hugging Face – Text Generation:
  https://huggingface.co/blog/how-to-generate

* Google Colab – GPT-2 Text Generation:
  https://colab.research.google.com/drive/15qBZx5y9rdaQSyWpsreMDnTiZ5IlN0zD

## ✅ Conclusion

This project demonstrates how a pre-trained GPT-2 transformer model can be fine-tuned on a custom dataset and used for text generation. The task provided practical experience with Hugging Face Transformers, dataset preparation, model fine-tuning, and prompt-based text generation.

## 👩‍💻 Author

##SUPRIYA P##
