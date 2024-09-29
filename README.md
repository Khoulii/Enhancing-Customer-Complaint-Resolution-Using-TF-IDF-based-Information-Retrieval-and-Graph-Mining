# Enhancing-Customer-Complaint-Resolution-Using-TF-IDF-Information-Retrieval-System-and-Graph-Mining

## 1. Introduction
This project focuses on text mining and similarity analysis of complaints in Arabic and English. By leveraging NLP techniques, the project aims to preprocess textual data and determine the similarity of user queries to existing complaint descriptions.

## 2. Purpose
The primary purpose of this project is to enable users (employees) to find similar complaints based on their input query. By employing techniques such as TF-IDF vectorization and cosine similarity, the project enhances the retrieval of relevant documents, making it easier for users to access pertinent information.

## 3. Data Source
The dataset used for this project is a closed-source dataset from a popular telecommunication company in Amman, Jordan.

## 4. Packages Used
The following Python packages are utilized in this project:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `nltk`: For natural language processing tasks including tokenization, stemming, and stopword removal.
- `tashaphyne`: For Arabic text processing and stemming.
- `langid`: For language identification.
- `sklearn`: For implementing TF-IDF vectorization and cosine similarity calculations.
- `networkx`: For creating and visualizing graphs.
- `matplotlib`: For plotting graphs.
- `tkinter`: For creating the user interface.

## 5. Mechanism
The project follows these key steps:
1. **Text Preprocessing**: The raw text data is cleaned and processed. This includes tokenization, stopword removal, stemming, and handling Arabic diacritics.
2. **TF-IDF Vectorization**: The preprocessed text is transformed into a TF-IDF matrix, which represents the importance of words in the documents relative to the entire dataset.
3. **Cosine Similarity Calculation**: Similarity scores are computed between the user query and the existing complaint descriptions to identify the most relevant documents.
4. **Co-occurrence Analysis**: The project also includes an analysis of word co-occurrences in the top similar documents to identify relationships between terms.
5. **Graph Visualization**: Results are visualized through directed and weighted graphs, showcasing the relationships and similarities among complaints.

## 6. Results
The output of the project includes:
- The top 5 most similar documents based on the user query and their cosine similarity scores.
- Directed and weighted graph visualizations that illustrate the relationships between terms and the structure of similar complaints.
<p align="center">
  <img src="https://github.com/user-attachments/assets/309e2326-2d0e-4f65-9554-c7225d5a98fb" width="400">
  <img src="https://github.com/user-attachments/assets/e81fbc94-fa32-4968-9d63-953a6d84ecac" width="400">
  <img src="https://github.com/user-attachments/assets/f8a96cd9-5efa-4cb3-94f5-f08bca4c5fe0" width="400">
</p>
