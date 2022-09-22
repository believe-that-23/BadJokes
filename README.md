# BadJokes
This project was bootstrapped with [Create React App]

About this project
Basically it is a joke app it bring jokes from ("https://icanhazdadjoke.com/") using API.
Library used for fetch API is axios.
It store the intial joke in local storage and fetch extra joke when I request to API and again store in local storage.
It has joke UPVOTE and DOWNVOTE system and show Jokes in a sorted order non increasing order of their upvote .


# npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

![bn](https://user-images.githubusercontent.com/84314022/191697972-c507d008-9460-49de-be30-2a872f44f215.png)

Displays new jokes after fetching the data from the API and storing it in the local storage.<br>
After Upvoting a joke it sorts the jokes in decreasing order of upvotes.


![bn2](https://user-images.githubusercontent.com/84314022/191698021-3e4d4147-4b89-46ff-b6b2-48e1d2255da3.png)

The emoticons also change according to the upvotes and downvotes of a joke.
