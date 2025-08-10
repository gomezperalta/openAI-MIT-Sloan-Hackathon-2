# openAI-MIT-Sloan-Hackathon-2
Contribution to the challenge "Mini Alpha-Fold".

In the jupyter-notebook you will find a mock for predicting the binding strength between a ligand and a protein sequence. For that purpose, the SMILES representation of the ligand and the protein sequence are processed to obtain the embeddings using transformer models available in Hugging Face. These transformers correspond to DeepChem/ChemBERTa-5M-MLM (SMILES), Rostlab/prot_bert (protein sequence) and facebook/esm2_t6_8M_UR50D (protein sequence).

With the embeddings, a simply linear model is fit. This is a simple idea to be workout later.
