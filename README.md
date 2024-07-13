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

  ![Data Exploration 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/Anime%20Distribution.png?raw=true)

  ![Data Exploration 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/Anime%20through%20the%20years.png?raw=true)

  ![Data Exploration 3](https://github.com/DSM2499/Portfolio/blob/main/Photos/Clustering%20for%20users.png?raw=true)

- **Recommendation Output:**

  ![Recommendation Output 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/Recommendation%20Example.png?raw=true)

  ![Recommendation Output 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/Training%20loss%20VS%20Validation%20Loss.png?raw=true)

  ![Recommendation Outpout 3](https://github.com/DSM2499/Portfolio/blob/main/Photos/RecommendationGUI.png?raw=true)

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
        
         ![Cluster 0](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%200.png?raw=true)

        Primary Genres: Comedy, Parody, School, Ecchi, Magic

        Insights: Audience preference for light-hearted, humorous content blending school settings with fantasy elements. Inclusion of Ecchi indicates acceptance of mature themes.

     - Cluster 1:

       ![Cluster 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%201.png?raw=true)

       Primary Genres: Fantasy, Adventure, Action, Comedy, Magic

       Insights: Strong attraction to imaginative, high-energy content featuring magical and action elements within fantasy settings.

     - Cluster 2:

       ![Cluster 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%202.png?raw=true)

       Primary Genres: Romance, Comedy, School, Drama, Ecchi

       Insights: Clear preference for romantic narratives in school settings, with an appetite for emotional depth and some mature content.

     - Cluster 3:

       ![Cluster 3](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%203.png?raw=true)

       Primary Genres: Sports, Shounen, Comedy, Drama, Action

       Insights: Dominance of sports-themed and youth-targeted content, appealing to viewers who enjoy competitive storylines with emotional and humorous elements.

     - Cluster 4:

       ![Cluster 4](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%204.png?raw=true)

       Primary Genres: Action, Supernatural, Comedy, Mystery, Shounen

       Insights: Audience drawn to action-packed supernatural themes, with a taste for complex plots and youth-centric narratives.

     - Cluster 5:

       ![Cluster 5](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%205.png?raw=true)

       Primary Genres: Music, Comedy, Slice of Life, School, Drama

       Insights: Niche combining music themes with realistic, everyday stories, appealing to viewers seeking relatable content with emotional depth.

     - Cluster 6:

       ![Cluster 6](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%206.png?raw=true)

       Primary Genres: Kids, Comedy, Fantasy, Adventure, Action

       Insights: Strong market for all-ages content, blending imaginative adventures with light-hearted comedy.

     - Cluster 7:

       ![Cluster 7](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%207.png?raw=true)

       Primary Genres: Hentai, School, Supernatural, Demons, Fantasy

       Insights: Distinct adult-oriented cluster with a focus on darker, fantasy-based narratives and supernatural themes.

     - Cluster 8:
    
        ![Cluster 8](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%208.png?raw=true)

       Primary Genres: Sci-Fi, Action, Mecha, Adventure, Comedy

       Insights: Clear audience for futuristic, high-energy content, particularly featuring advanced technology and robotic themes.

     - Cluster 9:

       ![Cluster 9](https://github.com/DSM2499/Portfolio/blob/main/Photos/recommendation%20GI%209.png?raw=true)

       Primary Genres: Slice of Life, Comedy, School, Drama, Romance

       Insights: Strong preference for grounded, emotionally engaging stories focusing on everyday life and relationships.


  This cluster analysis provides a nuanced understanding of anime genre preferences, revealing distinct audience segments. These insights can      inform content creation strategies, marketing approaches, and programming decisions in the anime industry.

  - **Anime Duration**
 
    My analysis of anime episode durations reveals key trends in content structure and viewer preferences. These insights offer valuable 
    guidance for content creators, distributors, and streaming platforms in the anime industry.

    ![anime duration](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20duration.png?raw=true)

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

     ![user gender](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20user.png?raw=true)

    ![user age](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20age%20distribution.png?raw=true)

    ![user region](https://github.com/DSM2499/Portfolio/blob/main/Photos/anime%20location%20distribution.png?raw=true)

    <p>Our analysis of the anime community reveals a predominantly male audience with significant female representation and a small non-binary user base. The largest demographic consists of users in their early thirties, followed by young adults, with a global reach that includes notable concentrations in Poland, Germany, Brazil, Canada, and several European countries. This diverse audience composition provides valuable guidance for content creation, marketing, and platform development in the anime industry.</p>

    <p>To effectively engage this audience, content strategies should focus on developing gender-inclusive anime that appeals to both male and female viewers while also incorporating themes that resonate with non-binary individuals. Marketing campaigns can be localized to target countries with high user concentrations, with messaging tailored to the predominant age groups. Platform developers should prioritize age-appropriate content recommendations, offer customization options for different gender identities, and implement region-specific features. By leveraging these demographic insights, stakeholders in the anime industry can create more inclusive and engaging experiences, potentially expanding their user base and deepening audience engagement across various demographic segments.</p>

  - **User Engagement Analysis:**

     ![user engagement 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/user%20engagement%20gender.png?raw=true)

    ![user engagement 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/user%20engagement%20age.png?raw=true)

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

  ![Dataset Description 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/sentiment%20data.png?raw=true)
  
  ![Dataset Description 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/Sentiment%20data%20distribution.png?raw=true)

- **Code Repository:**
    [Sentiment Analysis](https://github.com/DSM2499/sentiment_analysis)

- **Results:**
    The model demonstrates robust performance on unseen clean data, achieving an accuracy of 74.15%. This result is promising, indicating the model's ability to generalize to new instances. However, the training accuracy plateauing at approximately 75% suggests potential overfitting, as the gap between training and test accuracy is relatively small.

  ![Model Results](https://github.com/DSM2499/Portfolio/blob/main/Photos/Seniment%20-%20accuracy%20over%20epochs.png?raw=true)


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

  ![Airfoil Sound Prediction 1](https://github.com/DSM2499/Portfolio/blob/main/Photos/airfoil%20images.png?raw=true)

  ![Airfoil Sound Prediction 2](https://github.com/DSM2499/Portfolio/blob/main/Photos/airofil%20images%202.jpeg?raw=true)

- **Approach:**
    In this project, I developed a robust predictive model for airfoil-generated sound levels utilizing Apache Spark and advanced machine learning techniques. The process began with the creation of a Spark session to efficiently manage data processing tasks. After acquiring the dataset, I loaded it into a Spark DataFrame and performed initial data cleaning, which included removing duplicate rows and addressing missing values.
    
    The data preprocessing phase involved renaming relevant columns for clarity and saving the cleaned data to a Parquet file, ensuring efficient storage and retrieval. Upon reloading the data, I designed a comprehensive machine learning pipeline incorporating feature vectorization, scaling, and linear regression.
    
    To prepare for modeling, I strategically split the dataset into training and testing sets. The pipeline model was then fitted to the training data and subsequently used to generate predictions on the test data. Model performance was rigorously evaluated using multiple regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2).
    
    Throughout the development process, I prioritized best practices in code formatting and documentation, ensuring clarity and maintainability of the codebase. The final step involved saving the trained pipeline model for future applications.
    
    This structured approach resulted in the creation of an efficient and scalable predictive model capable of providing valuable insights into airfoil noise levels. The model serves as a powerful tool for engineers and researchers, facilitating data-driven decision-making in airfoil design and noise reduction strategies.

- **Dataset Description:**

    Dataset: [NASA Airfoil Noise Raw](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/datasets/NASA_airfoil_noise_raw.csv)

  ![Dataset Description](https://github.com/DSM2499/Portfolio/blob/main/Photos/airfoil%20dataset.png?raw=true)
  
- **Code Repository:**
    [Airfoil Sound Prediction](https://github.com/DSM2499/Airfoil_sound_predictions)

- **Model Results:**

  ![Model Results](https://github.com/DSM2499/Portfolio/blob/main/Photos/Airfoil%20results.png?raw=true)

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
