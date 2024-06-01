![Screenshot (293)](https://github.com/youssef665/AI-ML-projects/assets/110295462/b4e4b9a7-3b8f-4ec3-9542-45188e4ea2e0)![Screenshot (292)](https://github.com/youssef665/AI-ML-projects/assets/110295462/426e5543-f2e7-4175-8be3-89b2a3fdad7a)![Screenshot (293)](https://github.com/youssef665/AI-ML-projects/assets/110295462/876dd354-f7fe-4f84-9227-4d221060b4db)
![Screenshot (292)](https://github.com/youssef665/AI-ML-projects/assets/110295462/b206715c-a548-4007-abc2-8064feddf109)

The project involves the following key steps and components:

Data Preprocessing:

The song data is cleaned and prepared using SpaCy, a powerful NLP library. SpaCy is used to perform tasks such as tokenization, lemmatization, and removal of stop words. This step ensures the text data is in a suitable format for analysis and free from any noise that could affect the accuracy of the similarity predictions.
Vectorization:

The cleaned song data is converted into numerical vectors using the SentenceTransformer model. This model transforms text-based features of songs into a numerical format that can be quantitatively analyzed.
Cosine Similarity Calculation:

The vectorized song data is then analyzed using cosine similarity. Cosine similarity measures the similarity between two non-zero vectors of an inner product space by measuring the cosine of the angle between them. This method is particularly effective for text data, as it provides a robust metric for determining the similarity between songs based on their lyrical content.
Libraries and Tools Used:
Numpy: For numerical operations and handling arrays.
Pandas: For data manipulation and analysis.
SpaCy: For preprocessing text data, including tokenization, lemmatization, and stop word removal.
SentenceTransformer: For converting song lyrics into numerical vectors.
Scikit-learn: Specifically, the cosine_similarity function to compute similarity scores.
OS: For handling file operations.
By following these steps, the project is able to predict song similarity, which can be used for various applications such as music recommendation systems, playlist generation, and music analysis.

This project demonstrates an effective approach to quantifying song similarity using machine learning and natural language processing techniques, making it possible to recommend songs that are similar in their lyrical content.
