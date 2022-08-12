# `Welcome to Dan's Portfolio!`
<br>

## `about me`
My name is Daniel Han and I was a forensic engineer until just a few months ago. With my structural engineering background, I investigated many buildings for insurance claims so that the adjustors can make informed decisions on the coverage amounts or whether a claim is fraudulent.

And then one day I met a Data Scientist whose job was similar to mine - to help his client make informed decisions - but was done in a completely different way. I was fascinated by the fact that many decisions in the business settings - perhaps even the ones I helped my client make - could be made based on `data`!  

Fast forward to today, I am now an aspiring Data Scientist enrolled in a Bootcamp at [BrainStation](https://brainstation.io/course/online/remote-data-science-bootcamp) to embark on a new journey in my career. Excited about all the things I can do with what I've learned, I have already started a few projects which I decided to showcase here.<br><br>    
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

### `data cleaning`

- The original data is provided in json format and requires conversion to a more workable format (i.e. csv).<br><br>
- Multiple schemas - business, user, review, check-ins - are cleaned, reformatted and combined into one.<br><br>
- Some critical information - namely the business hours, categories, and attributes - are input as texts in somewhat random manner and contained many typos and exceptions, which called for extensive cleaning and normalization. This done by using `regex` patterns and user-defined element-wise functions.<br><br>

**Uncleaned Columns of Business Table**<br>
<img src = "https://user-images.githubusercontent.com/53546728/184282670-4ff78618-fd7e-4d63-af87-79cf826f8061.jpg" width="300" height="300">
<br><br>

### `exploratory data analysis (eda)`

- The cleaned data are reviewed for its general distribution and correlations with the rating.<br><br>
- Datetime variables are decomposed to look for any trend and/or seasonality.<br><br>
- Geographical information is visualized on the map. <br><br> 

**Correlation Heatmap for categorical/numeric variables**<br>
<img src="https://user-images.githubusercontent.com/53546728/184282565-9c625491-2378-4bae-825c-008936ed2af4.png" width="400" height="400">

**Time-Series Decomposition**<br>
<img src="https://user-images.githubusercontent.com/53546728/184382731-6c6a4c33-bf46-4572-a6aa-ad7ed1c9d002.jpg" width="600" height="400">

**Geographic Information**<br>
<img src="https://user-images.githubusercontent.com/53546728/184385745-ffc06991-5a0e-43c5-9916-3b2f66e6245f.jpg" width="600" height="300">
<br><br>

## [Project 2 - Quora Classification: Sincere or Insincere Question?](https://github.com/daniel29han/portfolio/tree/main/Projects/Quora)
<sub>**NLP | Python | EDA | Sentiment Analysis | Machine Learning | Classification Model | Agile Methodology | Git**</sub>
