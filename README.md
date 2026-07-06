# 🎵 Music Recommendation System

A **Streamlit-based Music Recommendation System** that recommends songs according to the user's emotions detected from text input. The application uses **Natural Language Processing (NLP)** and **Machine Learning** to analyze the user's mood and suggest relevant songs.

---

## 🚀 Features

- 🎭 Emotion detection from user text
- 🎵 Song recommendations based on detected emotion
- 💻 Interactive Streamlit web interface
- 🤖 NLP-based emotion classification
- 📊 Machine Learning powered recommendation system

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Transformers (Hugging Face)
- Pickle

---

## 📂 Project Structure

```
Music-Recommendation-System/
│
├── assets/
│   ├── home image.png
│   ├── recommendation image.png
│   └── emotion image.png
|
├── app.py
├── requirements.txt
├── README.md
│
├── music/
│   ├── model.ipynb
│   └── musicdata.pkl
│
├── text/
│   ├── text_inference.ipynb
|   ├── text_model.ipynb
│   └── data/
│

```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/artsaikat/Music-Recommendation-System.git
```

### 2. Navigate to the project

```bash
cd Music-Recommendation-System
```

### 3. Create a virtual environment

```bash
python -m venv myenv
```

### 4. Activate the virtual environment

**Windows**

```bash
myenv\Scripts\activate
```

**Linux / macOS**

```bash
source myenv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will automatically open in your web browser.

---

## 🎯 How It Works

1. The user enters a sentence describing their current mood or situation.
2. A Transformer-based NLP model predicts the user's emotion.
3. Songs with similar emotional context are selected.
4. The recommended songs are displayed through the Streamlit interface.

---

## 📊 Dataset

The original Spotify dataset is **not included** in this repository because it exceeds GitHub's file size limit.

Place the dataset in the following location before running the project:

```
music/data/spotify_dataset.csv
```

---

## 📸 Screenshots

You can add screenshots of the application here.

Example:

```
assets/homepage.png
assets/recommendation.png
```

Then display them using:

```markdown
![Home Page](assets/homepage.png)

![Recommendations](assets/recommendation.png)
```


## 👨‍💻 Author

**Saikat Maiti**

GitHub: https://github.com/artsaikat

---

## 📄 License

This project is developed for educational and learning purposes.
