## Personalized Movie Recommendation System

### Project Concept:
This project aims to develop a personalized movie recommender system leveraging advanced machine learning and deep learning algorithms. The system is designed to enhance the movie selection process by providing tailored recommendations based on user preferences and behaviors. By integrating existing techniques and frameworks, the project seeks to improve the user experience on Over-The-Top (OTT) streaming platforms, offering a more personalized and satisfying movie discovery process  .

### Supporting Motivation:
The motivation for this project stems from personal challenges and broader issues faced by users in the digital landscape. Many users, including myself, find it difficult and time-consuming to locate suitable movies on existing platforms, leading to a frustrating experience. Studies have shown that personalized recommendation systems significantly increase user satisfaction and decrease the time spent searching for content. The project aims to address these issues by developing a system that reduces information overload and helps users discover diverse and relevant movies efficiently .

### Project Development Process:
1. **Data Preprocessing and Exploratory Data Analysis (EDA):**
   - Cleaning and optimizing the dataset to ensure high-quality input for the models.
   - Utilizing libraries such as Python, pandas, seaborn, and matplotlib for data handling and visualization.

2. **Model Development:**
   - **Baseline Model:** Implementing Singular Value Decomposition (SVD) for its simplicity and effectiveness.
   - **Primary Model:** Developing a stacked autoencoder using PyTorch to capture non-linear user-item relationships.
   - **Additional Models:** Incorporating SVD++, Restricted Boltzmann Machine (RBM), and a hybrid algorithm to enhance recommendation accuracy.

3. **Model Evaluation and Fine-Tuning:**
   - Comparing models based on evaluation metrics like Mean Absolute Error (MAE) and Root Mean Square Error (RMSE).
   - Conducting user testing with real reviews from friends and family to validate the recommendations.

4. **Final Deliverables:**
   - A robust and functional movie recommender system.
   - Documentation of the project, including methodologies, results, and future work suggestions.

### Evaluation:
The evaluation process involved a thorough comparison of different models based on predictive performance metrics. The best-performing model was further fine-tuned and validated through user testing, ensuring both statistical robustness and practical relevance. The user feedback highlighted the model's ability to provide accurate and satisfying recommendations, confirming the project's success in enhancing the movie selection experience .

### Conclusion and Future Work:
- The project successfully developed a personalized movie recommendation system.
- **97%** of the users liked the movies recommended by the model.
- Future development will focus on updating the movie database, expanding language and TV show inclusivity, incorporating OTT platform information, automating user feedback collection, and collaborating with OTT platforms for broader user evaluation.
- These enhancements will ensure continuous evolution and adaptation of the system to meet user needs and keep up with advancements in the field of recommendation systems.
