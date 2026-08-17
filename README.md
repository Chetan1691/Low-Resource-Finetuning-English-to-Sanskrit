India has 22 scheduled languages and hundreds of additional languages and dialects.
Most publicly available text corpora and LLM pretraining data are concentrated in English and other high-resource languages.
Resource availability among Indic languages is highly uneven.
Languages such as Hindi, Kannada, Tamil, Telugu and Bengali have abundant datasets and web corpora.
Languages like Sanskrit, Konkani, Bodo and Santali have very limited digitized text, parallel corpora and evaluation datasets.
Full fine-tuning of modern LLMs requires significant GPU memory, making it impractical on consumer hardware or free cloud GPUs.
Parameter-Efficient Fine-Tuning (PEFT) techniques reduce the computational and memory requirements for model adaptation.
QLoRA (Quantized Low-Rank Adaptation) achieves this by quantizing the base model to 4-bit precision and training only small low-rank adapter matrices.
QLoRA trains less than 1% of the model parameters while retaining performance close to full fine-tuning.
This project fine-tunes a small open-source LLM on an English–Sanskrit parallel corpus using QLoRA on free-tier cloud platforms (Google Colab and Kaggle Notebooks)
