## 🧠 Introduction
This project focuses on analyzing large volumes of news articles to identify **cluster topics** using **PySpark MLlib** for scalable machine learning. The project also features a **Gradio-based UI** for an interactive experience. After preprocessing and model training, we achieved a **clustering accuracy of 79%**.

## 🧰 Prerequisites
<div align="left">
  <img alt="Gradio" src="img/gradio.png" height="60" width="60"/>
  <img alt="Python" src="img/python.png" height="70" width="70"/>
</div>

## ⚙️ Workflow
1. **Data Collection**:
   * News articles collected from datasets like Kaggle.
2. **Data Preprocessing**:
   * Tokenization, stop word removal, TF-IDF vectorization using PySpark.
3. **Model Building**:
   * Logistic Regression via PySpark MLlib.
4. **Integration**:
   * Interactive Gradio UI for real-time article clustering.
5. **Result**:
   * Achieved \~79% clustering accuracy.

### 🔁 Data Flow:

News Dataset -> Preprocessing -> Feature Engineering -> Model Building -> Gradio UI

## 🖥️ Gradio UI Preview
* Input: Paste a news headline.
* Output: Displays predicted topic.
* Purpose: To identify the article’s underlying topic interactively.



