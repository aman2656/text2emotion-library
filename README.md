# What is emotion?
Emotion is a biological state associated with the nervous system brought on by neurophysiological changes variously associated with thoughts, feelings, behavioural responses, and a degree of pleasure or displeasure.
(Source: Wikipedia)

Human being can easily identify the emotions from text and experience it. But what about the machines, are they able to identify the emotions from text?

#### Text2Emotion is the python package which will help you to extract the emotions from the content.

- Processes any textual message and recognize the emotions embedded in it.
- Compatible with 5 different emotion categories as Happy, Angry, Sad, Surprise and Fear.

## Features
> ##### 1. Text Pre-processing
> At first we have the major goal to perform data cleaning and make the content suitable for emotion analysis.
> - Remove the unwanted textual part from the message.
> - Perform the natural language processing techniques.
> - Bring out the well pre-processed text from the text pre-processing.
> ##### 2. Emotion Investigation
> Detect emotion from every word that we got from pre-processed text and take a count of it for further analytical process.
> - Find the appropriate words that express emotions or feelings.
> - Check the emotion category of each word.
> - Store the count of emotions relevant to the words found.
> ##### 3. Emotion Analysis
> After emotion investigation, there is the time of getting the significant output for the textual message we input earlier.
> - The output will be in the form of dictionary.
> - There will be keys as emotion categories and values as emotion score.
> - Higher the score of a particular emotion category, we can conclude that the message belongs to that category.

## How to use?
#### [Check Demo on Colab]()

## App Deployment
Here's the code implementation with **Streamlit App** for the users.
1. Enter the text.
2. Hit the submit button.
3. Tada!! Get the output in visualization form
#### [Check Demo of App](https://pyemotion.herokuapp.com/)

Let's experience the library, test your multiple use cases on web app and check whether the library performs as per your expectations.
