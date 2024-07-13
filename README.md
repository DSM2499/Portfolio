# Dinakar Murthy's Data Portfolio

## About Me
<p>As a data scientist with a keen eye for detail, I blend my expertise in business analytics and computer engineering to drive impactful outcomes. My career is marked by developing precise predictive models, optimizing data processes, and significantly enhancing forecasting accuracy. Leveraging my proficiency in Python, SQL, and advanced data analysis techniques, I've consistently reduced operational costs and automated reporting processes, thereby streamlining decision-making and boosting organizational efficiency.</p>
<p>At Delivered Korea, I spearheaded the development of a Python-based sales prediction model using RFM analysis, achieving an impressive 90% accuracy rate. By integrating digital marketing metrics with internal data sources, I revolutionized our customer segmentation strategies. As a Research Assistant at San Francisco State University, I identified a critical gap in sales prediction models for emerging digital startups and developed a tailored solution that clinched first place at the CSU research conference.</p>
<p>My professional journey includes designing a robust relational database for financial transactions at Associated Students Inc. and leading the development of a geo-location web application for NGOs at Kinetrix. These experiences, coupled with academic projects in recommendation systems, sentiment analysis, and market analysis, have honed my ability to apply sophisticated machine learning techniques to real-world challenges.</p>
<p>Holding a Master's Degree in Business Analytics from San Francisco State University and a Bachelor's Degree in Computer Science and Engineering from PES University, I combine theoretical knowledge with practical expertise. My skill set spans machine learning, programming, data analysis, and statistical analysis, enabling me to thrive in data-driven environments and deliver innovative solutions that drive business growth.</p>

## Projects

### Anime Recommendation System

- **Motivation:**
    <p>As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences. By leveraging advanced algorithms and comprehensive datasets, I aimed to craft a personalized discovery experience for both myself and fellow anime aficionados. This endeavor presented an exciting opportunity to apply data-driven techniques to a domain I'm deeply passionate about. It allowed me to explore the intricate relationships between various anime attributes and viewer preferences, ultimately translating these insights into meaningful recommendations.</p>
    
- **Description:**
  <p>This project involves creating a recommendation system for animes using collaborative filtering and content-based filtering techniques. The system is designed to provide personalized anime recommendations based on user preferences and anime attributes.</p>
- **Tools and Technologies:**
  <p>Python, Pandas, Scikit-learn, TensorFlow, Keras and tkinter</p>

- **Approach:**
  <p>The program implements a comprehensive anime recommendation system utilizing collaborative filtering and statistical analysis techniques. The process begins with data preprocessing, where user and anime data are imported, normalized, and encoded. Principal Component Analysis (PCA) is applied to reduce dimensionality, followed by KMeans clustering to identify user segments. The program extracts and normalizes embedding weights from a trained neural network model to find similar animes based on user preferences. The recommendation system is integrated with a graphical user interface (GUI) to allow users to input anime names and receive recommendations. </p> 

