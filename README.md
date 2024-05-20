# medical-QnA-system

This project is developed to answer user queries specific to medical field. <br>
**1.** Loaded the dataset in pandas dataframe and perfomed text cleaning and preprocessing using scaCy and re python library. <br>
**2.** Performed unsupervised training using preprocessed text on fastText for domain specific vector representation. <br>
**3.** Generated vector representation for preprocessed_question column. <br>
**4.** Recieved input from user and performed step 1 on it and then generated its vector representation. <br>
**5.** Finally calculated the maximum cosine similarity between user vector and step 3 vectors to answer the user query.

## Tech & Library

<div >
	<code><img width="40" src="https://github.com/DivingDev/medical-QnA-system/blob/main/resources/google-colab-logo-tech-companies.png" alt="Google Colab" title="Google Colab"/></code>
	<code><img width="25" src="https://user-images.githubusercontent.com/25181517/183423507-c056a6f9-1ba8-4312-a350-19bcbc5a8697.png" alt="Python" title="Python"/></code>
	<code><img width="40" src="https://github.com/DivingDev/medical-QnA-system/blob/main/resources/spaCy.png" alt="spaCy" title="spaCy"/></code>
	<code><img width="40" src="https://github.com/DivingDev/medical-QnA-system/blob/main/resources/fasttext-icon-white-web.png" alt="fastText" title="fastText"/></code>
</div>

## Project Development Flow

![](https://github.com/DivingDev/medical-QnA-system/blob/main/resources/project-flow.gif)

## Screenshots

![App Screenshot](https://github.com/DivingDev/medical-QnA-system/blob/main/resources/Example-output.png)
