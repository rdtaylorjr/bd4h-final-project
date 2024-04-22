# bd4h-final-project
CSE 6250 Big Data Analytics for Heathcare 
Spring 2024
Final Project

Team ID:  A4
Team Members:  Saptarshi Basu and Russell Taylor
Paper Title:  Hongyi Yuan, Zheng Yuan, Sheng Yu (2022). Generative Biomedical Entity Linking via Knowledge Base-Guided Pre-Training and Synonyms-Aware Fine-Tuning. arXiv preprint arXiv:2204.05164.

Google Colab Notebook:  https://colab.research.google.com/drive/1oJ6Yif6AJvIJVkSlPUXVAsZ6z8bg58Pl
Google Drive Zip File: https://drive.google.com/file/d/1q9on0e7_b15JgpDH0FUfQbus6stpzI74
Github Repo: https://github.com/rdtaylorjr/bd4h-final-project/
PowerPoint: https://docs.google.com/presentation/d/1AbrsOq3NLhLLklfPL2qzGAL6Fz-KaexL
Video Presentation: https://youtu.be/sc8sKQKG7nw

## To run our code:
1. Copy the bd4h-team-a4.zip file from the Google Drive link above to your /content/gdrive/My Drive folder in your Google Drive account
2. Unzip the bd4h-team-a4.zip file to create a folder called /content/gdrive/My Drive /bd4h-team-a4
3. Open the Google Colab Notebook link above and connect to a GPU runtime. Our code must be run on a GPU or else it will fail.
4. When running the Google Colab notebook, it should mount to your newly created /content/gdrive/My Drive/bd4h-team-a4 folder

## IMPORTANT NOTE:
If you receive an error that `accelerate` is required, please run the cell that says !pip install transformers[torch], then restart the session, then run all cells except that one. We are using PyTorch and HuggingFace's Seq2SeqTrainer, which sometimes requires this workaround when used together. Additionally, please make sure you are running the notebook with a GPU, not a CPU.
