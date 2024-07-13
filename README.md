# Dinakar Murthy's Data Portfolio

## About Me

As a data scientist with a keen eye for detail, I blend my expertise in business analytics and computer engineering to drive impactful outcomes. My career is marked by developing precise predictive models, optimizing data processes, and significantly enhancing forecasting accuracy. Leveraging my proficiency in Python, SQL, and advanced data analysis techniques, I've consistently reduced operational costs and automated reporting processes, thereby streamlining decision-making and boosting organizational efficiency.

At Delivered Korea, I spearheaded the development of a Python-based sales prediction model using RFM analysis, achieving an impressive 90% accuracy rate. By integrating digital marketing metrics with internal data sources, I revolutionized our customer segmentation strategies. As a Research Assistant at San Francisco State University, I identified a critical gap in sales prediction models for emerging digital startups and developed a tailored solution that clinched first place at the CSU research conference.

My professional journey includes designing a robust relational database for financial transactions at Associated Students Inc. and leading the development of a geo-location web application for NGOs at Kinetrix. These experiences, coupled with academic projects in recommendation systems, sentiment analysis, and market analysis, have honed my ability to apply sophisticated machine learning techniques to real-world challenges.

Holding a Master's Degree in Business Analytics from San Francisco State University and a Bachelor's Degree in Computer Science and Engineering from PES University, I combine theoretical knowledge with practical expertise. My skill set spans machine learning, programming, data analysis, and statistical analysis, enabling me to thrive in data-driven environments and deliver innovative solutions that drive business growth.

## Projects

### Anime Recommendation System

- **Motivation:**
    As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences.
    
    By leveraging advanced algorithms and comprehensive datasets, I aimed to craft a personalized discovery experience for both myself and fellow anime aficionados. This endeavor presented an exciting opportunity to apply data-driven techniques to a domain I'm deeply passionate about. It allowed me to explore the intricate relationships between various anime attributes and viewer preferences, ultimately translating these insights into meaningful recommendations.
    
- **Description:**
    This project involves creating a recommendation system for animes using collaborative filtering and content-based filtering techniques. The system is designed to provide personalized anime recommendations based on user preferences and anime attributes.
    
- **Tools and Technologies:**
    Python, Pandas, Scikit-learn, TensorFlow, Keras, and tkinter
    
- **Approach:**
    The program implements a comprehensive anime recommendation system utilizing collaborative filtering and statistical analysis techniques. The process begins with data preprocessing, where user and anime data are imported, normalized, and encoded. Principal Component Analysis (PCA) is applied to reduce dimensionality, followed by KMeans clustering to identify user segments. The program extracts and normalizes embedding weights from a trained neural network model to find similar animes based on user preferences. The recommendation system is integrated with a graphical user interface (GUI) to allow users to input anime names and receive recommendations.
    
