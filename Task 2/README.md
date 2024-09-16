<h1>Data science/Data Analytics Internship at Brainwave_Matrix_Solutions </h1>
<br>
<h2>Twitter Sentiments Analysis (NLP)</h2>

A brief description about this project : This is an entity-level sentiment analysis dataset of twitter. Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three tweets in this dataset: Positive,Negative and Neutral.

This dataset is the collection of 200 unique tweets collected with the help of a Chrome extension.
<h2>Dataset Information</h2>
    <ul>
        <li><strong>Tweet Text:</strong> Contains tweet</li>
        <li><strong>Reply Count:</strong>Count of replies</li>
        <li><strong>Retweet Count:</strong>Count of retweets</li>
        <li><strong>Like Count:</strong>Count of likes</li>
        <li><strong>View Count:	</strong>Count of views</li>
        <li><strong>Lemmatized Tweet Text:</strong> Tweet after lemmatization</li>
        <li><strong>Subjectivity:</strong> Subjectivity score of tweet</li>
        <li><strong>Polarity:</strong> Polarity score of the Tweet</li>
        <li><strong>Analysis Score:</strong>Indicate whether the tweet is positive,negative or neutral.</li>
    </ul>
<h2>Steps taken in this project</h2>
    <h3>Collect and Load Data</h3>
        <p>Collected data from an online platform and loaded the data into jupyter notebook (used Python language and its libraries that are needed for the analysis).</p>
    <h3>Text processing</h3>
        <h4>1. Text Cleaning</h4>
            <ul>
                <li><strong>Remove Unwanted columns:</strong> Remove columns that are not needed for analysis</li>
                <li><strong>Remove Punctuation:</strong> Strip out punctuation marks.</li>
                <li><strong>Remove URL:</strong> Eliminate links .</li>
                <li><strong>Remove stop words:</strong> Eliminate words like and ,as etc .</li>
                <li><strong>Remove emojis:</strong> Eliminate emojis.</li>
                <li><strong>Remove Special Characters:</strong> Get rid of special characters like #,",@ etc.</li>
                <li><strong>Remove Named Entities:</strong> Remove entities like name of a person, country etc.</li>
                <li><strong>Lowercasing:</strong> Convert all text to lowercase to ensure uniformity.</li>
            </ul>
         <h4>2. Lemmatization</h4>
            <ul>
                <li><strong>Lemmatization:</strong> Reduce words to their base form using vocabulary and morphological analysis(e.g., "better" to "good").Label each word with its corresponding part of speech using POS tags(e.g., noun, verb, adjective).</li>
            </ul>            
         <h4>3. Subjectivity and Polarity</h4>
            <ul>
                <li><strong>Subjectivity and Polarity:</strong> Sujectivity is a metric to decide the amount of personal opinion and factual information in a text, ranging from 0 to +1, where 0 is highly objective and +1 is highly subjective.Polarity is the level of positivity or negativity in a text, ranging from -1 to +1, where -1 is negative and +1 is positive</li>
            </ul>
             <h4>4. Building Word Cloud</h4>
            <p>Creating a word cloud is to visualize the content of a large collection of textual information and their subject domains within seconds, without reading all of them. Create word cloud separately for positive, neagtive and neutral polarity.Most frequent words will shown big in size and least will be shown small in size. </p>
                <h4>5. Visualisation</h4>
            <p>Plot barplot and scatter plot.Scatter plot shows the relationship between polarity and sujectivity of the data.Depicted sentiment distribution using bar plot with Analysis score in x-axis and the count of analysis score in y-axis.Bar plot has been created separately based on the sentiment distribution of Like count,Reply count,View count,Retweet count</p>
<h4>6. Predictive model building and saving model</h4>
            <p> Separate the Lemmatized tweet text and analysis score in to two variables. Splits this dataset in to two sets: a training set and a test set, which is use to evaluate the performance of the model. Training set used to train the model on part of data and test set used to evaluate the model's performance on the remaining data.
                Create a classification model using logistic regression algorithm and train this model using training data set. Accuracy, precision, recall, and F1-score are evaluation metrics  used for classification models. These metrics help to assess the performance of models that predict categorical outcomes.It is then saved for making the future analysis easy</p>
    <p>Through this project, I have successfully built and evaluated a predictive model for sentiment analysis of tweets. This project demonstrates the entire workflow, including data collection, preprocessing, exploratory data analysis, model training, evaluation. Key steps include text cleaning, tokenization, sentiment analysis using TextBlob, and visualization with word clouds and bar charts. The model's performance is assessed using accuracy, precision, recall, and F1-score.</p>
<h2>Contact Information</h2>
    <p>For feedback  and queries regarding this project, please contact.</p>
    <p>LinkedIn:</p><a href="https://www.linkedin.com/in/akash-p-nair-b63b46318?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"></a>https://www.linkedin.com/in/akash-p-nair-b63b46318?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app</p>
    <p>Email:akashpbsc.cs2021@gmail.com</p>

