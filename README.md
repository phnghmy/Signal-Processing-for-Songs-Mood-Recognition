# Signal-Processing-for-Songs-Mood-Recognition
Signal Processing for Songs' Mood Recognition
In the evolving landscape of digital music consumption, accurate mood classification plays a crucial role in enhancing user experience on streaming platforms. While services like Spotify and SoundCloud have introduced mood-based features, inconsistencies in labeling often result in disjointed listening experiences. This project proposes a music mood recognition algorithm based on audio processing analysis and machine learning, particularly focusing on clustering techniques and neural networks.

This study utilizes a dataset of 389 songs across eight genres from the Free Music Archive (FMA), with music features such as tempo, key, scale (surface-level), and audio deep learning features such as spectral centroid and Mel-spectrograms, which are extracted through extensive preprocessing, including denoising, trimming, normalization, and Short-Time Fourier Transform (STFT). Both audio features and deep spectral representations are analyzed together and individually to find the best models.

Two machine learning approaches are employed: unsupervised clustering (K-Means and Fuzzy C-Means) to group songs into mood categories without labels, and a supervised neural network trained with sparse categorical cross-entropy and optimized via Stochastic Gradient Descent. Principal Component Analysis (PCA) is used to reduce feature dimensionality. Mood categories are defined by energy and emotion levels (Energetic/Relaxing × Happy/Sad), forming four mood groups.

The results show K-Means provides clearer, interpretable clusters, while the neural network—though flexible—exhibits overfitting, with a test accuracy of 43.59%. Fuzzy clustering
reveals the overlapping emotional content in music more effectively than hard clustering.Limitations include dataset size, subjectivity in mood labeling, and lack of lyrical or contextual
data.

This project contributes a potential framework for mood-based recommendation, offering feasible applications in playlist generation and music discovery for users and artists alike. Future work may explore deep learning architectures, context-aware personalization, and integration of lyrics for a more comprehensive emotional modeling of music.

<img width="617" alt="Screenshot 2025-04-03 at 11 10 34 AM" src="https://github.com/user-attachments/assets/a8fb21d9-f437-4807-897e-688f9fb4fe38" />
