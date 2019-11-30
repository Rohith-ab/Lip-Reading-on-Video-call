#AndroidDevChallenge

# Lip Reading on Video call

A lip reading app for Video calls which will help when there is background noise. The app will read your lips and translate it into text or voice to the person at the other end. 

Most people might have been in this situation: You have a conference call and you still haven't reached your home or office and in the middle of nowhere, in a train commuting, on the sidewalk, in a bar with friends...the list goes on. You still try to take the call and it's too noisy! you end up dropping the call. Not any more...the Lip Reading assistant will save your day. All you have to do is when you are on a video call, tap on the Lip read action button and sit back and just talk in a very low voice, the app will read your lips and convert it to your simulated voice to the audience at the other end, simultaneously you can view the text spoken by you. It sure sounds like magic!

## App Flow

***Step 1: Open the video call app and tap on Lip read***

<img src="Story1.jpg" width="90%">

***Step 2: The app will mute your background noise for the person at the other end.***

<img src="Story2.jpg" width="90%">

<img src="Story3.jpg" width="90%">

***Step 3: Will start lip reading and show the text in the bottom for you***

<img src="Story4.jpg" width="90%">

***Step 4: The person at the other end can hear your simulated voice with clarity***

<img src="Story5.jpg" width="90%">


# Tell us how you plan on bringing it to life.

The app is in a concept stage right now. 

### Our Approach : Contours of Face + Voice from mic + Smart Compose

1. #### Contours of Face 
    We will use this to get the movement of the lips to extract best matching word which is being spelt by the user.

2. #### Voice from mic
    We will use this to extract the best possible voice and words by also removing the background noise.

3. #### Smart Compose
    By using the words which he has previously spoken, will we use Smart Compose to get the best possible next word.
    
 By combining all the above 3 approaches we will predict what the user is speaking.
 
 ### How Google can help us:
 
 * By providing the dataset for extracting words from contours of face or the Lip Reading model itself if Google has one to save time.
 * Access to Smart Compose API.
 * Dataset for removing background noise from sound.
 * Natural Language Processing Expert as a mentor would be really helpful.
 * Resources like GPU, Cloud and Server for video calling.
 
 ### Timeline :

#### In December 2019:
* Studying and building the dataset.

#### In January 2020:
* Analyzing and Preparing the ML model.
* Developing and Testing the Android App.

#### In February & March 2020 :
* Training and Testing the model.

#### In April 2020:
* Testing the final output in real environment.


# Tell us about you

We are a software company called [Flashbox](http://flashbox.in/)  in Bengaluru, India helping large enterprises build products. We also are developing an app called [5Things](https://play.google.com/store/apps/details?id=com.flashbox.a5things) which shows you content (News, Restaurants, movies, weather, sports scores, stock market updates, trivia etc based on demography and location). At a time we show only 5Things. Right now we are in beta, we will be releasing the app within a couple months.
