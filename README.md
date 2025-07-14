# 🎯 Clip Recommender – Lumin Internship Prototype 2

This project is the second prototype created for the Lumin AI Internship Task. It demonstrates a **content-based recommendation engine** that suggests gaming clips to users based on their viewing history.

---

## 💡 Features

- Simulated user profiles with tag-based preferences
- Gaming clips with AI-generated tags (clutch, comedy, headshot, etc.)
- Personalized top-3 recommendations per user
- Uses cosine similarity and CountVectorizer (classic ML approach)

---

## 📊 Technologies Used

- Python
- Pandas / NumPy
- Scikit-learn (cosine similarity)
- Google Colab

---

## 🧠 How It Works

1. Each clip is tagged with descriptive metadata (e.g., `"clutch", "highlight"`).
2. Each user has a viewing preference history (simulated).
3. The system calculates **cosine similarity** between a user’s interests and each clip.
4. Returns the **top 3 most relevant clips** for that user.

---


