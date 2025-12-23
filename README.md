The official repository for the paper: "Multimodal Large Language Models for Big Data Synthesis: Addressing the Data Bottleneck of Chemicals in Plastics".

Code Introduction
1. SMILES Processing.py
Function: Batch canonicalization of SMILES strings for chemicals.
Input: SMILES string.csv
Output: Canonicalized SMILES string.csv
2. LLM for data extraction-Qwen2.5-32B.py
Function: This code implements the batch extraction of chemical economic indicator data from literature PDF files using the Qwen2.5-32B model.
Input: Literature.pdf files
Output: Extraction_data.txt files
3. LLM for data extraction-Qwen2-VL-72B.py
Function: This code implements the batch extraction of chemical economic indicator data from web images files using the Qwen2-VL-72B model.
Input: Web_images.jpg files
Output: Extraction_data.txt files

Citation
If you find our code useful, we kindly request that you cite the following paper:
Multimodal Large Language Models for Big Data Synthesis: Addressing the Data Bottleneck of Chemicals in Plastics
If you have any issues, please contact with cyhan@mail.dlut.edu.cn

