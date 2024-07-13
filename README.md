# Dinakar Murthy's Data Portfolio

## About Me
<p>As a data scientist with a keen eye for detail, I blend my expertise in business analytics and computer engineering to drive impactful outcomes. My career is marked by developing precise predictive models, optimizing data processes, and significantly enhancing forecasting accuracy. Leveraging my proficiency in Python, SQL, and advanced data analysis techniques, I've consistently reduced operational costs and automated reporting processes, thereby streamlining decision-making and boosting organizational efficiency.</p>
<p>At Delivered Korea, I spearheaded the development of a Python-based sales prediction model using RFM analysis, achieving an impressive 90% accuracy rate. By integrating digital marketing metrics with internal data sources, I revolutionized our customer segmentation strategies. As a Research Assistant at San Francisco State University, I identified a critical gap in sales prediction models for emerging digital startups and developed a tailored solution that clinched first place at the CSU research conference.</p>
<p>My professional journey includes designing a robust relational database for financial transactions at Associated Students Inc. and leading the development of a geo-location web application for NGOs at Kinetrix. These experiences, coupled with academic projects in recommendation systems, sentiment analysis, and market analysis, have honed my ability to apply sophisticated machine learning techniques to real-world challenges.</p>
<p>Holding a Master's Degree in Business Analytics from San Francisco State University and a Bachelor's Degree in Computer Science and Engineering from PES University, I combine theoretical knowledge with practical expertise. My skill set spans machine learning, programming, data analysis, and statistical analysis, enabling me to thrive in data-driven environments and deliver innovative solutions that drive business growth.</p>

## Projects

### Anime Recommendation System

- **Motivation:**
    <p>As an avid anime enthusiast, I've long been captivated by the medium's vibrant characters, compelling narratives, and imaginative worlds. This passion led me to an intriguing realization: the joy of discovering new anime could be significantly enhanced through personalized recommendations. This insight sparked my journey to develop an Anime Recommendation System, a project that perfectly marries my love for anime with my expertise in data science and machine learning. The goal of this project was to create a sophisticated platform capable of suggesting anime titles based on individual preferences.</p>
        <p>By leveraging advanced algorithms and comprehensive datasets, I aimed to craft a personalized discovery experience for both myself and fellow anime aficionados. This endeavor presented an exciting opportunity to apply data-driven techniques to a domain I'm deeply passionate about. It allowed me to explore the intricate relationships between various anime attributes and viewer preferences, ultimately translating these insights into meaningful recommendations.</p>
    
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
  <p>My drive to create this sentiment analysis model stemmed from a fascination with the power of natural language processing to decode human emotions from text. As social media continues to shape public discourse, I recognized the immense value in developing tools that can accurately interpret the sentiments expressed in tweets and other online communications.</p>
      <p>This project offered an exciting opportunity to delve deep into the intricacies of text preprocessing and advanced neural network architectures, pushing the boundaries of my data science skills. By tackling the challenges of cleaning messy social media data and fine-tuning a complex model, I aimed to create a robust solution with real-world applications in market research, brand monitoring, and public opinion analysis. This endeavor not only allowed me to apply theoretical knowledge to a practical problem but also satisfied my curiosity about the intersection of linguistics and machine learning, fueling my passion for uncovering insights from unstructured data.</p>

- **Description:**
  <p>This project demonstrates sentiment analysis using a Long Short-Term Memory (LSTM) neural network. Sentiment analysis involves determining the sentiment (positive or negative) expressed in text data. In this project, we use a dataset of Twitter data to train an LSTM model to classify tweets as positive or negative.</p>

- **Tools and Technologies:**
   - Data Processing & Analysis: Pandas, NumPy, NLTK, Regular Expressions
   - Machine Learning & Deep Learning: TensorFlow, Keras, Scikit-learn
   - Data Visualization: Matplotlib, Seaborn
   - Auxiliary Libraries: String, Multiprocessing, Warnings

- **Dataset**: https://www.kaggle.com/datasets/kazanova/sentiment140

