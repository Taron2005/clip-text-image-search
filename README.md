# clip-text-image-search
This is a simple and efficient image search engine that retrieves relevant images based on a text query using **CLIP** embeddings and **FAISS** similarity search, applied on the **Flickr8k** dataset.

## 🚀 How It Works

1. Each image is encoded into a fixed-size embedding using the **CLIP image encoder**.
2. Text queries are encoded using the **CLIP text encoder**.
3. Both embeddings are normalized for cosine similarity.
4. **FAISS** is used to quickly find top-N image vectors closest to the query embedding.
5. Matching images are displayed in a grid in Google Colab.
