# NLP Assignment 

### Course: NLP with Deep Learning  
**Name:** Kaustubh Agrawal  
**Roll No:** 22222  
**Topic:** Co-occurrence Matrix (Count-based Word Embeddings)

---

## Introduction
This assignment is about understanding how count-based word embeddings work by building and analyzing a co-occurrence matrix. Word embeddings are important in Natural Language Processing (NLP) because they represent words in a numerical form that models their meanings and relationships.

---

## Objectives
- Load and preprocess a text dataset.  
- Build a co-occurrence matrix for the given text.  
- Visualize word relationships using PCA.  
- Interpret the results and explain the meaning of embeddings.  

---

## Dataset
We use the **Reuters Corpus** from NLTK.  
- The dataset contains news articles.  
- It is suitable for learning NLP because it has real-world text with different topics.  

---

## Steps Implemented
1. **Load Dataset**  
   - Reuters corpus from NLTK.  
   - Tokenization of text using NLTK.  

2. **Build Vocabulary**  
   - Selected the most frequent words.  
   - Assigned indices to each word.  

3. **Create Co-occurrence Matrix**  
   - Used a context window around each word.  
   - Counted co-occurrence frequencies.  

4. **Dimensionality Reduction**  
   - Applied PCA to reduce the high-dimensional co-occurrence matrix into 2D.  
   - Helps to visualize word similarities.  

5. **Visualization**  
   - Plotted the embeddings of frequent words in 2D space.  

---

## Results
- The co-occurrence matrix captures relationships between words based on context.  
- Words used in similar contexts are placed closer together after PCA visualization.  
- This shows how count-based embeddings represent semantic similarity.  

---

## How to Run
1. Open the notebook `task.ipynb` in Jupyter or VS Code.  
2. Run all cells step by step.  
3. Required libraries: `numpy`, `matplotlib`, `sklearn`, `nltk`.  

---

## Conclusion
- Co-occurrence matrices are an early but powerful method for word embeddings.  
- They help in understanding how words are related in a text corpus.  
- Though simple, this forms the foundation for advanced embeddings like Word2Vec and GloVe.  

