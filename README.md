# WasteLess

## Inspiration
Waste can be harmful to the environment and all of us living in it, especially if not disposed of correctly. We found that knowing how to dispose of different types of waste and correctly identifying waste is not common knowledge. According to the New York Post, “a new survey of 2,000 Americans revealed that 62 percent worry that a lack of knowledge is causing them to recycle incorrectly. Over half of respondents (53 percent) erroneously believe greasy pizza boxes can be recycled, while 68 percent incorrectly think the same for used plastic utensils.”

Many people struggle with identifying the correct method of disposing of waste. It would be helpful if there was a way for people to quickly and easily get the answers they need and learn the proper way of recycling and throwing away waste. Let’s do better for ourselves and the planet we live on!
 
 
## What it does
WasteLess was created to solve the problem of incorrectly identifying and disposing of waste. This app was created to be an easy and quick way to find out how to dispose of the waste around you. It’s easy to just throw everything away in the same trash can especially when you don’t know otherwise or have the time to look into it. 

Instead of guessing if you are disposing of items correctly, you can open WasteLess and find out in seconds. Once you open the app a camera will open up and allow object detection to begin. It will label the items and when you click on it, the information will popup regarding the correct action you need to take. 

WasteLess also includes a recent search/history feature where you can look at previous items you detected. Users can also search for other items by typing in the product’s name. This can be convenient for users who do not want to use their camera or do not have the product close to them.

In order to make this app successful, we needed to research different categories of waste that are commonly encountered. Our categories include biodegradable, compostable, recyclable, hazardous, electronic, biomedical, and household waste. We have included information on each of these in the prototype with the information overview feature, a navigation bar feature on the main menu screen.


## How we built it
Using Figma we created a high fidelity prototype for our app. In the app, the camera opens and allows the user to capture the object they want to find out about. Using object detection, the product is detected and the user is told what it is and how to dispose of it. In addition, the user has the option of clicking the popup for more information on how or where to dispose of the product.

In the creation of WasteLess, we also made an app using Android Studio so that we could use TensorFlow Lite for object detection. The app works in the same way as our prototype. Using object detection the type of waste appearing in the user’s camera is identified and the information required for the user to dispose of the waste correctly is shown.


## Challenges we ran into
We ran with quite a few challenges while coming up with WasteLess and implementing it. At first, we all had different ideas coming into this hackathon. We started by bouncing off ideas and talking them out to see which one would allow us all to learn something new while also creating an impactful change. Once we discussed the idea behind WasteLess and the environmental change it would have, we all were on board to start working on it. The idea of helping our environment in a creative and easy way inspired us to choose this app.
While we were all intrigued with this app idea, we found that machine learning was new to most of us. We started by learning the basics and how machine learning works. We also looked for a platform we could use it on. We found that there were already pre-trained object detection models, we just had to find the one that worked the best for our app.

Using Figma was also something new for some of us. One challenge that was faced was how to incorporate a camera feature to portray what our app would do using TensorFlow.

The last challenge we faced was the time difference. We have been navigating between Eastern Standard Time (EST) and Indian Standard Time (IST). We had to figure out a schedule that would work for all of us to be able to meet up together.


## Accomplishments that we're proud of 
A lot of us had no experience with Machine Learning and Figma. It gave us the opportunity to explore something new. All of us gained experience with Google Colab and TensorFlow and learned more about the models that were offered for object detection.

Figma was another interface most of us had no prior experience with. We learned how to navigate Figma and what it has the power to create. Each of us came with our own strengths and we had the opportunity to learn something new from one another.

We were also able to navigate working in different time zones. It was interesting having some of us work in the morning while some of us were working at night. We also had to factor in eating and sleeping schedules which made for an interesting virtual teamwork experience. 
 
 
## What we learned
It can be daunting learning something new, especially with a short time frame however, we all came to this hackathon hoping to learn something new and to be challenged. We decided one of the challenges we were going to face was Machine Learning.  As a team, we were able to explore Google Colab and TensorFlow and learn how to use their object detection models.

Another interface that was new to most of us was Figma. We had the opportunity to explore the interface and see how prototyping worked. We learned the importance of design and how powerful it can be towards showing an idea. It also set the foundation for how we wanted to implement WasteLess.


## What's next for WasteLess?
Moving forward we are hoping to fully implement WasteLess. We also want to improve our object detection model on the WasteLess mobile app. Currently, most of the objects detected have received an accuracy score within 50-60%. Our goal is to reach an 80-90% accuracy score. 

We also want to localize content and provide information regarding each state. After researching we noticed that some states have different procedures to dispose of waste and it would be helpful if you received the information corresponding to where you live.

One feature we also started adding but want to elaborate on is our fun fact/tip popup. We currently have a place for tips on our learn more page. However, we want to add a place for fun facts that circulate on our start-up page while the app is loading.

#### Code based on TensorFlow Lite [examples](https://github.com/tensorflow/examples).

