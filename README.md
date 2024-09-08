# WeebFilter

WeebFilter is a simple model to recommend anime using collaborative filtering. The model is trained on a dataset of over 35 million entries and takes user preference to recommend animes.

This assignment is part of the PySpark Bootcamp 2024 at the dept. of Cloud Computing and Big-Data (CCBD), PESU.

## Two Approaches

WeebFilter implements two collaborative filtering methods:

1. **Alternating Least Square (ALS)**:

   - This matrix factorization method works by finding latent factors that represent user preferences and anime attributes. It alternates between minimizing the least squares of these factors to provide more accurate recommendations.
2. **Cosine Similarity**:

   - This method calculates the cosine similarity between user-anime vectors to identify how closely related users or anime are. It is used to recommend similar anime based on user preferences.

## License

This project is licensed under the unlicense.
