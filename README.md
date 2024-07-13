# Dinakar Murthy's Data Portfolio

## About Me

As a data scientist with a keen eye for detail, I blend my expertise in business analytics and computer engineering to drive impactful outcomes. My career is marked by developing precise predictive models, optimizing data processes, and significantly enhancing forecasting accuracy. Leveraging my proficiency in Python and advanced data analysis techniques, I've consistently reduced operational costs and automated reporting processes, thereby streamlining decision-making and boosting organizational efficiency.

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

- **Insights:**

   - **Insights from Genre Clustering:**
      - Cluster 0:
        
         ![Cluster 0](https://private-user-images.githubusercontent.com/49876969/348498557-4fc9c8b4-57dc-4378-bbfb-dec3c46ca373.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTgxNDAsIm5iZiI6MTcyMDg5Nzg0MCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg1NTctNGZjOWM4YjQtNTdkYy00Mzc4LWJiZmItZGVjM2M0NmNhMzczLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MTA0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQzMWYzZDhhMzM5YWUzYjQyMjI4ZDRkNmMxZDk0NTkwMDlhZGQ4NWE3NzIwZjI0Mjg4NjI1MWQ4YjE5MGFiYTImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Z8EhnIERMzHIdtI2o22faCAq-oX6d5AK3uaC0Nl2ZTk)

        Primary Genres: Comedy, Parody, School, Ecchi, Magic

        Insights: Audience preference for light-hearted, humorous content blending school settings with fantasy elements. Inclusion of Ecchi indicates acceptance of mature themes.

     - Cluster 1:

       ![Cluster 1](https://private-user-images.githubusercontent.com/49876969/348498569-5a86c20e-39c1-4779-b27e-c70b874e04bc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTgzMTAsIm5iZiI6MTcyMDg5ODAxMCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg1NjktNWE4NmMyMGUtMzljMS00Nzc5LWIyN2UtYzcwYjg3NGUwNGJjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MTMzMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWRmNzliZTI1M2VlOTAxNzA3ZGFkMDhlNzU0NTRkMjlhNWQ2NzNkODZhNmI0MWM4YzZiMTAyZWZhMWRmZjlmNmMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.OmS0MBw28NSH78EdGXmQ_EG4Yt8ZA-o1gAArWfTUCOk)

       Primary Genres: Fantasy, Adventure, Action, Comedy, Magic

       Insights: Strong attraction to imaginative, high-energy content featuring magical and action elements within fantasy settings.

     - Cluster 2:

       ![Cluster 2](https://private-user-images.githubusercontent.com/49876969/348498587-09af803c-5510-4305-a817-ee383a9be695.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTg0MTAsIm5iZiI6MTcyMDg5ODExMCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg1ODctMDlhZjgwM2MtNTUxMC00MzA1LWE4MTctZWUzODNhOWJlNjk1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MTUxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM2Zjg1OWJhMDBkMGVkYmFjODcwNjE4ODRkNjk5NzIyZTM2NzEyNWQ0YmIyMDg5YmU1NTRjZDgxMmQ2MzI3M2MmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.7QeHcr6PqU6U7sG4Rx9ykQPXjqo88E7qHZgbax4l2RA)

       Primary Genres: Romance, Comedy, School, Drama, Ecchi

       Insights: Clear preference for romantic narratives in school settings, with an appetite for emotional depth and some mature content.

     - Cluster 3:

       ![Cluster 3](https://private-user-images.githubusercontent.com/49876969/348498597-e1730133-3caf-4946-ab03-06ce5fa8cd7c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTg1MDIsIm5iZiI6MTcyMDg5ODIwMiwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg1OTctZTE3MzAxMzMtM2NhZi00OTQ2LWFiMDMtMDZjZTVmYThjZDdjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MTY0MlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTVkYmY2NzZjZGJmZjY5NzZhMjY4ODMwYmM4MjYzNmNjNDNlYWU2ZGY2NThiNmViZjFhNDdlYjc0N2QzN2ZjZDkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.nRhoLDwXccvdqd7mpjWEBY8GR3JzU6PgjAIvpwWL48I)

       Primary Genres: Sports, Shounen, Comedy, Drama, Action

       Insights: Dominance of sports-themed and youth-targeted content, appealing to viewers who enjoy competitive storylines with emotional and humorous elements.

     - Cluster 4:

       ![Cluster 4](https://private-user-images.githubusercontent.com/49876969/348498613-9d407ed2-9f12-4c6a-8cb8-c7f9b25c4f2b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTg1ODcsIm5iZiI6MTcyMDg5ODI4NywicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg2MTMtOWQ0MDdlZDItOWYxMi00YzZhLThjYjgtYzdmOWIyNWM0ZjJiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MTgwN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWYwZmIyNjdkZTQ1ZmUyZWFkZmM5ZjEwZmU4MTMwNGYwMWE1OTIwODJhMDAyZmIyNDc5OTgxMTcxYzc1YWNhN2MmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.nRJ9iFHBRkBYMTc-FnA45JpF1_5eKiVUmqy560Rh8G0)

       Primary Genres: Action, Supernatural, Comedy, Mystery, Shounen

       Insights: Audience drawn to action-packed supernatural themes, with a taste for complex plots and youth-centric narratives.

     - Cluster 5:

       ![Cluster 5](https://private-user-images.githubusercontent.com/49876969/348498651-962b6fad-a887-4f0a-9e9e-d8b1035a2fb6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTg2NzIsIm5iZiI6MTcyMDg5ODM3MiwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg2NTEtOTYyYjZmYWQtYTg4Ny00ZjBhLTllOWUtZDhiMTAzNWEyZmI2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MTkzMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTUzMmM1NGE5NjkxZGQ4YmZhYTVjMjIzMWMxNzU3NTNmYjAxYzkyMWRhMzEyNGVkM2ZiZTFiYWNlMjlhYjY2OGImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.mynbWGcVAa2-wcAX3dJYZpHhQXzfZjZFIDdD3bXMWIA)

       Primary Genres: Music, Comedy, Slice of Life, School, Drama

       Insights: Niche combining music themes with realistic, everyday stories, appealing to viewers seeking relatable content with emotional depth.

     - Cluster 6:

       ![Cluster 6](https://private-user-images.githubusercontent.com/49876969/348498673-57d1d677-4eeb-4d31-89f9-38bca94670b7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTg3MzksIm5iZiI6MTcyMDg5ODQzOSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg2NzMtNTdkMWQ2NzctNGVlYi00ZDMxLTg5ZjktMzhiY2E5NDY3MGI3LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MjAzOVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQyYzlkOWZmOGZmNjE2ZTEzYjAxYWQ5MTUzYTU5MmEzYjU2ZWFjM2Q1NDU0NDg4YjY4MDI3NzkzMzJmM2I3N2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.vWtQ1JTNwxq7n5nArmm-ethcMmHIFDS4SKlnvJQl41o)

       Primary Genres: Kids, Comedy, Fantasy, Adventure, Action

       Insights: Strong market for all-ages content, blending imaginative adventures with light-hearted comedy.

     - Cluster 7:

       ![Cluster 7](https://private-user-images.githubusercontent.com/49876969/348498683-c58411f3-a791-48c5-9845-db727800c3dc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTg4NjAsIm5iZiI6MTcyMDg5ODU2MCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg2ODMtYzU4NDExZjMtYTc5MS00OGM1LTk4NDUtZGI3Mjc4MDBjM2RjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MjI0MFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWVjMDU4ZWFmZjMxM2YyMzBhYjVmY2ZjYzNiYTUxOTcyOThiMjMxNDk1NzFmYzJjNTZjOGU2OTc4OWY2ZmMxYTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.jQBs9GlSb6mw_Yy26VEX8ZyFEY_8db-gh9VUFnc_Xok)

       Primary Genres: Hentai, School, Supernatural, Demons, Fantasy

       Insights: Distinct adult-oriented cluster with a focus on darker, fantasy-based narratives and supernatural themes.

     - Cluster 8:
    
        ![Cluster 8](https://private-user-images.githubusercontent.com/49876969/348498731-e737d870-bc4e-4e55-804d-e3bdda4ed929.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTkwMDUsIm5iZiI6MTcyMDg5ODcwNSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg3MzEtZTczN2Q4NzAtYmM0ZS00ZTU1LTgwNGQtZTNiZGRhNGVkOTI5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MjUwNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ1NzRkYjNiZTQxZTM5NjRmMTI3ODA2OGJmZWE1MmZhMDYyZmViY2FiNjE2NDc4NmU5Y2JhMGUwMmFmMDI2NDcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.tfmfqZS0YNNjp8Q5sqd8WTXoCI9h3vVVine0gI8UVwY)

       Primary Genres: Sci-Fi, Action, Mecha, Adventure, Comedy

       Insights: Clear audience for futuristic, high-energy content, particularly featuring advanced technology and robotic themes.

     - Cluster 9:

       ![Cluster 9](https://private-user-images.githubusercontent.com/49876969/348498744-ade3487a-a5ad-447e-850b-a13160f40296.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTkwNzUsIm5iZiI6MTcyMDg5ODc3NSwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTg3NDQtYWRlMzQ4N2EtYTVhZC00NDdlLTg1MGItYTEzMTYwZjQwMjk2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MjYxNVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ1YjJlMjBlNTAwNmZiMzUzOTA2MWY2NmI0YjljNTkxZjRmOTEyNDc4M2I5NjcwYTRjMGNiMmU0NzRkMDI2MWMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.v9tufABKKyDXps6ru6NTOi3oP39xleVoG9iwvpSdRT0)

       Primary Genres: Slice of Life, Comedy, School, Drama, Romance

       Insights: Strong preference for grounded, emotionally engaging stories focusing on everyday life and relationships.


  This cluster analysis provides a nuanced understanding of anime genre preferences, revealing distinct audience segments. These insights can      inform content creation strategies, marketing approaches, and programming decisions in the anime industry.

  - **Anime Duration**
 
    My analysis of anime episode durations reveals key trends in content structure and viewer preferences. These insights offer valuable 
    guidance for content creators, distributors, and streaming platforms in the anime industry.

    ![anime duration](https://private-user-images.githubusercontent.com/49876969/348499842-211daf36-ad5f-44ae-9a8b-e03f2f1e131d.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA4OTk0ODAsIm5iZiI6MTcyMDg5OTE4MCwicGF0aCI6Ii80OTg3Njk2OS8zNDg0OTk4NDItMjExZGFmMzYtYWQ1Zi00NGFlLTlhOGItZTAzZjJmMWUxMzFkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5MzMwMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTYwNWU4ZDAyMTIzN2Y4Y2NjOTFkZGU1OTNjMjg0YjdiNjc5Zjg3ODlmMDQxZGE1NmFhOWFiYWU1YTc3YTEyN2ImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.YNb_mB7nhu2cNlScRZ4cko6Ez2bt7JfrZl0fFU-8j0E)

    - Actionable Insights:
       - Maintain focus on standard 24-26 minute episodes to meet primary market demand.
       - Explore opportunities in short-form content (under 10 minutes) to capture quick-viewing audience segments.
       - Utilize shorter episodes in marketing campaigns to attract new viewers with lower time commitment barriers.
       - Create viewing pathways that gradually introduce users to longer-form content, fostering deeper engagement.

    Understanding the distribution of anime episode durations provides crucial insights for strategic decision-making in content creation, 
    platform design, and marketing within the anime industry. By leveraging these findings, stakeholders can enhance user engagement, streamline 
    content production, and develop more effective marketing strategies, ultimately driving growth and viewer satisfaction in the competitive 
    anime market.

  - **Audience Demographic Analysis:**

     ![user gender](https://private-user-images.githubusercontent.com/49876969/348500307-39fcbe96-c548-4ec0-adb6-b129cb6e59b2.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA5MDAyNzcsIm5iZiI6MTcyMDg5OTk3NywicGF0aCI6Ii80OTg3Njk2OS8zNDg1MDAzMDctMzlmY2JlOTYtYzU0OC00ZWMwLWFkYjYtYjEyOWNiNmU1OWIyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5NDYxN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTRhM2U3ZjE0NDU4OTFkM2NiODQzNjM4NDllMTU5MzE4ZmM3ZGE1M2I5MDQ4MGU3YWY2ZjQzNDZmOTIyMDVjNGUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.pKcIYE8jfbbZ2mPtBEgyGReDL2BJfLy2QhRsOvKlQCQ)

    ![user age](https://private-user-images.githubusercontent.com/49876969/348500310-349aa71d-c242-474e-919d-b2007bf0b5ba.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA5MDAyNzcsIm5iZiI6MTcyMDg5OTk3NywicGF0aCI6Ii80OTg3Njk2OS8zNDg1MDAzMTAtMzQ5YWE3MWQtYzI0Mi00NzRlLTkxOWQtYjIwMDdiZjBiNWJhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5NDYxN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWIwYjk1NWUwMTBhNWUxODVjMTM4MTgzNWU0OTMyODJjNzJjOWM4MGIwYWRmODFjYjdkMDg0ZjRiOWU2YjNiOGEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.DyHA63-crtZ5GLh7YCfSmd5G_-WMMdNPJPMfXCTwriE)

    ![user region](https://private-user-images.githubusercontent.com/49876969/348500314-e9198481-e5b0-43c9-afdf-4292437d0ddf.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA5MDAyNzcsIm5iZiI6MTcyMDg5OTk3NywicGF0aCI6Ii80OTg3Njk2OS8zNDg1MDAzMTQtZTkxOTg0ODEtZTViMC00M2M5LWFmZGYtNDI5MjQzN2QwZGRmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5NDYxN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTYzOTZiNTAyM2YwZTg1ZjA3MGQ5MDJkODY2NzU4Mjg1NTgyMTMwZTdiMzFhODcwODNjMDJhNTI5NGYwZWIwMzAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.fTXo0U35AGNK-3mQY24IdUKYhgeL2bKjIZgNfuUoc0A)

    <p>Our analysis of the anime community reveals a predominantly male audience with significant female representation and a small non-binary user base. The largest demographic consists of users in their early thirties, followed by young adults, with a global reach that includes notable concentrations in Poland, Germany, Brazil, Canada, and several European countries. This diverse audience composition provides valuable guidance for content creation, marketing, and platform development in the anime industry.</p>

    <p>To effectively engage this audience, content strategies should focus on developing gender-inclusive anime that appeals to both male and female viewers while also incorporating themes that resonate with non-binary individuals. Marketing campaigns can be localized to target countries with high user concentrations, with messaging tailored to the predominant age groups. Platform developers should prioritize age-appropriate content recommendations, offer customization options for different gender identities, and implement region-specific features. By leveraging these demographic insights, stakeholders in the anime industry can create more inclusive and engaging experiences, potentially expanding their user base and deepening audience engagement across various demographic segments.</p>

  - **User Engagement Analysis:**

     ![user engagement 1](https://private-user-images.githubusercontent.com/49876969/348500634-48667f5f-4113-49df-b6ba-53605f6b5c16.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA5MDA4MTEsIm5iZiI6MTcyMDkwMDUxMSwicGF0aCI6Ii80OTg3Njk2OS8zNDg1MDA2MzQtNDg2NjdmNWYtNDExMy00OWRmLWI2YmEtNTM2MDVmNmI1YzE2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5NTUxMVomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWNlYzVkNmM3NzEwMmM0Y2JmN2MyYWU5ZDQzYzg3M2JkZWM0ZjcwN2UwNTZmOTA1YWMzZTFlNGMyZDM3Yzg5YjYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.la4BNgsSNMEYR6Di1a3cRh6xy6JV57Y5zP6NgxHdHE4)

    ![user engagement 2](https://private-user-images.githubusercontent.com/49876969/348500640-9ad68602-fcb8-4e1c-99c9-db49a4375d42.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjA5MDA4MTIsIm5iZiI6MTcyMDkwMDUxMiwicGF0aCI6Ii80OTg3Njk2OS8zNDg1MDA2NDAtOWFkNjg2MDItZmNiOC00ZTFjLTk5YzktZGI0OWE0Mzc1ZDQyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MTMlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzEzVDE5NTUxMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTIwMzY0MGJlYzIxNTM2Mzg0OTFlN2QwODljMzQ0NDRjNTQwYWNmZmNiNTM0NmU5MjQyZmQ2Nzk5Y2FlOWUyNjMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.szFIIWGk439IsM3hpPTTv7N3S_RWPykDFOaLckSrYyA)

    <p>Anime audience engagement analysis reveals significant trends across gender and age demographics, providing actionable insights for content strategy, marketing, and user experience optimization. Users across all genders demonstrate high completion rates and substantial interest in planning future anime viewing, indicating strong content satisfaction and potential for sustained engagement. Age-wise, engagement peaks in the early 20s and mid-40s, with steady interest across the 25-35 age range, suggesting targeted demographics for focused marketing efforts. However, a notable decline in engagement beyond age 50 presents an opportunity for tailored content and outreach strategies to retain older viewers.</p>

    <p>To capitalize on these insights, content creators should focus on genres with high completion rates and promote upcoming releases to leverage the high 'plan to watch' counts. Marketing campaigns should be tailored to highly engaged age groups and gender preferences, with special attention to developing strategies that appeal to users over 50. Enhancing user experience through personalized recommendations based on completion and planning patterns can further boost engagement. Additionally, addressing the higher drop rates among Non-Binary users through content refinement and implementing community-building features like forums or watch parties can foster deeper user involvement. By integrating these strategies, stakeholders in the anime industry can optimize user engagement, retention, and overall satisfaction across diverse demographic segments.</p>


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

- **Inferences:**
  
  - **Model Performance:**
    - The R-squared value of 0.42 indicates that the model explains about 42% of the variance in the sound levels. While this is a moderate level of explanatory power, it suggests that there are other factors influencing the sound levels that are not captured by the model.
    - The Mean Squared Error (MSE) and Mean Absolute Error (MAE) values indicate the average magnitude of the errors in the model's predictions. The MAE of 3.88 suggests that on average, the model's predictions are off by about 3.88 decibels.

  - **Impact of Features:**
    - **Frequency**: The negative coefficient (-0.00136) suggests that higher frequencies are associated with slightly lower sound levels. This effect is small but consistent.
    - **Angle of Attack**: The negative coefficient (-0.349) indicates that an increase in the angle of attack reduces the sound levels. This suggests that modifying the angle of attack could be a practical way to manage noise levels.
    - **Chord Length**: The significant negative coefficient (-34.41) shows that larger chord lengths are strongly associated with lower sound levels. This suggests that increasing the chord length can significantly reduce noise.
    - **Free Stream Velocity**: The positive coefficient (0.104) indicates that higher free stream velocities are associated with higher sound levels, though the effect is relatively small.
    - **Suction Side Displacement**: The large negative coefficient (-171.16) indicates that increasing the suction side displacement thickness can lead to a significant reduction in noise levels.

  - **Practical Insights:**
    - **Design Adjustments:**
      - **Chord Length**: Given the strong negative impact of chord length on sound levels, designers of airfoils can consider increasing the chord length to reduce noise. This could be particularly useful in applications where noise reduction is critical, such as in commercial aviation or urban drone delivery systems.
      - **Suction Side Displacement**: The significant impact of suction side displacement thickness suggests that adjustments in the airfoil design to increase this thickness can effectively reduce noise levels. This could involve modifications in the surface geometry or the use of materials that enhance this displacement.
  - **Operational Strategies:**
      - **Angle of Attack**: Pilots and operators can adjust the angle of attack during flight operations to manage noise levels. For instance, during takeoff and landing, where noise is a significant concern, adjusting the angle of attack to optimal levels can help minimize noise pollution.
      - **Velocity Management**: Controlling the free stream velocity can be another strategy to manage noise, especially in environments where reducing noise is essential. This might involve optimizing flight paths and speeds to balance performance and noise levels.
  - **Further Research:**
      - The moderate R-squared value suggests that further research is needed to identify additional factors influencing sound levels. This could involve exploring other aerodynamic parameters, material properties, or environmental conditions.
      - Advanced modeling techniques, such as non-linear models or machine learning approaches, could be employed to capture more complex relationships and improve the predictive power of the model.

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
