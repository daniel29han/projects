# `Welcome to Dan's Portfolio!`
<br>

## `about me`
My name is Daniel Han and I was a forensic engineer until just a few months ago. With my structural engineering background, I investigated many buildings for insurance claims so that the adjustors can make informed decisions on the coverage amounts or whether a claim is fraudulent.

One day I had a chance to speak to a Data Scientist whose job was similar to mine - to help his client make informed decisions - but I learned that his job was done in a completely different way. I was fascinated by the fact that many decisions in the business settings - perhaps even the ones I helped my client make - could be made with `data`, instead of investigating everytime!  

Today, I am an aspiring Data Scientist enrolled in a Bootcamp at [BrainStation](https://brainstation.io/course/online/remote-data-science-bootcamp) to embark on a new journey in my career. Excited about all the things I can do with what I've learned, I have already started a few projects which I decided to showcase here.<br><br>    
## `about this portfolio`
This portfolio highlights the projects I am working on and will  for the next few months. As I am yet halfway through my program, these projects do not yet encompass the entire aspects of a Data Science/Analysis project.

As the course progresses, I will be actively adding to and modifying these projects. That means, everytime you visit here, you will find a newer, better version of my projects!

My program ends this December and by then I will be equipped with all the necessary knowledge, skills and techniques that a great Data Scientist must have. In the meantime, please check out my projects and feel free to connect with me on Linkedin or via email!

`email`: daniel29han@gmail.com <br>
`LinkedIn`: [https://www.linkedin.com/in/daniel-han-337706b3/](https://www.linkedin.com/in/daniel-han-337706b3/)
<br><br>
## [Project 1 - Yelp Rating Prediction and Recommender System](https://github.com/daniel29han/portfolio/tree/main/Projects/Yelp) 
<sub>**Data Acquisition | Data Cleaning | Regular Expressions | Visualizations | Python | EDA | Time Series | Machine Learning | Regression | Git**</sub>
<br>
### `overview`
- Yelp is an online platform where users can rate and write reviews on local businesses. Users can also browse the website and/or search local businesses of their interest.<br><br>
- To facilitate the user's browsing on Yelp's website, this project aims to recommend businesses to every user that they might enjoy.<br><br>
- In this hypothetical project, more than 6 million consumer reviews on Yelp are analyzed to study what kinds of businesses succeed and what the users like.<br><br>
- Also, given a set of information about a user and local business, the user's likely rating on the business is predicted on a continuous scale between 0 and 5.<br><br>
- Finally, a recommender system will be created based on collaborative filtering algorithm. (This is what I am studying and will update soon!)
<br><br>
### `why this project?`
- To improve user experience with the service by reducing browing time and effort and leave the impression that the service provider (Yelp) knows exactly what the users want - even when the users don't know themselves!<br><br>
- To better understand how Data Science can be utilized to improve customer satisfaction in the commercial setting.
<br><br>
### `data cleaning`

- The original data is provided in json format and requires conversion to a more workable format (i.e. csv).<br><br>
- Multiple schemas - business, user, review, check-ins - are cleaned, reformatted and combined into one.<br><br>
- Some critical information - namely the business hours, categories, and attributes - are input as texts in somewhat random manner and contained many typos and exceptions, which called for extensive cleaning and normalization. This done by using `regex` patterns and user-defined element-wise functions.<br><br>

*Uncleaned Columns of Business Table*<br>
<img src = "https://user-images.githubusercontent.com/53546728/184282670-4ff78618-fd7e-4d63-af87-79cf826f8061.jpg" width="300" height="300">
<br><br>

### `exploratory data analysis (eda)`

- The cleaned data are reviewed for its general distribution and correlations with the rating.<br><br>
- Datetime variables are decomposed to look for any trend and/or seasonality.<br><br>
- Geographical information is visualized on the map. <br><br> 

*Time-Series Decomposition*<br>
<img src="https://user-images.githubusercontent.com/53546728/184382731-6c6a4c33-bf46-4572-a6aa-ad7ed1c9d002.jpg" width="600" height="400">

*Geographical Analysis*<br>
<img src="https://user-images.githubusercontent.com/53546728/184385745-ffc06991-5a0e-43c5-9916-3b2f66e6245f.jpg" width="600" height="250">
<br><br>

## [Project 2 - Quora Classification: Sincere or Insincere Question?](https://github.com/daniel29han/portfolio/tree/main/Projects/Quora)
<sub>**NLP | Python | EDA | Sentiment Analysis | Machine Learning | Classification Model | Agile Methodology | Git**</sub>
<br>
### `overview`
- Quora is a social question-and-answer website based in Mountain View, California, where users can collaborate by editing questions and commenting on answers that have been submitted by other users.<br><br>
- While the convenience that anyone can post and edit questions on the forum allows users to dynamically engage in the service, the downside is that some users may post insincere questions which would compromise the reliability of the website and/or degrade other groups of individuals.<br><br>
- In this hypothetical project, the characteristics of insincere questions on Quora are studied using machine learning techniques, and a classification model predicting whether or not a question in sincere is created based on the underlying logic.
<br><br>
### `why do this project?`
- To study what characteristics of language imply the insincerity of a question.<br><br>
- To automate the process of classifiction such that, given a question, my project outputs the result instantly.<br><br>
- To use Data Science to promote healthy web environment and protect vulnerable groups from toxic contents.
<br><br>
### `text processing`
- Cleaned the questions of punctuations, contractions, stopwords (i.e. words that do not contribute to the sentiment of a document such as 'a(n)', 'is'), etc.
- Through further processing techniques, converted each question in the dataset into 'tokens' of words (i.e., Tokenization), which is a more ideal form for exploratory data analysis and modelling.<br><br>
*Questions before Processing*<br>
![Screenshot 2022-08-14 093106](https://user-images.githubusercontent.com/53546728/184539462-7063abab-2328-4973-964b-ef2d2891f99e.jpg) <br><br>
*Questions after Processing*<br>
![Screenshot 2022-08-14 102424](https://user-images.githubusercontent.com/53546728/184541472-4457de8a-df17-4b5b-95f6-2309dbc91622.jpg)
<br><br>
### `exploratory data analysis`
- Reviewed the words frequently appearing and/or relevant to the context using the bag-of-word and Tf-Idf mechanism.<br><br>
- Displayed frequent & relevant words using WordCloud.<br><br>
- It was found that the words associated with insincere questions were largely related to race, religions, politics, sex, and violence.<br><br>

*Words Frequently Appearing in and Relavant to Insincere Questions*<br>
<img src="https://user-images.githubusercontent.com/53546728/184539721-d7a77304-5794-4219-b4e3-ea6697e15a32.jpg" width="500" height="250">
<br><br>
### `modelling`
- Two different algorithms, Tf-Idf and Word2Vec, were considered for converting words to digital inputs.<br><br>
- Several  classification algorithims, namely Multinomial Naive Bayes, Random Forest, and Logistic Regression, were considered.<br><br>
- Performances of the different models are compared with confusion matrix and the best performing model is selected.<br><br>

![Screenshot 2022-08-14 100102](https://user-images.githubusercontent.com/53546728/184540547-2f927be3-34b5-4a81-87bc-c55b766c2f14.jpg)<br><br>

### `testing`
- Using the classification model, the test set of questions are classified as either sincere or insincere.<br><br>

*Questions Classified as Insincere based on Classification Model*<br>
<img src="https://user-images.githubusercontent.com/53546728/184540767-5825024b-deba-47cc-a8e4-18e3134911ea.jpg" width="1000" height="600">

