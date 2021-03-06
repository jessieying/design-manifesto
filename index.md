### Welcome to My Site

In D-Term of 2018, I took a course on Human-Computer Interaction at Worcester Polytechnic Institute with Professor Lane Harrison. Throughout the term, we learned a lot about design processes and solutions involved in building applications, and how those design choices impact a user’s overall experience. In groups of 3–4 students, we explored specific aspects of human-centered design by creating prototype applications and documenting the entire process. While doing so, I found that for each of these applications, I started following a general design pattern based off of strategies and principles we learned from class. Below, I explain my design process, along with how it applies to projects I worked on throughout this term. Feel free to keep reading to learn more about my design manifesto, or check out my portfolio of projects at the bottom of this page!

* * *

# A Little About Me

Hi, my name is Jessie Ying and I am currently a junior at Worcester Polytechnic Institute. I’m studying computer science and I’ve always been interested in design, so Human-Computer Interaction was definitely an exciting topic for me to learn about. In the future, I hope to apply what I’ve learned from this course to applications I create or work on, in order to provide the best user experience I can. Outside of class, I like playing ultimate frisbee, going for runs, and spending time with my two dogs.

![me](https://jessieying.github.io/design-manifesto/images/jessie-ying.png)

* * *

# My Design Manifesto and Projects

During my design process for building applications, I was able to apply a lot of what I learned from class and readings to my projects. In doing so, I was able to establish five key steps that are necessary in creating a successful application: brainstorming, establishing an objective, user prototyping, testing and feedback, and reflection.



### Brainstorming: Coming up with as many ideas as possible

The design processes for each of our projects always started with brainstorming. We wanted to come up with as many as ideas as possible during this phase; any and every idea was acceptable. An strong emphasis was placed on quantity over quality, because it was necessary to have as many ideas as we could (even the bad ones), so that we can figure out how to make those ideas better and combine the best parts of all of our ideas to create the best product we can. The reading [How to be Creative](http://faculty.washington.edu/ajko/books/design-methods/how-to-be-creative.html) discusses this strategy and encourages externalizing bad ideas to figure out what’s wrong with those ideas and how to improve them.

In [Design for Wellbeing](https://medium.com/design-for-wellbeing/design-for-wellbeing-creating-an-emotion-detector-to-control-videos-41709636be07), we came up with a lot of ideas from our initial brainstorming session, which was very helpful later on when deciding what application to build. We were able to compare the all ideas we came up with and pick the one we thought would be best, while incorporating cool features from our other ideas into our final application as well. Some of the ideas we came up with for this project included using [Affectiva](https://www.affectiva.com) to recommend songs based on user emotion, suggesting breaks when detecting frustration or stress while doing homework problems, showing emojis based on a user's facial expression, and displaying games based on a user's mood. The final idea we went with was a YouTube Emotion Detector that uses the user's expressions to determine their mood, and operates the video player based on the feedback from that.

Another reading, [Ideation Overview](https://kixlab.org/courses/cs374-spring-2017/classes/08-Ideation/), talked about how group brainstorming by itself is not the most effective for coming up with as many ideas as possible. Instead, each member should generate ideas individually and then come together to share and build on each other’s ideas. In [Designing for Another World](https://medium.com/@robertharrison43/design-for-another-world-603bed415e64), my group implemented this strategy and we were able to come up with an overwhelming amount of ideas, which was really great. The results from our group brainstorming session (after each of us shared our own ideas) are shown below:


![brainstorming](https://jessieying.github.io/design-manifesto/images/another-world-brainstorm.jpg)



### Establishing an objective: Making the purpose clear

I found that establishing a clear objective before diving in and building our application was super important and made the overall process a lot easier. It was crucial to set a goal and define the purpose of the application before starting. For example, if the application is trying to solve a problem, what is the scope of the problem and how does the appplication target this? The article [How to Define Problems](http://faculty.washington.edu/ajko/books/design-methods/how-to-define-problems.html) discusses how to derive goals from your data gathered in the brainstorming phase. Another aspect to consider in this phase is who you are designing for. Figuring out the target audience allows you to better understand how to design your application for the users that will actually be using your product.

In the first few assignments, we were given the scope of project as well as our objective and target audience. In [Designing for Others](https://medium.com/@Avorent/an-alternate-design-for-worcester-public-library-21d8021b470c), our goal was to prototype a mobile version of the Worcester Public Library site and cater it towards parents of children ages 3–10. This made it easy for us to jump right in and start designing, so I didn’t really think too much of this step as a crucial one in the design process. However, by the end of the term, the projects were a lot more open-ended, so when we had to establish our own objectives and goals for the user, I found it much more difficult to define our application’s purpose. In [Designing for Tension](https://medium.com/@john3r8amaral/design-for-tension-8081059ed3e5), we had to decide on a topic and the specific use of our chatbot as well as our target audience. [Designing for Another World](https://medium.com/@robertharrison43/design-for-another-world-603bed415e64) was even more open-ended, and we could pick any scene or world to simulate in our virtual reality application.



### User prototyping: Seeing how your application works

Prototyping is another important step in designing an application because it helps to clear up uncertainties about how the application will work, what it will look like, and whether or not it addresses the problem you’re trying to tackle. As mentioned by the author in [Why you should be prototyping](https://medium.com/@rachelbinx/why-you-should-be-prototyping-e4f7d55a6848), first attempts at building applications are almost always wrong, or not entirely perfect. So that’s where prototyping comes in. It allows the programmer to observe how users interact with their application, and to see if their initial designs were a good idea or not. Also, methods of prototyping (such as [paper prototyping](https://www.uxpin.com/studio/blog/paper-prototyping-the-practical-beginners-guide/)) can be very cheap and quick to make for the purpose of seeing how people use your application, so you don’t have to spend lots of time and money on building the final product, just to find out it is not user-friendly, or it doesn’t achieve the purpose you intended it to.

In [Designing for Tension](https://medium.com/@john3r8amaral/design-for-tension-8081059ed3e5), we used the Wizard of Oz prototyping method, as discussed in the article [How to Prototype](http://faculty.washington.edu/ajko/books/design-methods/how-to-prototype.html). This technique involved us having one person simulate being the bot by asking another person questions relating to the product they were “considering” buying. Below is a sample conversation we had with a friend:

**James:** What do you do?

**Bot:** I am the bot of reason, I can help you make better financial decisions. Feel free to ask me questions about things that you are considering purchasing

**James:** Should i buy a new pair of soccer cleats?

**Bot:** Nice! Would you use this for school/work, or for play

**James:** Play

**Bot:** Great! How often will you use it?

**James:** 2 or more times per week

**Bot:** Will these benefit you in the long term?

**James:** Yes

**Bot:** Can you easily afford this, or will this be a big purchase for you?

**James:** I can easily afford this

**Bot:** Great, then treat yo self! You deserve it!

**James:** Awesome!

**Bot:** Is there anything else you would like to ask me?

**James:** No, thanks!

**Bot:** No problem!



### Testing and feedback: Usability of your application

Testing an application is vital to its success and effectiveness. It allows you to find out if your application is usable and accomplishes its purpose. During in-class demo days, we were able to do this by showing our application to people from other groups and observing how they interact with our product. Sometimes we found that users didn’t quite do what we expected them to, or they didn’t entirely understand a certain aspect of our application. For example, in [Designing for Wellbeing](https://medium.com/design-for-wellbeing/design-for-wellbeing-creating-an-emotion-detector-to-control-videos-41709636be07), some users had trouble making the facial features our application was programmed to detect, while others didn’t make facial features at all. We took note of this for future improvements. Below is the sad expression that our Designing for Wellbeing application is supposed to detect. However, this did not occur for several users, so they were not able to experience one of the key features of our application.

![sad](https://jessieying.github.io/design-manifesto/images/wellbeing-sad.png)

In addition, feedback from users after testing was very valuable, because it allowed us to see what they liked and didn’t like about our application, as well as other possible features that we could implement that users might want or need.



### Reflection: Evaluating strengths and weaknesses
At the end of any design process, reflecting on things that went well and things that didn’t is a very important step. Acknowledging areas of improvement helps us see what we could have done better and what we could do to improve our application in the future. Also, in this phase, we established what potential next steps for our project would be  if we had more time to work on it. For our last project, [Designing for Another World](https://medium.com/@robertharrison43/design-for-another-world-603bed415e64), we were able to gather lots of feedback about our virtual reality application. We found that people liked the overall look and feel of our scene and the idea of it being interactive, but they wished there were more games features, such as winning and losing. This helped us to see what worked well, in addition to determining what we could do to improve upon our application next time if we had more time.

Overall, designing applications to meet users’ needs is a huge component of computer science. Programs are designed to be used by people, and in order to make those programs as effective and usable as possible, careful consideration of the design process at every step is crucial to the application’s success. Taking this course has made me more aware of how much design choices affect user experience, and I plan to apply what I’ve learned to applications I develop in the future.



* * *

# Portfolio

Click on any of my projects below to learn more:

**Design for Others**
[![Others](https://jessieying.github.io/design-manifesto/images/design-for-others.png)](https://medium.com/@Avorent/an-alternate-design-for-worcester-public-library-21d8021b470c)

**Design for Understanding**
[![Understanding](https://jessieying.github.io/design-manifesto/images/design-for-understanding.png)](https://medium.com/design-for-understanding-design-process/design-for-understanding-b3d08904b868)

**Design for Tension**
[![Tension](https://jessieying.github.io/design-manifesto/images/design-for-tension.png)](https://medium.com/@john3r8amaral/design-for-tension-8081059ed3e5)

**Design for Wellbeing**
[![Wellbeing](https://jessieying.github.io/design-manifesto/images/design-for-wellbeing.png)](https://medium.com/design-for-wellbeing/design-for-wellbeing-creating-an-emotion-detector-to-control-videos-41709636be07)

**Design for Another World**
[![Another World](https://jessieying.github.io/design-manifesto/images/design-for-another-world.png)](https://medium.com/@robertharrison43/design-for-another-world-603bed415e64)






