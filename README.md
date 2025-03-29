# 🌙 MoodGuard

> **Bridging the gap between digital expression and real-life mental health support.**

---

## 🧠 Overview

As mental health issues rise globally by **25%**, social media has become a primary outlet for emotional expression—yet **only 30%** of teens seek professional help, despite **80%** expressing their struggles online.

**MoodGuard** is an **AI-driven tool** designed to integrate with social media platforms and identify potential mental health concerns in user-generated content. By performing real-time **sentiment analysis** and **mental health classification**, it offers users personalized support through pop-ups containing resources like:

- 🧑‍⚕️ Counseling and helpline links  
- 📘 Educational mental health content  
- 🎧 Custom Spotify playlists to boost mood

Users remain in control, with the option to dismiss suggestions—ensuring support without pressure.

---

## 🔍 Inspiration

We wanted to address **hidden mental health struggles**, especially those expressed subtly through social platforms like **Twitter, Instagram, and Reddit**. Recognizing that our team—and many others—turn to social media in tough times, we sought to build a solution that offers **help when it’s needed most**, without invading privacy.

---

## 🛠️ Tech Stack

- **Natural Language Processing (NLP)**  
- **BERT** (Bidirectional Encoder Representations from Transformers)  
- **Google Colab** for training and collaboration  
- **Custom Python GUI** for user interaction  
- **Spotify API** for personalized playlists  

---

## 🧪 How It Works

1. **Data Sourcing**  
   - Dataset from **Kaggle**, labeled with categories like *Depression*, *Anxiety*, *Suicidal*, *Bipolar*, and *Normal*.

2. **Preprocessing**  
   - Cleaned missing values  
   - Tokenized and split into training/testing sets  

3. **Model Training**  
   - Fine-tuned **BERT** over 3 epochs  
   - Achieved **81% accuracy**  
   - Switched to **GPU** to overcome memory limitations  

4. **Prediction + Interface**  
   - User inputs a post  
   - Backend performs sentiment classification  
   - Displays relevant mental health resources and a curated Spotify playlist

---

## ⚠️ Challenges & Learnings

- Initial struggle with vectorization led to reliance on BERT's built-in tokenizer  
- RAM issues when handling 50K+ samples → optimized by trimming to 5K without loss in accuracy  
- GUI design had to be user-friendly and non-invasive  
- Consulting mentors helped align technical decisions with user empathy

---

## 🎯 Impact

**MoodGuard** empowers social media platforms to proactively support mental health through subtle, non-intrusive interventions. By surfacing helpful resources when emotional distress is detected, it encourages help-seeking behavior while respecting user autonomy.

---

## 🚀 Try It Yourself

1. Clone this repo  
2. Open `moodguard.ipynb` on Google Colab  
3. Run the cells to train and deploy the model  
4. Interact with the GUI to simulate post submission  
5. View real-time mental health classification and suggested resources

---

## 🤝 Team & Credits

Built with passion and purpose during HackGT 11: Circus of Inventions.  
Special thanks to our mentors and the open-source community.

---

## 🌟 Future Improvements

- Real-time API for social media platforms  
- Expanded language support  
- Adaptive playlists based on mood over time  
- Opt-in user customization for types of resources shown

---

> _“Support doesn’t have to be loud. Sometimes, a whisper is all it takes.”_ 💙
