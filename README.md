# RAG_based_pdf_qna


![Alt text](https://github.com/priyanksonis/RAG_based_pdf_qna/blob/main/architecture.JPG)

Embedding Model: all-MiniLM-L6-v2  <br /> 
Vector Database: FAISS  <br /> 
Generative Model: t5-large 

This is the link to the colab notebook:

https://colab.research.google.com/drive/1WfZcRtnuYPERMYlyH7-vOQZ14Pt9wV-T?usp=sharing

PS: We are using similar chunking method used in this repo: https://github.com/bhaskatripathi/pdfGPT

## Dependencies

To run this notebook/code in your system you need to install the necessary packages with pip:

```bash
pip install pymupdf
pip install PyPDF2
pip install sentence-transformers
pip install faiss-cpu
pip install transformers
pip install gradio

 
