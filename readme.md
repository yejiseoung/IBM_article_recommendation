# IBM Article Recommendations Project

## Proejct Description
This project is the part of Data Science Nanodegree Program by Udacity by analyzing the interactions that users have with articles on the IBM Watson Studio platform. The purpose of the current project is to build a recommendation model that recommends articles that users might have interests. The datasets contain each article's information including users' emails, article_id, titles, and document's description, etc. 


## Dependencies
- Python 3.5+
- Machine Learning Libraries: Numpy, Pandas, Sciki-Learn
- NLP Libraries: NLTK 
- Model Load: Pickle
- Visualization: matplotlib, seaborn


## File Descriptions
The files structure is arranged as below:

        - Data
            - articles_community.csv: data to process
            - user-item-interactions.csv: data to process
            - user_item_matrix.p: data to process
        
        - Recommendations_with_IBM.ipynb
            - Exploratory Data Analysis: data exploration, clean, wrangling
            - Rank Based Recommendations: build a recommendation model to find the most popular articles based on the most interactions. This model would be useful for new users who do not have any information in archive. 
            - User-User Based Collaborative Filtering: build a recommendation model based on similarities between users and items. 
            - Content Based Recommendations: build a recommendation model by using natural language processing (NLP).
            - Matrix Factorization: build a recommendation model based on the user-item interactions. We built a matrix decomposition, and saw how well the model can predict new articles that users interact with. 
            
        - README.md




## License
This is part of Data Science Nanodegree Udacity program project, and IBM provided the data. 