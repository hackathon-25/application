![Logo](https://user-images.githubusercontent.com/41522248/57200843-8bc6d100-6f45-11e9-8c33-26a4638cea35.png)

http://unbouncepages.com/wastefun/


## Description
Today, one of the largest concern is climate changing resulted by global warming which landfill play a significant role in it. As environmental responsibility is not a duty of only a group of people anymore, We believe that by guiding people how to dispose of waste properly, we could reduce the amount of undiverted waste remarkably.
Our solution which is inspired by an AI research at SFU is encouraging people to waste properly.As we believe that people will be more motivated by presence of rewards,  we have a concept of giving points to the user and also the option of redemption to them.
In the concept, there is a device consists of several bins with a scale under and a sensor at top of each of them. There is also a camera for recognition of an object. Moreover, our device ( set of bins and camera and sensors ) has a monitor that allows users to log in to their account and to earn points based on their performance. The device not only shows where the recognized object has to go but also print out informative messages.

## Algorithm of earning points and redemption

Users are rewarded :
- For putting items into correct bins.
  - If users put an item into a right bin, they are rewarded with relevant points.
    - Green 5 points
    - Papers 4 points
    - Recycles 3 points
    - Glasses 2 points
    - Garbage 1 point
  - If users put an item into a wrong bin, they will be penalized by losing 10 points
- Based on the personalized goals
  - If users exceeded the limit (calculated based on the number of people leave together), they lose half of the points earned last month
  - If users did better than their history, depends on how well they did they will earn more points.
  - If users performance was worse than themselves and better than the limit, they are not rewarded more points.
- For the successful challenges, they have participated in
For example, if they do not make a mistake for a week they will be given more points 

Redemption system:

Users are motivated to use the device by the presence of rewards. For this reason, every 100 points are considered as a dollar and users can use them in different ways like Gift cards.


## What is your stack? What language did you program it in? What API’s did you use?
We have an API written in Ruby. We hosted the web app on Heroku.
Besides that, we've built an Android app that allows users to have an account, access the statistics and redeem points for money.
We plan to build an AI assistance that's going to recognize the objects and the information should be sent to the api.

## What are the next steps to complete the project?

One of the main part of our project is related to object recognition which has not be implemented  due to the time limitation.
Furthermore ,as statistic illustrates, the undiverted waste is not only related to the households. For this reason, the next level of our concept is a way to encourage industries to dispose of waste properly.


## references
https://www.conferenceboard.ca/hcp/provincial/environment/waste.aspx
http://www.sfu.ca/sfunews/stories/2019/04/innovators-aim-for-a-cleaner-environment-.html?fbclid=IwAR3xlCB5O8zUvU6aFd_9VdkQr4iNEBIRERCR7K_8jdC2gVkS4eirFzS0xoo





