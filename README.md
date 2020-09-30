# Audio-Sentiment-Analysis-using-Librosa

# Introduction 
We are going to build an audio emotion classifier. But why you ask, are we doing this? Well, for a few reasons: 

- **Its becoming fairly important**<br/>
At least, here in Australia, due to the recent fallout of the Royal Commision, there's more scrutiny than ever into the financial sector. One of the areas that traditionaly have been ingored by the government is contact centres, many of these generate contracts through telephone conversations. So compliance is a hot topic right now 

- **Because we can**<br/>
With recent advancements of Deep Learning, better hardware and more open sourcing of data, this enables us to build the capability that we couldn't before. So, why not.  

- **Accessibility**<br/>
I've specifically chosen emotion as our target because its one of the more accesible **labeled** dataset. Don't misunderstand, there are many good quality audio datasets out there, but many are either not relevant (eg. background noises), or locked behind paid wall. Emotions are probably relevant enough since we are dealing with conversations between agent and customer, and there's variety of sources. Also, emotions are general enough (not context dependent), so we can apply to a vast number of different projects

This is going to be a 4 part series . Could be more, but not less. Part 2 covers feature extraction whilst Part 3 and 4 we will dive into the modelling. But to train a model, we need data. So Part 1 here, we are going to check out a few data sources which are all open sourced:

- Surrey Audio-Visual Expressed Emotion [(SAVEE)](https://www.kaggle.com/ejlok1/surrey-audiovisual-expressed-emotion-savee)
- Ryerson Audio-Visual Database of Emotional Speech and Song [(RAVDESS)](https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio)
- Toronto emotional speech set [(TESS)](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess)
- Crowd-sourced Emotional Mutimodal Actors Dataset [(CREMA-D)](https://www.kaggle.com/ejlok1/cremad)
