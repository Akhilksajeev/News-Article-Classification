### **News Article Classification**  

This project classifies news articles into **10 categories** (e.g., *Business, Sports, Politics*) using **NLP and machine learning**.  

#### **Key Steps:**  
1. **Preprocessing**: Cleans text (lowercase, removes URLs/punctuation), applies lemmatization, and removes stopwords.  
2. **Feature Extraction**: Uses **TF-IDF** to convert text into numerical features.  
3. **Models Tested**:  
   - **Logistic Regression** (Best: **79.87% accuracy**)  
   - **Naive Bayes** (78.31%)  
   - **SVM** (79.14%)  
4. **Interactive Tool**: Users input text and select a model for real-time predictions.  

#### **Result**:  
- **Logistic Regression performed best**, with strong accuracy across categories like *Sports (F1: 0.89)* and *Business*.  
- **Use Case**: Automated news tagging for publishers or content recommendation.  

**Future Work**: Try deep learning (e.g., BERT) for improved accuracy.
