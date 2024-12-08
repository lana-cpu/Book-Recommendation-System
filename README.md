# Book Recommendation System Using NLP by Lana G.

The Book Recommendation System is designed to help users find books based on their interests. By using Natural Language Processing (NLP) techniques, the system matches user input, such as keywords or genres, to relevant book titles in the dataset. The goal of the project is to create a simple yet effective tool for recommending books.

"The dataset used for this project is the **Book Recommendation Dataset**, sourced from Kaggle : (https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset). \n",
    "It consists of various files containing detailed information about books, including:\n",
    "- **Books.csv**: Includes book titles, authors, publication years, and links to book images.\n",
    "- **Ratings.csv**: Contains user ratings for books.\n",
    "- **Users.csv**: Includes user demographic information.\n"

**Key Features**
This project uses several techniques to ensure accurate and meaningful recommendations:
**•	Data Cleaning and Exploration:** The dataset was prepared by removing duplicates, handling missing values, and conducting exploratory data analysis (EDA). Visualizations like bar charts and scatter plots were used to highlight patterns in book ratings and publication years.
**•	NLP Methods:**
o	Tokenization to break titles into individual words.
o	Lemmatization to reduce words to their base form for better matching.
o	TF-IDF vectorization to calculate the importance of words in book titles.
o	Cosine similarity to measure how closely user queries match book titles.
**•	Recommendation System:** Users can input phrases such as "mystery thriller" to receive a list of similar books, including titles, authors, and ratings.

**How to Use**
The system is implemented in a Jupyter Notebook. Users can clone the project, install the required Python libraries, and interact with the recommendation engine by running the provided cells. The process is straightforward and designed for ease of use.

**Improvements for the Future**
While the system works well for title-based recommendations, there are ways to make it even better:
•	Web Hosting: Hosting the system online through a tool like Flask or Streamlit would make it more accessible to users without programming knowledge.
•	Adding More Data: Including book descriptions, reviews, or genres would provide more context and improve the quality of recommendations.
•	Advanced NLP Models: Using pre-trained models like BERT could improve the system’s understanding of user queries and deliver more accurate results.
•	Scalability: Optimizing the system for larger datasets would allow it to handle more books and faster processing.
•	Personalization: Adding features like user profiles or tracking user preferences could make recommendations more tailored and dynamic.

**Conclusion**
This project shows how NLP can be used to build a practical recommendation system. By combining data cleaning, EDA, and advanced NLP techniques, the system delivers meaningful results for users. With further development, such as hosting the system online and adding advanced features, it could become a fully deployable platform that connects users with their next great read.