- **Data Exploration:**

  ![Data Exploration 1](https://private-user-images.githubusercontent.com/49876969/348380335-ef4f4ea2-e1d6-4d18-878f-cde8a93ab170.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYxNDQsIm5iZiI6MTcyMDg5NTg0NCwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODAzMzUtZWY0ZjRlYTItZTFkNi00ZDE4LTg3OGYtY2RlOGE5M2FiMTcwLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzcyNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTBkYWFjNTgyMmE1OWYzNGI1ZjRmYTNjMjZiMTFhODNmOTZlZWE2NWQxNDM5OWEzY2E3M2M4ODNkMTViOWE4ZDMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.GIh-1CFubswbJ-NFzWtiOY-p8aXaTtrmfZIev1yoG0M)

  ![Data Exploration 2](https://private-user-images.githubusercontent.com/49876969/348380570-50d29ab5-6884-4857-8aa6-ec1ad8e5fc6b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYxOTAsIm5iZiI6MTcyMDg5NTg5MCwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA1NzAtNTBkMjlhYjUtNjg4NC00ODU3LThhYTYtZWMxYWQ4ZTVmYzZiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzgxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWExODVlNjM1MWJhZjg0NDI2ODYxNmRiMGUxMjZhNDBjYmM5MTVhOTdiNTZjODQ4NjE3ZTdkNDc4ZTQ2NDU2NzEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.XF1wLvQc0Rm0PPSSgdp6Ll1_UlNFJLGscqJqW_gsYhg)

  ![Data Exploration 3](https://private-user-images.githubusercontent.com/49876969/348380737-a9f69661-11c3-42a0-8a63-335db4adac22.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYyMTksIm5iZiI6MTcyMDg5NTkxOSwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODA3MzctYTlmNjk2NjEtMTFjMy00MmEwLThhNjMtMzM1ZGI0YWRhYzIyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzgzOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE2ZmQ3NTk0OTdlOTNlOWFlMzg3MjQ5YmYzOWU4YWUzMjU3M2YyMWNjMDFkYmM0NjFmNWI3ZDEyZDUzNjIzZGQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.U7JvG-jcEVZlav-7aDCqxyJQFOanrUA7snGe01SDias)

- **Recommendation Output:**

  ![Recommendation Output 1](https://private-user-images.githubusercontent.com/49876969/348381609-7272e8ca-466b-4088-9045-d9b2a03ce0a9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYyNTksIm5iZiI6MTcyMDg5NTk1OSwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODE2MDktNzI3MmU4Y2EtNDY2Yi00MDg4LTkwNDUtZDliMmEwM2NlMGE5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4MzkxOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE0NDc4NGFmMmVjN2IzNmExZmJlYzc4MGQ2MDFiZmRlNWE3N2E1ZGQ3ZTZlN2RmMTI0YTYwM2UxNjliOWM1YWMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Bo7BqyOP3mDAtSnRyMHV8zOltpdz3KuVeLj47JiHNlY)

  ![Recommendation Output 2](https://private-user-images.githubusercontent.com/49876969/348381075-76be8b6e-4768-45a7-9312-75cd9f7e3077.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYyODAsIm5iZiI6MTcyMDg5NTk4MCwicGF0aCI6Ii80OTg3Njk2OS8zNDgzODEwNzUtNzZiZThiNmUtNDc2OC00NWE3LTkzMTItNzVjZDlmN2UzMDc3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4Mzk0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWMwYTJjMjQxNzI5ZmMzZTQ4ZDIwZDI0MGM3Yzk2ZWZmODc3NDk3MDU3ODk5OWUzZDczYjliYmQ0OWZkNjk3ZTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Y3d2ubxLGvNB_lSzONnBXtXTWnUxDaPAUuhrYWdz4XY)

  ![Recommendation Outpout 3](https://private-user-images.githubusercontent.com/49876969/348398404-c3905634-cca1-4d80-a51b-ecc255754ded.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYzMjIsIm5iZiI6MTcyMDg5NjAyMiwicGF0aCI6Ii80OTg3Njk2OS8zNDgzOTg0MDQtYzM5MDU2MzQtY2NhMS00ZDgwLWE1MWItZWNjMjU1NzU0ZGVkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDAyMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTIxMmU5NWUzYmZiYzBiMDZjMWY1OWM0MDY4OTUxYTZkZTY4ODRmZDQ2ZmMyMzk1NTBkYWU4YjBhODA1OTI5NDkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.9m17nDsQ_ai6dC2TIocfFuipv37gACYVR0j9aky1TcQ)

- **Code Repository:**
    [Anime Recommendation System](https://github.com/DSM2499/recomendation_system)

- **Dataset:**
    [MyAnimeList Dataset](https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset)

- **Results:**
    Achieved a satisfactory level of accuracy and user satisfaction with the recommendations provided.

- **Acknowledgement:**
    In developing this Anime Recommendation System, I had the privilege of collaborating with my talented colleague, Sajid. Their exceptional design skills and collaborative spirit were instrumental in elevating this project from a data-driven concept to a fully-realized, user-friendly application. Sajid's contributions were crucial in translating complex algorithms into an intuitive interface, significantly enhancing the user experience of our Anime Recommendation App.
    
    This collaboration underscores the importance of interdisciplinary teamwork in bringing data science projects to life. While my expertise lay in developing the underlying recommendation algorithms and data analysis, Sajid's design acumen ensured that our technical achievements were presented in an accessible and visually appealing manner.
    
    Our partnership on this project exemplifies the synergy between data science and user experience design, resulting in a more robust and engaging final product. This experience has reinforced my belief in the power of diverse skill sets and collaborative problem-solving in tackling complex data challenges.
    
    I'm grateful for Sajid's invaluable contributions, which have undoubtedly enhanced the overall quality and impact of this project. Their involvement has not only improved the end result but also enriched my own learning experience, providing insights into the crucial role of design in data-driven applications.
    
- **Future Work:**
    Exploring hybrid recommendation systems and real-time recommendation updates.

### Sentiment Analysis

- **Motivation:**
    My drive to create this sentiment analysis model stemmed from a fascination with the power of natural language processing to decode human emotions from text. As social media continues to shape public discourse, I recognized the immense value in developing tools that can accurately interpret the sentiments expressed in tweets and other online communications.
    
    This project offered an exciting opportunity to delve deep into the intricacies of text preprocessing and advanced neural network architectures, pushing the boundaries of my data science skills. By tackling the challenges of cleaning messy social media data and fine-tuning a complex model, I aimed to create a robust solution with real-world applications in market research, brand monitoring, and public opinion analysis. This endeavor not only allowed me to apply theoretical knowledge to a practical problem but also satisfied my curiosity about the intersection of linguistics and machine learning, fueling my passion for uncovering insights from unstructured data.
    
- **Description:**
    This project demonstrates sentiment analysis using a Long Short-Term Memory (LSTM) neural network. Sentiment analysis involves determining the sentiment (positive or negative) expressed in text data. In this project, we use a dataset of Twitter data to train an LSTM model to classify tweets as positive or negative.
    
- **Tools and Technologies:**
    - Data Processing & Analysis: Pandas, NumPy, NLTK, Regular Expressions
    - Machine Learning & Deep Learning: TensorFlow, Keras, Scikit-learn
    - Data Visualization: Matplotlib, Seaborn
    - Auxiliary Libraries: String, Multiprocessing, Warnings
    
- **Dataset:**
    [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
    
- **Dataset Description:**

  ![Dataset Description 1](https://private-user-images.githubusercontent.com/49876969/348441714-c06175e5-a6a4-4273-b3a6-d595e1f532fd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTYzODUsIm5iZiI6MTcyMDg5NjA4NSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDE3MTQtYzA2MTc1ZTUtYTZhNC00MjczLWIzYTYtZDU5NWUxZjUzMmZkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDEyNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWU1OWI4M2Y3MjUyYzRjOGUwMTdkMzRjZDRlYTY1YWQ0NTg4NGIzNTM4ZjIwYjFhYTAyOTI0MzViN2FjMmRmOWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.J2nz0YPQS2XiAjnm-oRDPk75n0iNYXa5LnHMOp1BlRI)
  
  ![Dataset Description 2](https://private-user-images.githubusercontent.com/49876969/348440879-6ece24a9-37cb-4a3b-869f-15270496d705.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTY0MDksIm5iZiI6MTcyMDg5NjEwOSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDA4NzktNmVjZTI0YTktMzdjYi00YTNiLTg2OWYtMTUyNzA0OTZkNzA1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDE0OVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ1MTMzZmNiMmU0NDM1YmRhOGVlODdlNmEzZWEyNjBlNGEzODI2NzA5NTRiNjRjNzIwNzJlNTg1YmVjNDk3ZWUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.0BtoL-Dn8fSDN5QMB1dhFVPsXZKEXZglPNnaxdsIw7Y)

- **Code Repository:**
    [Sentiment Analysis](https://github.com/DSM2499/sentiment_analysis)

- **Results:**
    The model demonstrates robust performance on unseen clean data, achieving an accuracy of 74.15%. This result is promising, indicating the model's ability to generalize to new instances. However, the training accuracy plateauing at approximately 75% suggests potential overfitting, as the gap between training and test accuracy is relatively small.

  ![Model Results](https://private-user-images.githubusercontent.com/49876969/348441027-26ee09d7-9d07-412b-8ed4-0d00051cbc73.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTY0MzEsIm5iZiI6MTcyMDg5NjEzMSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDEwMjctMjZlZTA5ZDctOWQwNy00MTJiLThlZDQtMGQwMDA1MWNiYzczLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDIxMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWEwYjQ4NTRhNDc3NDcxZjViYmU3NDZlOTM4ZDdlMTk4YTFiMDJmYTM2ZDk4NjM4Y2M0MGM5ZTBmMjBjZjcxOGImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.iIyhEfecljeOvpLS3BL4W_yJEsZIX-fNhnGGM0ywgn4)

To further enhance the model's performance, two primary avenues for improvement are identified:
- **Hyperparameter Tuning:** Fine-tuning the model's hyperparameters could potentially mitigate overfitting and improve overall accuracy. This may involve adjusting learning rates, batch sizes, or the architecture of the neural network.
- **Data Quality Enhancement:** Improving the quality and quantity of the training data could lead to better model performance. This might include gathering more diverse examples, implementing advanced data augmentation techniques, or refining the data cleaning process.

These observations provide valuable insights for future iterations of the model, highlighting the iterative nature of machine learning development and the continuous opportunities for refinement in sentiment analysis tasks.

### Airfoil Sound Prediction

- **Motivation:**
    This project is driven by the critical need to accurately predict sound levels generated by airfoils, a key factor in optimizing aerospace components. In an era where environmental impact and public acceptance are paramount, understanding and minimizing noise pollution from aircraft and other aerospace technologies has become increasingly important.
    
    By harnessing the capabilities of machine learning and big data analytics through Apache Spark, this project aims to develop a robust predictive model. This model will serve as a valuable tool for engineers and researchers, enabling data-driven decision-making in airfoil design and noise reduction strategies.
    
    The project encompasses several key phases. It begins with data preparation, involving the cleaning and preprocessing of a large dataset to ensure quality input for the model. This is followed by the construction of a scalable and efficient machine learning pipeline designed to handle big data effectively. Finally, the model undergoes rigorous evaluation using various regression metrics to assess its performance.
    
    The ultimate objective is to create a reliable, high-accuracy tool for predicting airfoil-generated sound levels. This endeavor not only addresses a significant challenge in aerospace engineering but also contributes to broader efforts in noise reduction and environmental sustainability in aviation.
    
    By bridging the gap between big data analytics and aerospace engineering, this project aims to drive innovation in airfoil design, potentially leading to quieter, more efficient aircraft and improved quality of life in areas affected by aviation noise.

  ![Airfoil Sound Prediction 1](https://camo.githubusercontent.com/b43aaf71ea89eab01f6921bccdb8a5f93fc8f1589753676299752de36a856a0a/68747470733a2f2f63662d636f75727365732d646174612e73332e75732e636c6f75642d6f626a6563742d73746f726167652e617070646f6d61696e2e636c6f75642f49424d536b696c6c734e6574776f726b2d424430323331454e2d436f7572736572612f696d616765732f416972666f696c5f616e676c655f6f665f61747461636b2e6a7067)

  ![Airfoil Sound Prediction 2](https://camo.githubusercontent.com/157ef2b6c697b82c0b747a554167df1297119d43e84fc288f87afb6973d2a181/68747470733a2f2f63662d636f75727365732d646174612e73332e75732e636c6f75642d6f626a6563742d73746f726167652e617070646f6d61696e2e636c6f75642f49424d536b696c6c734e6574776f726b2d424430323331454e2d436f7572736572612f696d616765732f416972666f696c5f776974685f666c6f772e706e67)

- **Approach:**
    In this project, I developed a robust predictive model for airfoil-generated sound levels utilizing Apache Spark and advanced machine learning techniques. The process began with the creation of a Spark session to efficiently manage data processing tasks. After acquiring the dataset, I loaded it into a Spark DataFrame and performed initial data cleaning, which included removing duplicate rows and addressing missing values.
    
    The data preprocessing phase involved renaming relevant columns for clarity and saving the cleaned data to a Parquet file, ensuring efficient storage and retrieval. Upon reloading the data, I designed a comprehensive machine learning pipeline incorporating feature vectorization, scaling, and linear regression.
    
    To prepare for modeling, I strategically split the dataset into training and testing sets. The pipeline model was then fitted to the training data and subsequently used to generate predictions on the test data. Model performance was rigorously evaluated using multiple regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
    
    Throughout the development process, I prioritized best practices in code formatting and documentation, ensuring clarity and maintainability of the codebase. The final step involved saving the trained pipeline model for future applications.
    
    This structured approach resulted in the creation of an efficient and scalable predictive model capable of providing valuable insights into airfoil noise levels. The model serves as a powerful tool for engineers and researchers, facilitating data-driven decision-making in airfoil design and noise reduction strategies.

- **Dataset Description:**

    Dataset: [NASA Airfoil Noise Raw](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/datasets/NASA_airfoil_noise_raw.csv)

  ![Dataset Description](https://private-user-images.githubusercontent.com/49876969/348444479-633b2fe6-87ab-48d7-89a0-bb4f9cab3ee9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTY0NjMsIm5iZiI6MTcyMDg5NjE2MywicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDQ0NzktNjMzYjJmZTYtODdhYi00OGQ3LTg5YTAtYmI0ZjljYWIzZWU5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDI0M1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTAxMjYwZTRlZmE2MGI5ZTNiMWVlOTYwZTRkOTYwM2ExMzVkOGE2Nzg0ZThlM2FlNjY4NTA0OWZhNDI0NzkyOTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.TiaULMbUV5HW9NlQRRJMItkGIymX7KkNhQUENdw3NFw)
  
- **Code Repository:**
    [Airfoil Sound Prediction](https://github.com/DSM2499/Airfoil_sound_predictions)

- **Model Results:**

  ![Model Results](https://private-user-images.githubusercontent.com/49876969/348443921-5e673e4c-d2aa-4998-8558-30b233e56f6e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTY0ODIsIm5iZiI6MTcyMDg5NjE4MiwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDM5MjEtNWU2NzNlNGMtZDJhYS00OTk4LTg1NTgtMzBiMjMzZTU2ZjZlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE4NDMwMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWNkMzIyZjEyMTk1NTk2ZGFiMTlhOTBmNGFkM2NlZTc3NThiY2Y2ODkwMDg0NjNmMDA0NDNhZmI4YTAyMDkwYjImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.PwP6a_bz7dngUFbY4tTnCIzrYxinsnOwbc05LSyYYWc)

- **Future Work:**

Future work on this project presents several promising avenues for enhancement and expansion:
- **Model Sophistication:** Incorporating more advanced machine learning techniques such as random forests, gradient boosting machines, or deep learning architectures could potentially yield improved prediction accuracy. These methods may capture complex relationships in the data that linear regression might miss.
- **Data Enrichment:** Expanding the dataset with more diverse and comprehensive airfoil data could enhance the model's ability to generalize across various designs and operating conditions. This could involve collecting data from a wider range of airfoil types and environmental scenarios.
- **Real-time Analytics:** Implementing a real-time data pipeline using Apache Kafka for streaming data and Spark Streaming for real-time analytics could enable continuous monitoring and prediction of noise levels. This would allow for more dynamic and responsive noise management strategies.
- **Advanced Feature Engineering:** Conducting a more in-depth feature engineering process could uncover additional relevant attributes from the raw data. This might involve deriving new features based on domain knowledge or using automated feature extraction techniques, potentially leading to improved model performance and new insights.
- **User Interface Development:** Integrating the predictive model into a web-based application with an intuitive interface would significantly enhance its accessibility and utility. This would allow engineers and researchers to easily interact with the model, facilitating its incorporation into their design and optimization processes.

By pursuing these enhancements, the project could evolve into a more comprehensive and powerful tool for airfoil noise prediction and management. These advancements would not only improve the model's accuracy and applicability but also increase its value in real-world aerospace engineering scenarios.

## Conclusion

As we conclude this portfolio, it's evident that the journey through data science is one of continuous learning and innovation. Each project presented here represents not just a solution to a specific problem, but a step forward in my understanding of data's power to drive insights and decisions.

From developing sentiment analysis models to predicting airfoil-generated sound levels, these projects showcase my ability to tackle diverse challenges across various domains. They demonstrate my proficiency in data preprocessing, machine learning model development, and results interpretation, as well as my commitment to producing scalable, efficient solutions.

However, this portfolio is not just a reflection of past accomplishments. It's a foundation for future growth and exploration. The field of data science is rapidly evolving, and I am excited to continue pushing the boundaries of what's possible with data.

I look forward to taking on new challenges, exploring cutting-edge technologies, and contributing to impactful projects that harness the full potential of data science. Whether it's diving deeper into advanced machine learning techniques, exploring real-time analytics, or developing more intuitive ways to present complex data, I am committed to expanding my skills and knowledge.

Thank you for taking the time to explore my work. I welcome opportunities to discuss how my skills and passion for data science can contribute to solving real-world problems and driving innovation in your organization.
