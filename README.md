# Rust-IR-BERT 

## Machine Learning-Based Vulnerability Detection in Rust Code Using LLVM IR and Transformer Model

This repository implements **Rust-IR-BERT**, a machine-learning pipeline for automated vulnerability detection in Rust code. It provides the following two end-to-end workflows:

- **LLVM IR Pipeline**  
  1. Compile Rust source to LLVM IR  
  2. Extract semantic embeddings with GraphCodeBERT  
  3. Classify vulnerabilities using CatBoost  

- **Rust Source Pipeline**  
  1. Clean and tokenize raw `.rs` files  
  2. Extract embeddings with GraphCodeBERT  
  3. Classify with CatBoost  

