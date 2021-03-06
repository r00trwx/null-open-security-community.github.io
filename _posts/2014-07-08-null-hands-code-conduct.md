---
layout: post
title: null hands on Code of Conduct
---

Hello everyone. This post describes an incident that occurred on the 15th of March at a null Humla session, at Bangalore. This incident is a very good example of why it is important to follow the Code of Conduct during null sessions.
<!--more-->

**A little background:**

This incident occurred during the “Memory forensics with Volatility” humla on 15th March 2014. The humla champion for the day was the very able and energetic Rajesh. I was one of the unofficial volunteers for that day. Rajesh had setup several challenges for the participants. To verify if the answers to the challenges were correct, participants had to submit their answers to a web application which was hosted on Rajesh’s laptop. Rajesh was also displaying the number of people who had submitted the right answer on the projector. Whenever someone would submit a correct answer, the counter on the projector would increment.

**What went wrong:**

I was one of the first people in the audience to finish one of the challenges. I submitted the answer, as instructed, to the web application, which told me that my answer was right. I also noticed that the counter on the screen incremented. This was extremely fascinating to me to the extent that I wrote a Python script to submit the correct answer several times, just to see the counter increment on screen. In no time the server was overwhelmed with requests that were coming from multiple computers on the network now. I stopped my script and stood there while Rajesh kept asking the participants to just focus on the challenges and submit the answer only once.

**Why was it wrong:**

Simply put, it was wrong because sending multiple requests to the server with the same answer was never part of the challenges for that day.
The humla session was “Memory Forensics with Volatility” and clearly not “Writing Web Requests and Loops in Python” or “Web Application Security Testing”. Attacking (yes it was attacking because there was no explicit permission given) the web application/server was unethical and should not have happened. The web application was part of the session delivery and had not been setup to sharpen our skills with Python scripting or Web Application Security Testing. Rajesh had clearly indicated that the answer needs to be submitted only once. Several requests were also made to stop other requests that were coming in from the network. Attempts to execute XSS vectors, local file inclusion vectors etc. were also seen. This was wrong at so many levels. It may appear completely harmless and benign but ended up being a discomfort to others. We need to be able to differentiate that even though it is an offensive session, the targets we will be attacking will clearly be indicated by the champion. Anything else is out of bounds.

**How do we prevent this from happening:**

We need to begin with respecting the champion and his/her instructions who are delivering the session out of their passion and willingness to contribute to the community. From there keeping the following points in mind will surely go a long way in making the session a great success:
1. No matter who you are in the community please ensure that the null hands on Code of Conduct is upheld. Behavior like this will not be tolerated as it disturbs the course of the session and breaks the trust between the community and the champion.
2. Learn to differentiate between targets assigned as part of challenges/tasks by the champion and the setup that is actually being used to deliver the session. This is mostly common sense, but simply following the instructions of the champion can help you identify what you can test and what you should not. Help the champion deliver his session. Refrain from doing anything that the champion has asked you not to do. Use your common sense, your best judgment and respect the instructions of the champion. Do not give into temptation to run that port scan or test for SQLi or anything that the champion has not asked you to do. It’s the choices we make that make us who we are.
3. If you are confused about something, ask the champion or the volunteers. Make sure all your questions, doubts, concerns and your full attention is directed towards the champion. No matter how insignificant you think your question may be, the discussion that will follow will solve a lot of other questions that others may have had in their heads and will improve overall learning.

Here’s a video message as well explaining the importance of respecting the Code of Conduct.

<iframe width="560" height="315" src="https://www.youtube.com/embed/EnhWFd57dU8" frameborder="0" allowfullscreen></iframe>

I hope this post highlights the importance of being responsible community members and ensuring that setting examples by behavior is the way to mentor new and younger people in the community. Thank you all for reading. Happy hacking!