- **Data Exploration:**

  ![](https://private-user-images.githubusercontent.com/49876969/348380335-ef4f4ea2-e1d6-4d18-878f-cde8a93ab170.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MTk5MDIsIm5iZiI6MTcyMDgxOTYwMiwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODAzMzUtZWY0ZjRlYTItZTFkNi00ZDE4LTg3OGYtY2RlOGE5M2FiMTcwLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEyVDIxMjY0MlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTk2MmY5ZTY0MTRhMDMyMmQ1NTBiNWY5MzhlOTlhYzIxN2FkYzJkODUxMTQ0MWViNWQ3ZWNjZjY3MzBlMGU4NGMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0._mVeTB2VvipuurfhvUj5iFqUC1vj5fsRI7PtFpy3M8M)
  
  ![](https://private-user-images.githubusercontent.com/49876969/348380570-50d29ab5-6884-4857-8aa6-ec1ad8e5fc6b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MTk4NDYsIm5iZiI6MTcyMDgxOTU0NiwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA1NzAtNTBkMjlhYjUtNjg4NC00ODU3LThhYTYtZWMxYWQ4ZTVmYzZiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEyVDIxMjU0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWE0ZGViMTk1ZWUxNWExNDIxMGJhY2VlZmNhZTc1ODBlZmJmYThmNWFmOTlkZGZhMmZjYTFiNmMxNjRlNjg5OTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.LTQkkQH5Fclo5QMsEs7OxKIm8EyZFHF2i1mhUZKZhyQ)

  ![](https://private-user-images.githubusercontent.com/49876969/348380737-a9f69661-11c3-42a0-8a63-335db4adac22.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MTk5NzEsIm5iZiI6MTcyMDgxOTY3MSwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA3MzctYTlmNjk2NjEtMTFjMy00MmEwLThhNjMtMzM1ZGI0YWRhYzIyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEyVDIxMjc1MVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWY4ZDkxNWVkNmEwMDgwMjVjMTkwZTVhZjczNzE4NTg4NTM1YzU3MDZmNjU2OWI5MzQ0NjBlNDdmNzQ5ODZlMjMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.eptqtb4f_st5rxV6JhzFGHzg-KcyWbEpwol12C8o1gY)

- **Recommendation Output**
  
  ![](https://private-user-images.githubusercontent.com/49876969/348398404-c3905634-cca1-4d80-a51b-ecc255754ded.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MTk3NTMsIm5iZiI6MTcyMDgxOTQ1MywicGF0aCI6Ii80OTg3Njk2OS8zNDgzOTg0MDQtYzM5MDU2MzQtY2NhMS00ZDgwLWE1MWItZWNjMjU1NzU0ZGVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEyVDIxMjQxM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWY4ZmExNGI4YmI3OTM3OTdhMjE5OTY2MmYwZjJiZTg0NmFkZGM3ZTc4N2I3MGNhYjE0ZThkYjc5YmI1NGExNWMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.eqj9Jkp3cmtSWWQ5rsA_zOnekn81vSTgL2xBYhjDusE)

  ![](https://private-user-images.githubusercontent.com/49876969/348381609-7272e8ca-466b-4088-9045-d9b2a03ce0a9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MjA2NjcsIm5iZiI6MTcyMDgyMDM2NywicGF0aCI6Ii80OTg3Njk2OS8zNDgzODE2MDktNzI3MmU4Y2EtNDY2Yi00MDg4LTkwNDUtZDliMmEwM2NlMGE5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEyVDIxMzkyN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTZjOGNjYjc5NWJhYjBmYzRkNTg2NDgwNmM3MDI3NzA2MTYxMGNkOTcwOTFjYTMxZGQ3NzE2OTdjYzVmMjgzZTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.OIg5hMM6UFg0BDSczD-z-9E7Hy1PpOlxads80PxQBEY)

- **Code Repository:** https://github.com/DSM2499/recomendation_system

- Dataset: https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset

- **Results:**
  <p>Achieved a satisfactory level of accuracy and user satisfaction with the recommendations provided.</p>

- **Acknowledgement:**
   <p>In developing this Anime Recommendation System, I had the privilege of collaborating with my talented colleague, Sajid. Their exceptional design skills and collaborative spirit were instrumental in elevating this project from a data-driven concept to a fully-realized, user-friendly application. Sajid's 
   contributions were crucial in translating complex algorithms into an intuitive interface, significantly enhancing the user experience of our Anime Recommendation App.
   This collaboration underscores the importance of interdisciplinary teamwork in bringing data science projects to life. While my expertise lay in developing the underlying recommendation algorithms and data analysis, Sajid's design acumen ensured that our technical achievements were presented in an 
   accessible and visually appealing manner.
   Our partnership on this project exemplifies the synergy between data science and user experience design, resulting in a more robust and engaging final product. This experience has reinforced my belief in the power of diverse skill sets and collaborative problem-solving in tackling complex data challenges.
   I'm grateful for Sajid's invaluable contributions, which have undoubtedly enhanced the overall quality and impact of this project. Their involvement has not only improved the end result but also enriched my own learning experience, providing insights into the crucial role of design in data-driven 
   applications.</p>

- **Future Work**: Exploring hybrid recommendation systems and real-time recommendation updates.

### Sentiment Analysis

- **Motivation:**
  <p>My drive to create this sentiment analysis model stemmed from a fascination with the power of natural language processing to decode human emotions from text. As social media continues to shape public discourse, I recognized the immense value in developing tools that can accurately interpret the sentiments expressed in tweets and other online communications. This project offered an exciting opportunity to delve deep into the intricacies of text preprocessing and advanced neural network architectures, pushing the boundaries of my data science skills. By tackling the challenges of cleaning messy social media data and fine-tuning a complex model, I aimed to create a robust solution with real-world applications in market research, brand monitoring, and public opinion analysis. This endeavor not only allowed me to apply theoretical knowledge to a practical problem but also satisfied my curiosity about the intersection of linguistics and machine learning, fueling my passion for uncovering insights from unstructured data.</p>

- **Description:**
  <p>This project demonstrates sentiment analysis using a Long Short-Term Memory (LSTM) neural network. Sentiment analysis involves determining the sentiment (positive or negative) expressed in text data. In this project, we use a dataset of Twitter data to train an LSTM model to classify tweets as positive or negative.</p>

- **Tools and Technologies:**
   - Data Processing & Analysis: Pandas, NumPy, NLTK, Regular Expressions
   - Machine Learning & Deep Learning: TensorFlow, Keras, Scikit-learn
   - Data Visualization: Matplotlib, Seaborn
   - Auxiliary Libraries: String, Multiprocessing, Warnings

- **Dataset**: https://www.kaggle.com/datasets/kazanova/sentiment140

- **Dataset Description:**
  <p>This shows the dataset is eqyally distributed.</p>

![](https://private-user-images.githubusercontent.com/49876969/348440879-6ece24a9-37cb-4a3b-869f-15270496d705.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MzQxNjgsIm5iZiI6MTcyMDgzMzg2OCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDA4NzktNmVjZTI0YTktMzdjYi00YTNiLTg2OWYtMTUyNzA0OTZkNzA1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDAxMjQyOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTU5M2EzMzdkODg4NzhjMTNkMDBhMWFhZTlhMTNmOThhNWE3OTIxM2IwOGNlYTY5ZmY4Mzk0OGMzOTY2YWVmOTImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.DfrokxIj_p5qJKd3yow5yPRDnRvYH7G7h8SrP7VXcfs)

- **Code Repository**: https://github.com/DSM2499/sentiment_analysis

- **Results:**

  <p>The model demonstrates robust performance on unseen clean data, achieving an accuracy of 74.15%. This result is promising, indicating the model's ability to generalize to new instances. However, the training accuracy plateauing at approximately 75% suggests potential overfitting, as the gap between training and test accuracy is relatively small.

![](https://private-user-images.githubusercontent.com/49876969/348441027-26ee09d7-9d07-412b-8ed4-0d00051cbc73.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MzQzNDgsIm5iZiI6MTcyMDgzNDA0OCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDEwMjctMjZlZTA5ZDctOWQwNy00MTJiLThlZDQtMGQwMDA1MWNiYzczLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDAxMjcyOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTRmOGMzMjI0OWFiMTY1OGM1ZWIxNDcxNmI0Y2MxNmVmZTM2ZjM1MzIyMWM0ZjBmOTNiMzI3YTQwYzA5MGNiNzkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.oW3hJKPsS1fKPLQ0rUdvYJyLrkvdVi9aWTOGAhAMCUU)


To further enhance the model's performance, two primary avenues for improvement are identified:</p>
<p>Hyperparameter Tuning: Fine-tuning the model's hyperparameters could potentially mitigate overfitting and improve overall accuracy. This may involve adjusting learning rates, batch sizes, or the architecture of the neural network.</p>
<p>Data Quality Enhancement: Improving the quality and quantity of the training data could lead to better model performance. This might include gathering more diverse examples, implementing advanced data augmentation techniques, or refining the data cleaning process.</p>
<p>These observations provide valuable insights for future iterations of the model, highlighting the iterative nature of machine learning development and the continuous opportunities for refinement in sentiment analysis tasks.</p>