- **Dataset Description:**

  ![](https://private-user-images.githubusercontent.com/49876969/348441714-c06175e5-a6a4-4273-b3a6-d595e1f532fd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4MzUyMDQsIm5iZiI6MTcyMDgzNDkwNCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDE3MTQtYzA2MTc1ZTUtYTZhNC00MjczLWIzYTYtZDU5NWUxZjUzMmZkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDAxNDE0NFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPThjMTUxMmZhZTkxMWJiM2U3NDEzMGU4ZDMxZDA3Y2JkYTcyNDExMTU0MWNiNzdmOWQzZGRmNmJmODJkOTM5OGMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.MSgj3viWZZIcCsj58rRhGUN6bt34ktraH0iRBBoP4O0)


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

### Airfoil Sound Prediction
- **Motivation**:
  <p>This project is driven by the critical need to accurately predict sound levels generated by airfoils, a key factor in optimizing aerospace components. In an era where environmental impact and public acceptance are paramount, understanding and minimizing noise pollution from aircraft and other aerospace technologies has become increasingly important.</p>
      <p>By harnessing the capabilities of machine learning and big data analytics through Apache Spark, this project aims to develop a robust predictive model. This model will serve as a valuable tool for engineers and researchers, enabling data-driven decision-making in airfoil design and noise reduction strategies.</p>
      <p>The project encompasses several key phases. It begins with data preparation, involving the cleaning and preprocessing of a large dataset to ensure quality input for the model. This is followed by the construction of a scalable and efficient machine learning pipeline designed to handle big data effectively. Finally, the model undergoes rigorous evaluation using various regression metrics to assess its performance.</p>
      <p>The ultimate objective is to create a reliable, high-accuracy tool for predicting airfoil-generated sound levels. This endeavor not only addresses a significant challenge in aerospace engineering but also contributes to broader efforts in noise reduction and environmental sustainability in aviation.</p>
      <p>By bridging the gap between big data analytics and aerospace engineering, this project aims to drive innovation in airfoil design, potentially leading to quieter, more efficient aircraft and improved quality of life in areas affected by aviation noise.</p>

![](https://camo.githubusercontent.com/b43aaf71ea89eab01f6921bccdb8a5f93fc8f1589753676299752de36a856a0a/68747470733a2f2f63662d636f75727365732d646174612e73332e75732e636c6f75642d6f626a6563742d73746f726167652e617070646f6d61696e2e636c6f75642f49424d536b696c6c734e6574776f726b2d424430323331454e2d436f7572736572612f696d616765732f416972666f696c5f616e676c655f6f665f61747461636b2e6a7067)

![](https://camo.githubusercontent.com/157ef2b6c697b82c0b747a554167df1297119d43e84fc288f87afb6973d2a181/68747470733a2f2f63662d636f75727365732d646174612e73332e75732e636c6f75642d6f626a6563742d73746f726167652e617070646f6d61696e2e636c6f75642f49424d536b696c6c734e6574776f726b2d424430323331454e2d436f7572736572612f696d616765732f416972666f696c5f776974685f666c6f772e706e67)

- **Approach:**
  <p>In this project, I developed a robust predictive model for airfoil-generated sound levels utilizing Apache Spark and advanced machine learning techniques. The process began with the creation of a Spark session to efficiently manage data processing tasks. After acquiring the dataset, I loaded it into a Spark DataFrame and performed initial data cleaning, which included removing duplicate rows and addressing missing values.</p>
  <p>The data preprocessing phase involved renaming relevant columns for clarity and saving the cleaned data to a Parquet file, ensuring efficient storage and retrieval. Upon reloading the data, I designed a comprehensive machine learning pipeline incorporating feature vectorization, scaling, and linear regression.</p>
  <p>To prepare for modeling, I strategically split the dataset into training and testing sets. The pipeline model was then fitted to the training data and subsequently used to generate predictions on the test data. Model performance was rigorously evaluated using multiple regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).</p>
  <p>Throughout the development process, I prioritized best practices in code formatting and documentation, ensuring clarity and maintainability of the codebase. The final step involved saving the trained pipeline model for future applications.</p>
  <p>This structured approach resulted in the creation of an efficient and scalable predictive model capable of providing valuable insights into airfoil noise levels. The model serves as a powerful tool for engineers and researchers, facilitating data-driven decision-making in airfoil design and noise reduction strategies.</p>

- **Code Repository:** https://github.com/DSM2499/Airfoil_sound_predictions

- **Model Results:**
  
  ![](https://private-user-images.githubusercontent.com/49876969/348443921-5e673e4c-d2aa-4998-8558-30b233e56f6e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4Mzc2ODEsIm5iZiI6MTcyMDgzNzM4MSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0NDM5MjEtNWU2NzNlNGMtZDJhYS00OTk4LTg1NTgtMzBiMjMzZTU2ZjZlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDAyMjMwMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWZiOGQxODgzYmM0ODU2OThiMjE4NmM5ODIyNTk5M2VjMDM2Mzk2ZjE4ZTU1ZmY1ZjI3OGQ3MzNlMjJjYzg2NzUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.7k07WNmFJvSpX_iRMNpcxrFJn1El55qGuJ2Iv7LoNWQ)

- **Future Work:**

Future work on this project presents several promising avenues for enhancement and expansion:

<p>Model Sophistication: Incorporating more advanced machine learning techniques such as random forests, gradient boosting machines, or deep learning architectures could potentially yield improved prediction accuracy. These methods may capture complex relationships in the data that linear regression might miss.</p>
<p>Data Enrichment: Expanding the dataset with more diverse and comprehensive airfoil data could enhance the model's ability to generalize across various designs and operating conditions. This could involve collecting data from a wider range of airfoil types and environmental scenarios.</p>
<p>Real-time Analytics: Implementing a real-time data pipeline using Apache Kafka for streaming data and Spark Streaming for real-time analytics could enable continuous monitoring and prediction of noise levels. This would allow for more dynamic and responsive noise management strategies.</p>
<p>Advanced Feature Engineering: Conducting a more in-depth feature engineering process could uncover additional relevant attributes from the raw data. This might involve deriving new features based on domain knowledge or using automated feature extraction techniques, potentially leading to improved model performance and new insights.</p>
<p>User Interface Development: Integrating the predictive model into a web-based application with an intuitive interface would significantly enhance its accessibility and utility. This would allow engineers and researchers to easily interact with the model, facilitating its incorporation into their design and optimization processes.</p>
<p>By pursuing these enhancements, the project could evolve into a more comprehensive and powerful tool for airfoil noise prediction and management. These advancements would not only improve the model's accuracy and applicability but also increase its value in real-world aerospace engineering scenarios.</p>
