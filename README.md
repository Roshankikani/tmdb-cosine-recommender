# movie-recommender-system-tmdb-dataset
tmdb-cosine-recommender is a content-based movie recommender system developed using the TMDB dataset. This system leverages cosine similarity on feature-engineered metadata to identify and suggest similar films based on user selection. Built with a Streamlit-based web interface, it delivers real-time, responsive recommendations in an interactive format suitable for end-user deployment.

Key features include:

Content-Based Filtering: Utilizes textual features such as genre, director, cast, and keywords to compute similarity scores.

Cosine Similarity Metric: High-dimensional vector representations of movie metadata are compared using cosine distance, ensuring robust recommendation accuracy.

Scalable Backend: Efficient data preprocessing and caching mechanisms support rapid inference even on large datasets.

Streamlit Integration: A modern web UI enables users to explore recommendations dynamically without backend complexity.

TMDB Dataset: Uses curated movie metadata provided by The Movie Database (TMDB), offering real-world relevance and scalability.