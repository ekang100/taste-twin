# Taste Twin

Taste Twin is a data science and machine learning project exploring user compatibility and personalized food recommendations using Yelp data.

## 📊 Data Source

All data used in this project is sourced from the [Yelp Open Dataset](https://www.yelp.com/dataset), which includes:
- Business metadata
- User reviews
- User profiles
- Tips and more

We filter and preprocess the dataset to focus on food-related businesses and extract relevant features for modeling.

## 🧠 Goals

- Build compatibility scores between users based on review and taste overlap
- Recommend restaurants based on latent user and business embeddings
- Explore explainability layers to show *why* a recommendation was made

## ⚠️ Note

Large raw data files (JSON, JSONL, TAR) are excluded from this repository via `.gitignore`. You can download them directly from Yelp’s official dataset page if needed.
