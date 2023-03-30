<div>
<h1 align = 'center'><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUIwD84MUO1g9n6U0VWNJKRK0pPFVGTXsBeQ3KTeeGTpxX7VKB3-rMoW1J2bvU2blIFiM&usqp=CAU"  width="40" height="40"/><b> SENTIMENT ANALYSIS IN SOCIAL MEDIA: A STUDY ON CHATGPT IN MALAYSIA</b> </h1>
</div>



## Table of content
- [Table of content](#table-of-content)
- [📒 Executive Summary](#-executive-summary)
- [🧱 Background](#-background)
- [🔬 Goals and Objectives](#-goals-and-objectives)
- [🧿 Scope](#-scope)
- [🔖 Methodology](#-methodology)
- [🖥️ System Architecture](#️-system-architecture)
- [💣 Risks and Limitations](#-risks-and-limitations)
  - [💰 Financial Risk](#-financial-risk)
  - [⚙️ Technical Risk](#️-technical-risk)
  - [📑 Legal Risk](#-legal-risk)
- [🗿 Deliverables and Milestones](#-deliverables-and-milestones)
- [🗂️ Resources](#️-resources)
- [🛠️ Technical Specifications](#️-technical-specifications)
- [⏲️ Timeline and Deliverables](#️-timeline-and-deliverables)
- [🔍 Conclusion](#-conclusion)

## 📒 Executive Summary
This proposal outlines a social media monitoring tool to understand public opinion and sentiment on ChatGPT in Malaysia. The main goal of the project is to develop a web application that can identify areas for improvement and potential new features for ChatGPT. The project's scope includes collecting and processing social media data from social medias using APIs, performing sentiment analysis and topic modeling, and developing machine learning algorithms to classify social media data based on sentiment.

## 🧱 Background
<p align="center">
<img src="https://user-images.githubusercontent.com/97009588/228268824-9dc3aa13-493f-4002-b3d4-a82322902244.png" alt="Paris" height="250"></img>
</p>
ChatGPT is an artificial intelligence language model developed by OpenAI that is designed to generate human-like text in response to natural language inputs. As ChatGPT hits the market, it becomes crucial for us to understand public opinion and sentiment towards the platform. However, analyzing this data manually is time-consuming and often impractical. Therefore, there is a need for a platform that can monitor and analyze social media data in real-time to understand public opinion and sentiment on ChatGPT in Malaysia.
<br><br>
<b>Current Situation and Problems Faced:</b><br>
Currently, there is no platform dedicated to monitoring and analyzing social media data on ChatGPT in Malaysia. This makes it challenging to understand user behavior, preferences, and sentiment towards the platform. Manual analysis of social media data is time-consuming and often subject to biases and errors.
<br><br>
<b>Potential Benefits of the Proposed Solution:</b><br>
By developing a web application that can collect, process, and analyze social media data in real-time, the project will provide areas for improvement and potential new features for ChatGPT. This project will help to automate the process of analyzing social media data, saving time and reducing the risk of biases and errors associated with manual analysis. Overall, the proposed solution has the potential to provide valuable insights that can help improve ChatGPT's popularity and usage in Malaysia.

## 🔬 Goals and Objectives
The primary goal of this project is to develop a web application that can monitor and analyze social media data in real-time to understand public opinion and sentiment on ChatGPT in Malaysia.

We have established these objectives in order to achieve this goal:


- Develop a web application that can collect from social media using APIs and process those data.
- Perform sentiment analysis and topic modeling to understand public opinion and sentiment towards ChatGPT in Malaysia. 
- Develop visualizations and dashboards to present the results of the analysis.
- Provide recommendations for further development of ChatGPT based on the insights gained from the analysis.

## 🧿 Scope
The project will focus specifically on Twitter data, as Twitter is a popular social media platform for discussing technology and current events. By analyzing Twitter data in real-time, the project aims to provide valuable insights into the public's perception of ChatGPT

<b>Data Sources:</b>

The primary data source for this project will be Twitter's API, which will provide us with real-time access to tweets related to "ChatGpt." We will use Twitter's streaming API to collect tweets in real-time, using specific keywords and hashtags related to ChatGpt.

<b>Tools and Technologies:</b>

We will use Python as the main programming language for this project, along with several open-source libraries such as Tweepy, Pandas, and MongoDB:

I.	Tweepy: Use to connect to Twitter's API.

II.	Pandas: Use for data manipulation and preprocessing. 

III.	MongoDB:  To store the collected data which allow us to store and query the data efficiently.

IV.	NLTK (Natural Language Toolkit): Use for sentiment analysis

V.	PowerBI: To visualize and explore the data.

<b>Other Relevant Information:</b>

To ensure data privacy and security, we will comply with Twitter's API Terms of Service and any applicable laws and regulations related to data privacy and security. We will also use appropriate measures to secure the data, such as encrypting the database and using secure protocols for data transfer.


## 🔖 Methodology
The project will follow the Agile methodology, with sprints of 10-12 weeks, and regular demos and retrospectives to review progress and plan the next steps.

1. Data Collection: The project will collect Twitter data using the Twitter API, which provides access to a sample of the real-time Twitter stream. The collected data will include tweets that mention "ChatGpt" and related hashtags, keywords, and phrases.

2. Data Pre-processing: The collected data will be pre-processed to remove noise, such as irrelevant tweets and spam, and to extract relevant information, such as the user's sentiment towards ChatGpt. The pre-processing steps will include:
  •	Removing duplicate tweets
  •	Removing retweets
  •	Removing tweets that are not in English
  •	Tokenizing the text and removing stop words
  •	Applying stemming or lemmatization to reduce the text to its base form
  •	Applying part-of-speech tagging to identify noun phrases and named entities
  •	Filtering the text to remove mentions, URLs, and other irrelevant information
  •	Applying sentiment analysis to determine the polarity of the tweets

3. Sentiment Analysis: The project will perform sentiment analysis on the pre-processed data to determine the polarity of the tweets, i.e., positive, negative, or neutral sentiment. The sentiment analysis will be performed using a machine learning model, such as a Naive Bayes or Support Vector Machine (SVM) classifier, trained on a labelled dataset of tweets.

4. Data Visualization: The project will use data visualization techniques to display the sentiment analysis results in a meaningful and informative way, such as bar charts, pie charts, and word clouds. The visualization will provide an easy-to-understand summary of the sentiment distribution and the most common topics and phrases associated with ChatGpt.

5. Real-time Analysis: The project will perform real-time analysis of Twitter data to provide up-to-date insights into public opinion and sentiment about ChatGpt. The real-time analysis will involve continuously collecting and pre-processing Twitter data, performing sentiment analysis, and updating the visualization.

All in all, the methodology of the project is to collect and pre-process Twitter data, perform sentiment analysis, and visualize the results in real-time, using natural language processing and machine learning techniques. The methodology will provide valuable insights into public opinion and sentiment about ChatGpt, and help OpenAI to make data-driven decisions and improve its products and services.



## 🖥️ System Architecture

&ensp;Our proposed system architecture will be a web application that can monitor and analyze social media data in real-time to understand public opinion and sentiment on ChatGPT in Malaysia. The application will collect data from social media using APIs, perform sentiment analysis and topic modeling, and present the results through visualizations and dashboards.

**Tools and Technologies:**
Python: As the main programming language.
Tweepy: To connect to Twitter's API.
Pandas: For data manipulation and preprocessing.
MongoDB: To store the collected data.
NLTK: For sentiment analysis.
Power BI: For data visualization and analysis.

**Data Storage and Management:**
We will use MongoDB as our database management system. MongoDB is a document-oriented NoSQL database that can handle large volumes of unstructured data. We will store the collected data in MongoDB in a format that is suitable for further analysis. We will use PyMongo, a Python library for MongoDB, to interact with the database. The data will be organized in a collection called "tweets" with the following fields: tweet_id, created_at, text, username, user_id, location, sentiment, and topic.

**Hardware and Software Requirements:**
The proposed system architecture requires a server with the following hardware specifications:

Processor: Intel Core i7 or equivalent
RAM: 8 GB or more
Storage: 500 GB or more
The software requirements for the server are:

Operating System: Ubuntu Server 20.04 LTS
Python 3.8 or higher
MongoDB 4.4 or higher

**Data Visualization and Analysis:**
We will use Power BI, a business intelligence tool, for data visualization and analysis. Power BI allows us to create interactive dashboards and reports based on the data stored in MongoDB. We will use the Power BI Desktop app to connect to the MongoDB database and import the data. We will then create visualizations such as charts, graphs, and tables to display the sentiment and topics related to ChatGPT. We can also use filters and slicers to explore the data further.

**Flowchart of System Architecture:**
flowchart


## 💣 Risks and Limitations


### 💰 Financial Risk
a) The cost of cloud computing services, such as MongoDB Atlas and Power BI, may exceed the project budget.

**Mitigation Plan:**

a) Conduct a thorough cost analysis before the project begins to ensure that the project remains within budget.

b) Consider using open-source or low-cost alternatives to expensive software tools.

### ⚙️ Technical Risk
a) Social media data collection may not be reliable or consistent due to changes in social media API or policies.

b) Sentiment analysis accuracy may be affected by the use of slang or contextual references.

c) Topic modeling may not accurately reflect the key themes of the social media data.

**Mitigation Plan:**

a) Monitor the social media API and policies and make necessary adjustments to data collection methods.

b) Use Natural Language Processing techniques to preprocess the data and filter out irrelevant or confusing terms.

c) Use additional analytical methods to validate the results of the topic modeling and ensure accuracy.

### 📑 Legal Risk
a) Legal and ethical concerns may arise due to the collection and use of user-generated social media data.

b) Privacy concerns may arise if the social media data includes personal information.

**Mitigation Plan:**

a) Ensure that the collection and use of social media data comply with relevant laws and regulations, such as GDPR and CCPA.

b) Anonymize the data by removing personal information, and ensure that all data is stored and analyzed in a secure environment.

&ensp;Overall, a comprehensive risk management plan will be put in place to minimize the impact of any risks and limitations that may arise during the course of the project. This plan will include regular monitoring of project progress, identification of potential risks, and contingency strategies for addressing any issues that arise. In addition, the project team will maintain open communication with stakeholders to ensure that any concerns or issues are addressed in a timely and effective manner.

## 🗿 Deliverables and Milestones
<table border="1" align="center">
  <tr>
    <th>Deliverables and Milestones</th>
    <th>Timeframe</th>
  </tr>
  <tr>
    <td>Data Collection</td>
    <td>Week 1-2</td>
  </tr>
  <tr>
    <td>Data Cleaning and Preprocessing</td>
    <td>Week 3-4</td>
  </tr>
  <tr>
    <td>Sentiment Analysis</td>
    <td>Week 5-7</td>
  </tr>
  <tr>
    <td>Build Model & User Interface</td>
    <td>Week 8-11</td>
  </tr>
  <tr>
    <td>Deployment and Testing</td>
    <td>Week 12</td>
  </tr>
  <tr>
    <td>Maintenance</td>
    <td>Week 13-14</td>
  </tr>
</table>


## 🗂️ Resources

- **Staff**
   - Data Scientist
   - Data Engineer
   - Database administrator
   - Project Manager

- **Equipment**
   - Computer/Laptop
   
- **Software**
   - Python and libraries like Tweepy, Pandas, NLTK, Matplotlib
   - MongoDB
   - Visual Studio Code
   - Tableau / Power BI
   - Git and Github
   
- **Other expenses**
   - Twitter API
   - Cloud services

## 🛠️ Technical Specifications

<table>
  <tr>
    <th align= "left">Data sources</th>
    <td>Twitter data collected by using Twitter API</td>
  </tr>
  <tr>
    <th align= "left">Data schema</th>
    <td>JSON like data including fields such as the tweet ID, tweet text, user ID, time and other relevant metadata</td>
  </tr>
  <tr>
    <th align= "left">Data transformations</th>
    <td>Data preprocessing techniques such as converting all text to lowercase, tokenization, removing stop words, stemming, and lemmatization will be used on the collected tweets text.</td>
  </tr>
  <tr>
    <th align= "left">Machine learning algorithms</th>
    <td>
      <ul>
	<li>Naive Bayes, Support Vector Machines (SVM), Neural Network</li>
	<li>VADER</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th align= "left">Data visualization tools</th>
    <td>Tableau, Power BI, Matplotlib</td>
  </tr>
  <tr>
    <th align= "left">Programming language</th>
    <td>Python, HTML, CSS, Javascript, MongoDB Query Language (MQL)</td>
  </tr>
  <tr>
    <th align= "left">Frameworks</th>
    <td>Django, Pyscript</td>
  </tr>
  <tr>
    <th align= "left">Libraries</th>
    <td>Tweepy, Numpy, Pandas, NLTK, Matplotlib, Seaborn, WordCloud</td>
  </tr>
  <tr>
    <th align= "left">Hardware & software requirements</th>
    <td></td>
  </tr>
  <tr>
    <th align= "left">Data security measures</th>
    <td>
	  <ul>
	    <li>Use HTTPS to communicate with the Twitter API</li>
	    <li>Implement data encryption to ensure data privacy and security</li>
	    <li>Implement access control to ensure the access to database and the data is limited to authorized personnel only</li>
	  </ul>
	</td>
  </tr>
</table>


## ⏲️ Timeline and Deliverables
<div class="mermaid">
  
  ```mermaid
gantt
    title SENTIMENT ANALYSIS IN SOCIAL MEDIA: A STUDY ON CHATGPT IN MALAYSIA
    dateFormat  YYYY-MM-DD
  
    section Data Collections
    Data Collection  :2023-04-01 , 5d
  
    section Data Cleaning and Preprocessing
    Data Cleaning            :2023-04-6  , 7d
    Data Preprocessing                    :2023-04-10 , 10d
   
  
    section Sentiment Analysis
    Finalizing               :2023-04-20 , 7d
    Preparing Model       :2023-04-27 , 7d
    Model Testing         :2023-05-04 , 7d
  
    section Build Model & User Interface
    Simple data chart            :2023-05-11 , 8d
    ML visualization             :2023-05-16 , 9d
    Designing User interface  :2023-05-25 , 11d
    Features add-ons          :2023-06-04 , 8d
    Modul insert              :2023-06-11 , 6d
  
    section Deployment and Testing
    Finalizing                :2023-06-17 , 5d
  
    section Testing & project launch
    Live Testing      :2023-06-23 , 7d
    Fixing flaws      :2023-06-30 , 7d
  
  ```
  </div>
  
- Data Collection (`Week 1 - Week 2`)

  > Discussing which data source that suit the best for our project objectives and scope. 
  
- Data Cleaning and Preprocessing (`Week 3 - Week 4`)

  > Data Cleaning and preporcessing the data to be used for more advance processing such as EDA, Data Integration, Aggregation and Visualization. This phase is given 3 weeks to complete since we need to remove noisy data and duplications in order to have a completly clean data. 

- Sentiment Analysis (`Week 5 - Week 7`)

  > phase where we will be training the data and allow machine learning to use the data to create prediction, classification and clustering. 

- Build Model & User Interface (`Week 8 - Week 11`)

  > A crucial phase as overall project to create a stable and reliable system. Understanding the target audience, developing the interface with their wants and preferences in mind, and taking interactive elements, colour schemes, and typefaces into consideration are just a few of the tasks involved in UI design. For enterprises and organisations, a well-designed user interface may improve the user experience, allow for more effective decision-making, and increase energy efficiency.
  
- Deployment and Testing (`Week 12`)

  > Before we launch our website, it is important that we thoroughly test the system to ensure that everything is working properly and that the functions are ready to be used. This step also involves identifying and fixing any issues that could cause a system failure.

- Maintenance (`Week 13 - Week 14`)

  >  Performance monitoring and user feedback analysis

## 🔍 Conclusion
In conclusion, the proposed social media monitoring tool for ChatGPT in Malaysia has the potential to provide valuable insights into public opinion and sentiment towards the platform. By automating the process of analyzing social media data, the tool can save time and reduce the risk of biases and errors associated with manual analysis. The project's scope includes collecting and processing social media data, performing sentiment analysis and topic modeling, and developing machine learning algorithms to classify social media data based on sentiment. The project can ultimately benefit ChatGPT by providing areas for improvement and potential new features, thus improving its popularity and usage in Malaysia.
