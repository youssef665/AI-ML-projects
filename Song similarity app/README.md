
![Screenshot (293)](https://github.com/youssef665/AI-ML-projects/assets/110295462/51d809d3-d018-4653-a591-9908bcc36eba)<br>
![Screenshot (292)](https://github.com/youssef665/AI-ML-projects/assets/110295462/ac0e2bd0-b015-4ad3-b256-a2fd538368e6)<br>

The project involves the following key steps and components:

## Data Preprocessing:<br>

The song data is cleaned and prepared using SpaCy, a powerful NLP library. SpaCy is used to perform tasks such as tokenization, lemmatization, and removal of stop words. This step ensures the text data is in a suitable format for analysis and free from any noise that could affect the accuracy of the similarity predictions.<br>
## Vectorization:<br>

The cleaned song data is converted into numerical vectors using the SentenceTransformer model. This model transforms text-based features of songs into a numerical format that can be quantitatively analyzed.<br>
## Cosine Similarity Calculation:<br>

The vectorized song data is then analyzed using cosine similarity. Cosine similarity measures the similarity between two non-zero vectors of an inner product space by measuring the cosine of the angle between them. This method is particularly effective for text data, as it provides a robust metric for determining the similarity between songs based on their lyrical content.<br>
## Libraries and Tools Used:<br>
Numpy: For numerical operations and handling arrays.<br>
Pandas: For data manipulation and analysis.<br>
SpaCy: For preprocessing text data, including tokenization, lemmatization, and stop word removal.<br>
SentenceTransformer: For converting song lyrics into numerical vectors.<br>
Scikit-learn: Specifically, the cosine_similarity function to compute similarity scores.
OS: For handling file operations.<br>

By following these steps, the project is able to predict song similarity.

This project demonstrates an effective approach to quantifying song similarity using machine learning and natural language processing techniques, making it possible to recommend songs that are similar in their lyrical content.
