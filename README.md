# reading-notes
Using this repo to keep notes for Code Fellows bootcamp 

## Code 201
HTML
1.	When should you use an unordered list in your HTML document? 
When numerical ordering is not necessary. But it has been deprecated. 
2.	How do you change the bullet style of unordered list items?
The bullet style will change in an unordered list when they are nested inside one another.
3.	When should you use an ordered list vs an unorder list in your HTML document?
When ordered matters. An unordered list will use bullet points and not needed. Ordered lists will have numbers or letters next to them.
4.	Describe two ways you can change the numbers on list items provided by an ordered list?
One way would be to nest one inside the other. Or by setting the type attribute. 
CSS

1.	Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
Margin is the invisible padding of around the box. It can have positive and negative values this can cause separation or overlapping of boxes. 
Padding is the space between the border of the box and the content inside of it. There is no negative padding.
2.	List and describe the four parts of an HTML elements box as referred to by the box model.
Margin, padding, border and shorthand. Each will take care of different aspects of the “box” in order for it to do fifferent things either internally or externally. 

JS
1.	What data types can you store inside of an Array?
String, numbers, objects, and other arrays
2.	Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

Yes it is a multidimensional array. You can access it by specifying the location such as people[0][0]
3.	List five shorthand operators for assignment in javascript and describe what they do.
X +=1 same as x plus one
X-+1 same as x minus one
X *=1 same as x times 1
X /=1 same as x divided by 1
X %=1 same as x remainder of division to 1
4.	Read the code below and evaluate the last expression and explain what the result would be and why.

10dogfalse – everything gets treated as a string
5.	Describe a real world example of when a conditional statement should be used in a JavaScript program.
When you want to make a decision based on one expression. Example is person over 21 if true sell alcohol if not do not sell alcohol.
6.	Give an example of when a Loop is useful in JavaScript.
In order to iterate over an array and calling each individual item is not feasible. 






HTML
1.	To create a basic link, we wrap text or other content inside what element?
We would use an anchor tag and that can be applied to almost any element. An href would be needed to make this work. 
2.	The href attribute contains what information?
The href attribute will contain the actual link to the file it may come from a local directory or from online. 
3.	What are some ways we can ensure links on our pages are accessible to all readers?
Being clear with what part of the link is clickable, keeping link text as short as possible, reduce the amount of links and try to be clear what the link will do. 

CSS
1.	What is meant by “normal flow”?
Elements in a file will layout in the way they appear on the file and in the way they are modified by the stylesheets applied
2.	What are a few differences between block-level and inline elements?
Block level elements will modify the HTML based on blocks while inline elements can be block level but the intent of inline is to modify a specific tag 
3.	___ positioning is the default for every html element.
Static positioning is the default for every html element. Meaning that they are not affected by the four areas of the box model.
4.	Name a few advantages to using absolute positioning on an element.
It will allow for mor precise control with the ability to overlap one element on top of another. 
5.	What is a key difference between fixed positioning and absolute positioning?
With fixed positioning the item being shown will not move even when moving the webpage is moved around.  Similar behavior is seen in excel pivot tables. 

JS
1.	Describe the difference between a function declaration and a function invocation.
With function declarations the developer defines the behavior and with function invocation you are calling a function to behave the way it has been defined. 
2.	What is the difference between a parameter and an argument?
Function parameters and arguments are the same thing it is just a matter of how they are referred to when speaking of them. 

Pair Programming
Reason 1 – Engaged Collaboration  - This would help me because there have been times where I have spent longer than 15 minutes on a problem and decided to not ask for help or take a break. Also, I like to bounce ideas to other people in order to see if I’m approaching a problem correctly. 
Reason 2 – Learning from Fellow Students – This I like because I know I do not know everything and learning to view how other people see problems can be insightful. 

•	 who you met with
I met with Mike Nguchie he is a computer engineer for an organization providing consulting services for closed government programs. 
•	how you are connected to them
I met Mike through my fiancé one month ago. I called him earlier this evening and received some knowledge on what industry is doing and where it plans to go. 
•	what you learned about that person and their work
I learned that there is allot of work to be done in the area of cloud development and adoption. Allot of organizations both commercial and government. 
•	and how you can help them.
The way I can help is by learning all of the fundamental aspects of web programming and get a firm understanding of all concepts to be covered in this coding bootcamp. Along with this getting an AWS or Microsoft Azure certification will be key. 

HTML
1.	What is a real world use case for the alt attribute being used in a website?
Alt is useful for when a webpage is not able to load up the original image being requested. Alt will display a text that the developer chooses when this error occurs.
2.	How can you improve accessibility of images in an HTML document?
By using captions or the alt tag to the image being precented.  The alt tag would be useful in situations when the person is not able to see a picture and would require a screen reader to be able to provide a description. 
3.	Provide an example of when the figure element would be useful in an HTML document.
Figure would be useful when displaying an image and being descriptive with the image. The use of the figcaption with the figure tag.
4.	Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
A gif is a small image that can be used for animations as opposed to other media that is used for more detailed and longer media. SVG on the other hand is another way of drawing shapes on the web browser.
5.	What image type would you use to display a screenshot on your website and why?
I would use a jpeg file that has been converted. Depending on the app used the file extension may be one that may not be compatible with all web browsers. 

CSS
1.	Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
Foreground color will be used for color that you want to show on top of background color. Background color will take the entirety of a location if no foreground color or data is there. 
2.	Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
I would first start with a css stylesheet and use color palates that help with the website. I would use appropriate color for the website. 
3.	What should you consider when choosing fonts for an HTML document?
One would be how readability impacts the text, location of the font, and how functional is the font. 
4.	What do font-size, font-weight, and font-style do to HTML text elements?
Font size will change how big or small the font appears in the webpage. Font weight works similar to the bold feature in Microsoft word with the exception that you can go lighter in appearance of the font. 
5.	Describe two ways you could add spacing around the characters displayed in an h1 element.
Word spacing can be done with the word-spacing css property. This will allow you to choose a size you would like to apply to the spacing of words when presenting text. Example:
h1{
word-spacing: 2 rem;
};


•	What do you hope to get out of your experience?
•	I hope to get a detailed and deeper understanding of current best practices and real world practices of software development so that I am able to get a job and develop websites on my own. 
•	Why did you start classes now, at this time in your life?
•	Unfortunately, I got sick in the Army and now no longer able to perform at the same rate as I used to. My response and memory have been affected by my TBI. 
•	What's the "why behind the why", your deeper motivation for pursuing this?
•	I love software development in it’s entirety. I feel that being skilled in this area will help my career and the future I plan to give my daughter. 

Git Practice 
•	How did this go, overall?
•	Overall, it went great there was a lot of useful information and the interactivity of the site was great.
•	What observations or questions do you have about what you’ve learned so far?
•	There are allot of questions I have. Although I have a good understanding of what is going on actual practical practice is still needed. 
•	How long did it take you to complete this assignment? And, before you started, how long did you think it would take you to complete this assignment?
•	Total time was 2 days with breaks and I would say total time was about 2 hours total. 
PREP Social Media

https://github.com/carlitos-1988

https://www.linkedin.com/in/juan-olmedo-5613784a/

https://www.army.mil/article/254081/fisher_house_provides_place_to_rest_recover


Self Assessment 

Leadership Competency
Demonstrates proficiency in influencing others by modeling accountability & integrity, building relationships, and mentoring others.

Communication Competency
Demonstrates proficiency in written and verbal communications, active listening, and exchanging ideas/knowledge.

In the above areas of growth I have known that my communication and leadership needs help. Knowing this through the assessment puts it in writing and will work on these things. 

Business Acumen Competency
Demonstrates keen understanding of business operations and customer needs. Uses this to drive the organization towards broader business objectives, in consistent alignment with company mission and vision.

Quality Competency 
Demonstrates ability to effectively assess quality of work including that of their own and others, using keen attention to detail. Effectively identifies the root cause of problems with rigor, provides and applies solutions that prevent recurrence.

Confirm Slack, GitHub, and Canvas Setup
-	Done with all of the set ups. 
Power Hour
1.	Share one or two ways the speaker’s information will change your approach to your career transition.
1.	One way that the speakers information has changed my approach to career transition is in the ability to be knowledge able in the tasks and skills I decide to take on. I do not know the extent of the speakers knowledge overall but I do know he has invested a lot of time to know what he knows and is not afraid to admit when he does not know something. 
2.	List a few key take-aways from this presentation.
1.	A few takeaways from the presentation are that there is more than one way to play with CSS in this case codepen.io
2.	Another is how to use animations to be tied to elements of HTML along with the accepted standard for animations and transitions
3.	If there is animation to take place the best place for animations to occur is within CSS and not JS because JS may not be as friendly to a browser.
3.	Share a screenshot of your LinkedIn connection request, including a nicely worded note, sent to the speaker or someone else at their company.
1.	Was not able to send message apparently I need premium for this but did follow him.
2.	 


JS
1.	How would you describe an object to a non-technical friend you grew up with?
An object is a collection of functions and attributes that are given by the programmer. By programming attributes and behavior into these objects one would be able to create objects based on a template.
2.	What are some advantages to creating object literals?
Object literals are good for when you are trying to pass objects that are related to an array or server so that the data does not have any differences in it. 
3.	How do objects differ from arrays?
Objects define a single instantiated class with many attributes that can be repeatedly accesses. An array is a data structure that will hold many different data types including objects for use. Each will have methods built in but objects will have the ability define custom behavior with the use of functions. 
4.	Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
One example for using bracket notation to access an objects property would be to access a property as a variable. When defined as a bracket inside a function the ability for it to change is possible when calling it by the function name.   
5.	Evaluate the code below. What does the term this refer to and what is the advantage to using this?
This would referrer to the variable/function inside the object. If there is another variable outside of the object with the same name then there could be a collision. In this case it would allow for the developer to be precise when choosing an attribute or function. 
DOM
1.	What is the DOM?
The Document Object Model is a representation of the HTML webpage. By calling the nodes available in the DOM one can give behaviors to the HTML webpage by interfacing with the DOM. 
2.	Briefly describe the relationship between the DOM and JavaScript.
The relationship between the two would be that one (JS) will be responsible for defining behaviors that would be available inside the DOM. In essence one would be considered the skeleton and the other would be the muscle that allows the skeleton to move about different axis. 
Instructor Sync

•	What are your goals while taking this course?
•	My goals are to learn as much as possible. I want to also be proficient with my coding practices. While I do feel familiar with some of the material in class I know now that I am not as proficient as I though so I will continue to get the practice in so that I can become a confident developer. 
•	Are there any areas of concern, questions about the course or adjustments we might consider?
•	No adjustments the material and teaching methods provided work for me. 
•	What professional proficiency would you consider to be your top strength?
•	One proficiency I would consider my top strength at the moment is my ability to not give up on issues I encounter. My dedication to this course and learning software development gives me the ability to be percistent with this learning. 
•	What areas of professional competency would you like to improve?
•	I would like to continue to improve with HTML, CSS, JS, and Git. 


Customized Answers to Common Behavioral Questions

Use this document to curate your own answers to some of the most common behavioral interview questions. 

For each question, answer in the S.T.A.R. format, by filling in the outline below. 

By the time you graduate, you’ll have 10 or more questions answered here, and ready for use in your job interviews!
Behavioral Questions:
1.	Question 1: What are your career gloals  
1.	Situation: 
1.	 Give me a specific example of a time when a co-worker criticized your work in front of others. How did you respond? How has that event shaped the way you communicate with others?  
2.	Task:
 One situation I recall is when I was given the task of generating a bash script for the organization to use for importing users from one database to another. Needless to say one of my co-workers criticized my work in from of the team and was angry at the fact that it was incomplete. 
3.	Action: 
The action I took for this was to give myself a couple of hours to find out why my script did not work and found nothing for those couple of hours. I then went to the senior engineers to see if they could help me out. I did find a person who told me that I was not creating the database destination server before importing the dump file. 
4.	Result:
The ultimate result is that on the next team meeting I told my co-worker what I found and what I ultimately did to correct the issue. He was satisfied with my result and with my approach and apologized for his outburst that day. I Informed him that I understood because my lack of delivery caused the schedule to move +2 days to the right and I was not happy with my impact on this. In the future I will make sure I have successfully tested out my scripts and ask for help ahead of time so that large projects are not impact from my inability to test and ask for help. 
2.	Question 2: Tell me about a time when… 
1.	Situation: 
1.	Describe a situation when you had many projects due at the same time. What steps did you take to get them all done?  
2.	Task: 
1.	 I was tasked with continuing my duties of installing SW on peoples machines and setting up and deploying new projects on Atlassian but one day I was also tasked with finding all of the users for the Atlassian SW and understanding how licensing is being conducted at each program. As an Enterprise Services employee I had to identify and understand licensing for the Aerospace Sector and the Missile systems sector each of which carried over 5k employees and a number of programs that included both open area and closed networks. 
3.	Action: 
1.	 I took a lot of time to understand the layout of the users along with the programs that the licenses were taking. I ultimately delivered the needed information to the ESPM (Enterprise Services Program Manager) and served as a liaison for the ESPM to make informed decisions for co-terming our licenses for the next 18 months with the ultimate goal of establishing an enterprise agreement between Atlassian and Northrop Grumman 
4.	Result:
1.	 While I did complete the task I did notice that I was not taking care of my service tickets and some of my customers complained that I was not installing SW on time. I did receive negative scores for service delivery and my manager had a discussion with me. Although, she did mention that the project for the ESPM helped my case. 
3.	Question 3: Tell me about a time when… 
1.	Situation: 
1.	 Give me an example of when you involved others in making a decision.  
2.	Task: When I originally got hired on to my current organization, I did not know much of what was going on. I simply went with what I was taught and did not know how to properly install and configure the SW I was responsible for. After talking with the new employees, it seemed that none of us knew this part of our job, many of us were lost. 
3.	 Give me an example of when you involved others in making a decision.  
2.	Action: I decided to get with all of the new employees and make a list of what taskings we did not feel comfortable with and what taskings we did feel comfortable with. I ensured all of the current and new employees took part in this meeting so that I captured our real understanding of our roles and responsibilities. 
3.	 Result: The outcome of this ultimately led management to give us time to conduct more over the shoulder training with senior analysts and report our findings and tips and tricks to a shared SharePoint site so that newer employees would be able to capture the knowledge we had gained along with POCs for who would be better able to explain the lessons learned. 


Domain Modeling
1.	Explain why we need domain modeling.
Domain modeling is needed because it helps to ensure that the software being built is answering the needs of the organization or business unit it is intended for. By doing this developers will be able to develop software that is meets specifications much like the lab for today.
HTML Table Basics
1.	Why should tables not be used for page layouts?
They reduce accessibility, they are not automatically responsive, and the use of tags creates an alphabet soup of tages.
2.	List and describe 3 different semantic HTML elements used in an HTML <table>.
Using th for table header and that it is not meant to hold data
Using thead, tbody, and tfoot for different uses other than the traditional data that it is meant to display. For eample tfoot can have summary information of the data and or totals of the data just precented  thead same as described above. Lastly tbody used to group content of a table that contains the td

Introducing Constructors
1.	What is a constructor and what are some advantages to using it?
Constructors are good for utilizing classes in a repeatable manner where constructor arguments will fill in the needed data of an object. Sort of blueprinting objects bases on classes previously defined
2.	How does the term this differ when used in an object literal versus when used in a constructor?
3.	In a constructor the this keyword will map the argument passed to a constructor to an attribute of your choosing. Meaning that if you pass an argument to a constructor and would like to assign it to a classes attribute then using the this keyword would bind them together. 
Object Prototypes Using A Constructor
1.	Explain prototypes and inheritance via an analogy from your previous work experience.
•	NOTE: This is a very common front end developer interview question
Prototypes If I got this correctly are sort of like static objects that allow a uniformed behavior for all classes that inherit from that particular class. One analogy of this would be how most humans have the ability to talk and walk. In programming terms we can define this in each person and have each person independently implement their own version. Because all humans are different and we would like for them to behave in a similar way we would pass this responsibility to a human object and define this behavior there. We then would require all people to extend from human and then we would have all humans implement this behavior and modify as needed. For example, no appendages would mean that speed of walk or capability of walking would be impacted. 

1.	Flexbox is designed for one-dimensional content. Explain what this means.
It allows one dimensional spacing by allowing content to be moved in a one-dimensional space. This makes it easy to manage space alignment and size. 
2.	Explain the difference between the main axis and cross axis.
Flex direction along with row will control along the x axis and column will control vertically making it simple to move items in a two dimensional space. 
3.	How can using certain properties of flexbox negatively impact accessibility?
If not used correctly flex direction can change the layout of the information and this can affect screen readers for people using them. Also, flex wrap where content wraps around instead of just laying it out horizontally. While it looks good this may also affect screen readers. 
1.	What are some advantages of using flexbox over float?
Justify content align items make it easy to align items on the page. Instead of clearing out the float inherited values or the default float. 
2.	How does this topic connect with your long term goals?
It will help me better work with CSS which I feel is one of my weakest areas of this course so far. 



Dealing With Ambiguity in the Workplace 
1.	Share one or two ways the speaker’s information will change your approach to your career transition.
One of the biggest lessons learned is how workplace ambiguity if not dealt with properly a problem domain may not be fully understood. Using User Stories, System requirements, and properly collecting requirements from a client are important things to do. Ambiguity in short becomes a problem to engineers to be able to fix a problem that is appropriate and within budget. 
2.	List a few key take-aways from this presentation.
Takeaways:
•	You get what you asked for not what you want
•	Asking questions when collaborating all of the time not only from the customer but also from within the team. 
•	Consequences of ambiguity:
o	Low productivity 
o	Wasted time and effort 
o	Creating the wrong thing 
o	You can give inaccurate estimates for the customer 
o	You can give a best guess that may not be accurate
Lastly It is ok to fail and communicate often. 
3.	Share a screenshot of your LinkedIn connection request, including a nicely worded note, sent to the speaker or someone else at their company.
I was not able to send message but did follow Amanda. 
 


Video and Audio Content
1.	Explain how the ability to use video and audio on the web has evolved since the early 2000s.
Since the early 2000s audio and video seemed to be a thing that people would not want unless they went to YouTube or a video site since bandwidth was not what it is today. Also with video and audio people had to use what they had locally on their machines but with the evolution of the web sharing videos and creating videos has become a thing that is common. 
2.	Describe the use of the src and controls attributes in the <video> element.
Source for the video element will work similar to the source in the img tag. The video will play based on the source. The controls tag will give the user controls over the video that is being presented so that people who need to pause the videos for many reasons are able to do so. 
3.	Why is it important to have fallback content inside the <video> element?
It is important to have fallback content inside the video element in the event the browser being used does not allow for the original content to be played. 
4.	Write a very short story where <audio> and <video> are characters.
Not sure what is being asked but if a story is needed audio was a person who always wanted to say something to everyone and while some people listened other people decided to tune him out. One day he decided to get better and changed himself in to video and was able to take on both forms when ever needed. To this day audio will accompany video because of this need. 

A Complete Guide To Grid
1.	How does Grid layout differ from Flex?
CSS grid is a two dimensional layout system that allows developers to tackle the box model problem. Flex on the other hand is a one dimensional approach to the box model. 
2.	Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
Grid container will be the parent element of all of the grid items. This will the top level item that will host the grid items. The grid item is a child of the grid container the items can be sub-element for children of the grid items but ultimately the grid container will be the parent of them all. Lastly, grid lines are the dividing structure for the grid they can either be vertical or horizontal lines. Other things to note are grid cell would be the space between the cells. And Grid track would be the space between two cells that are together in a rwo. 
Responsive Images
1.	Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
Images should be responsive because they need to be able to keep the flow of the windows they appear on. If images are not responsive they would either be too small or to large depending on the window they are being displayed on. 
2.	Define the following <img> attributes srcset and sizes. Write an example of how they are used.
Srcset will define the image and let the browser choose along with this you can set the width of the image being used. Sizes will be activated once certain sizes of the screen are met. Sizes will then take effect. 
3.	How is srcset more helpful for responsive images than CSS or JavaScript?
Srcset seems to be more helpful by first defining the with of an image and when used with sizes the images will change according to the viewport being presented. Overall both make it so that CSS is not heavily involved and allot of the heavy lifting is done with the srcset tags.  



Give Your 60 Second Pitch

1.	What were you doing before you decided to change careers?
I’m currently employed at Northrop Grumman as a software development analyst taking responsibility for enterprise services applications mostly concerned with Atlassian a development and collaboration software. 
2.	Why did you decide to learn Software Development?
I decided to learn software development because as an analyst I got to see the challenges developers face when implementing features with Atlassian and other software. From my observations I was immediately intrigued in this field. I have studied java and other software  on my own but know I am on track to graduate from a coding bootcamp to further expand my skills in this area. 
3.	Why did you pick this specific skill?
Python and web development is an essential skill when dealing with enterprise services. When dealing with many internal customers’ needs and wants are always tasked upon us and having this skill will be crucial to modifying commercial off the shelf software. 
4.	Ideal environment you’d use this skill?
The ideal environment would be to generate software for flight software. I would like to develop graphical user interfaces for flight test software or actual testing software for flight items. I would also like to modify COTS software to fit the needs of an organization. I would like to be involved in many areas of development. 
5.	Previous experiences that give a boost to your new career in tech?
Previous experience that can give me a boost in my new career in tech is the understanding of networks and implementing automation scripts that would enable large teams to get up to date. As for security I currently have my security plus certification and will be getting my google IT fundamental certificate along with my Java SE8 certification by the middle of the year. 
Pitch:
I’m currently employed as a software development analyst for Northrop Grumman. My program managers and team members frequently entrust in me to be able to deliver project on time and on schedule with many perspectives to the problems at hand. I’m looking for a position that would allow me to utilize what I have learned over the last couple of years to include my web development training, security plus, and java certifications. In short, I have received a lot of training over the last two years and would like to make a difference with the software I will get to develop.  


JavaScript Canvas
1.	What does the <canvas> allow a developer to acheive?
It allows developers to generate responsive images. Overall more responsive images are allowed to be generated
2.	What is the importance of the closing `</canvas> tag?
If the closing tag is not there the browser may not be able to correctly parse the HTML and havascript code that manipulates the emelement 
3.	Explain what the getContext() method does.
4.	It allows the ability to get re rendering context and create a drawing APU for the canvas element 
Chart.js Documentation:
1.	What is Chart.js and how it can be brought into your project for creating responsive and customizable charts.
2.	It is a library 
3.	List 3 different Chart types you can create using Chart.js.
Easily Create Stunning Animated Charts with Chart.js
1.	What are some advantages to displaying data via a chart over a table?
2.	How could Chart.js aid your previously created applications visually?
Class 13
Local Storage and How To Use It On Websites
1.	Why would a developer use local storage for a web application?
When you would want for the user of your site to save information about the session that was just had. This could be a cart, some sort of selection of items or anything worth saving short term and not is some sort of database. 
2.	What information should not be stored in local storage?
Personal information that relates to the user. Most data you would want to save is information about the session and not the person who is visiting the site. 
3.	Local storage can store what type of data? How would you convert it to that type before storing?
Local storage only works with string  and when working with this type of data using JSON.stringify() and JSON.parse() would be beneficial to storing the needed data.
Stage Fright 

	Two things that I will be implementing when speaking in public for the future would be focusing on my non-verbal communication and being more aware of where I place my hands and reduce putting my hands in my pocket. I know I have done this in the past and have been told I do this. From now on I will make sure I carry a clicker or some sort of object that will prevent me from doing this.  Another thing that I will be doing is including the audience. I’ve known myself to ramble on for too long and lose the audience I am communicating with. From now on I will make sure I call out the audience in the middle of my public speaking and facilitate QA’s with the audience. If I do these two things immediately I know that my public speaking will get better and I may be able to identify other areas that I do not do well in.




CSS Transforms
1.	What does a CSS transform allow the developer to do to an element?
2.	CSS transform allows devs to modify the appearance and position of an element in 2 and 3 dimensional space. Things like rotate, scle skew and others can be done. 
3.	Provide an example of a transform and how you could see that being used on a website.
4.	Translate for when there is an element in Remo like request help moves out of the page in order to input data for requesting help. 
CSS Transitions & Animations
1.	What does a CSS transition allow the developer to do to an element?
Transitions will change a property over time when the element is interacted with. Things like hover or changing the content apply here. This is more for the animations that take place on them. 
2.	How does a CSS animation differ from a CSS transition?
3.	Transitions and animations differ in that transform will change how the item is interacted with while an animation is more so a visual display of an item. And item can have a an animation as it transitions. 
8 simple CSS3 transitions that will wow your users
1.	What are some benefits to using CSS transitions on websites?
2.	Some benefits are that they are easier to implement compared to the JS animations. This in turn makes the code to be more maintainable when working with other developers. 
3.	How this topic fit in with your long-term goals?
4.	This topic fits with my long-term goals by understanding that animations and transitions are pieces of code that can exists in CSS and by being able to understand and maintain this code as a CSS item I will be able work effectively in teams and maintain code better over a long period of time. In short, this understanding this will help with collaboration moving forward. 
 
Communication Plan 

•	What hours will you be available to communicate?
•	Juan Olmedo – will be available from 0900 to end of day every day Pacific.
•	Ben Halliwell – 0900 to 1800 ()EST 1200 to 2100
•	0900 – End of day
•	What platforms will you use to communicate (ie. Slack, phone …)?
•	We will be using Slack, Remo, and if necessary, google meet for this project. 
•	How often will you take breaks?
•	The team will take break every hour for at least 10 minutes to prevent fatigue. 
•	What is your plan if you start to fall behind?
•	Ask the instructor or the TA’s for help
•	How will you communicate after hours and on the weekend?
•	We will use slack to communicate over the weekend. 
•	What is your strategy for ensuring everyone’s voice is heard?
•	How will you ensure that you are creating a safe environment where everyone feels comfortable speaking up?
•	We will have our team lead Hayden ensure everyone is allowed to 


•	What components of your project will live on GitHub?
All components relative to the project. The Gut ignore document will have files removed that are not relevant to the project. 
•	How will you share the repository with your teammates?
Repository will be shared via the link on the team. Only one person will be allow to merge all of the pull requests for the team. Each team member will create branches locally and request to pull the request. 
•	What is your Git flow?
Git flow will be ACP by each team member and each team member will generate a pull request to be managed by one person on the team. 
•	Will you be using a PR review workflow? If so, consider:
•	How many people must review a PR?
Only the people who submit the PR will have to attend everyone else will be invited but not required to participate. 
•	Who merges PRs?
Hayden Cooper will be responsible to merge all of the PRs. 
•	How often will you merge?
We will merge every single day and as necessary during the day. 
•	How will you communicate that it’s time to merge?
Slack message will be sent out and response will have to be required to understand who will be coming or who will not be coming. From time of invitation there will be a 30-minute timer where the meeting has to begin. Once all of the pull requests have been completed a message will be sent out to the team to pull from main in order to have the latest working copy of the code repo. 


![image](https://user-images.githubusercontent.com/43771360/230510751-375cabe6-7fa6-4d1c-9d6c-2a7244968e19.png)


## Code 301 - Intermediate Software Development

# Notes so Far as of 21 apr 2023 
Prework 301

 

https://github.com/carlitos-1988/arrow-functions/pull/1

•	A question within the context of today's lab assignment
o	I understand that arrow functions seem easier to work with but what is the point of them if they just reduce code? The only reason I see to use them is to get window properties and context for use later on. Other than this I really do not see a point to them
•	An observation about the lab assignment, or related 'Ah-hah!' moment
o	One aha moment I had was with assignment was with the use of parenthesis with arrow functions. I was confused at first with how they would be used but luckily there were more examples to this.
•	How long you spent working on this assignment
o	Total time 1 hour.



Readings: Introduction to React and Components
1.	What is a “component”?
1.	A component is a modular, replaceable and reusable piece of code as an interface that allows for code to have a set pattern of behaviors to be used across code.
2.	What are the characteristics of a component?
1.	They are reusable, replaceable, non-context specific, extensible, encapsulated, nd independent. Once real world non coding example would be the use of an uninterrupted power supply. The only thing one would have to know is that you need to feed it a certain amount of wall power and it will produce a certain amount of power for a certain amount of time. The actual time and support will vary by manufacturer and how they provide power will also depend on this. In either case all one would have to do to fix one would be to replace it as it will not harm other parts of your computer
3.	What are the advantages of using component-based architecture?
1.	It assists with deployment of end of life or improved code by changing only certain areas without  breaking the rest of the code. Modifies and reduces complexity of the system by understanding inputs and outputs to the system without complicating what is needed for the rest of the team. Components can be reused in a modular system that allows for portability.

1.	What is “props” short for?
1.	It stands for properties
2.	How are props used in React?
1.	In react they are used to pass data from one component to another
3.	What is the flow of props?
1.	The flow of props has 3 steps
1.	Define the attribute and the value data
2.	Pass it to child components using props
3.	Render the pops data

 



Portfolio prep:
https://github.com/carlitos-1988/portfolio-prep

Reading Notes Repo:
https://github.com/carlitos-1988/reading-notes

Links:
Resume:
https://docs.google.com/document/d/1mubefHUNvOdGcLiC4zwCOWUV6YcywH_5wAM_tpVb6CM/edit?usp=sharing
LinkedIn:
https://www.linkedin.com/in/juan-olmedo-5613784a/
GitHub:
https://github.com/carlitos-1988?tab=repositories
behavioral questions:
https://docs.google.com/document/d/1e0c4FNfDBCS5IxWiS8lgOmDPjwjktpO8VjwMlYp3UQ0/edit?usp=sharing
Talk to your Network:
•	who you met with
I met with Mike Nguchie he is a computer engineer for an organization providing consulting services for closed government programs.
•	how you are connected to them
I met Mike through my fiancé one month ago. I called him earlier this evening and received some knowledge on what industry is doing and where it plans to go.
•	what you learned about that person and their work
I learned that there is allot of work to be done in the area of cloud development and adoption. Allot of organizations both commercial and government.
•	and how you can help them.
The way I can help is by learning all of the fundamental aspects of web programming and get a firm understanding of all concepts to be covered in this coding bootcamp. Along with this getting an AWS or Microsoft Azure certification will be key.

Targeted Job Search:
https://docs.google.com/spreadsheets/d/16HHDWPbF7-IIbyWB5aLxUc0jzhFnKNABthRiKo38JLM/edit?usp=sharing
Professional Pitch:
Need to create video: https://codefellows.github.io/common_curriculum/career_coaching/301/professional-pitch-draft
Professional Companies:
https://docs.google.com/document/d/1prqZGHWMXf7HS28nCPWPhFoMDogszHF3p_BXsbdTkqE/edit?usp=sharingrea
1.	What is React?
1.	A user Interface Library
2.	Component Architecture
3.	Data Flow in React
4.	Component State
2.	What is a component?
1.	Components are independent usable parts of code where they can be injected where needed. With the DOM it would likely be an attribute for HTML rendering or some widget on a webpage
3.	What is the dataflow of React?
1.	The dataflow for react is unidirectional, meaning data from parents flow down to children and not the other way. Because these children will not be able to update data on the child level and data is only updated at the top level. This ensures one directional architecture which is easier to manage.
4.	How do we make a React element a DOM element?
1.	Using the following code:
5.	function tick() {
6.	const element = (
7.	<div>
8.	<h1>Hello, world!</h1>
9.	<h2>It is {new Date().toLocaleTimeString()}.</h2>
10.	</div>
11.	);
12.	root.render(element);}
1.	Where root is a document.getElementByID and the DIV is everything that will be rendered
13.	React is a User Interface ______.
1.	That allows you to build applications through components and allows for manageable scalable applications to be built.
14.	Which direction does data flow in React?
1.	One direction parent to child only
15.	Every component manages its own ____.
1.	State

Classes Example:
https://replit.com/@carlitos-1988/ES6-Classes
Who are you (name and history),
•	Juan Olmedo
•	Los Angeles CA
•	Live in Seattle Washington Area
•	Air Force 11 years
•	Army 2 years
•	Engaged and have 1 daughter

what you do (job title),
•	Northrop Grumman SW Analyst
•	
and what value you bring (your why/passion).
•	Out of the box thinker
•	Passion for learning
•	Not easily dissuaded by difficult problems
•	Enjoy collaborating and learning from others




Retrospectives
1.	What went well, that I might forget if I don’t write down?
2.	What did I learn today?
3.	What should I do differently next time?
4.	What still puzzles me, or what do I need to learn more about?


Reading State and Props
1.	Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
1.	render
2.	What is the very first thing to happen in the lifecycle of React?
1.	Mounting the constructor
3.	Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
1.	Render
2.	Constructor
3.	React updates
4.	ComponentDidMount
5.	ComponentWillunmount
4.	What does componentDidMount do?
1.	It initializes networks requests or initializes the DOM. This is the place to set up subscriptions using APIs.


5.	What types of things can you pass in the props?
1.	You can pass Strings, numbers, Booleans, arrays, objects and functions
6.	What is the big difference between props and state?
1.	State is managed by each component individually and props are passed from parent to child. Props can all be seen in the React developer tools
7.	When do we re-render our application?
1.	Function usage like setState() will cause a change in the application by informing the app to update as there has been a change in state.
8.	What are some examples of things that we could store in state?
1.	Some examples include user generated data such as input, changes in state for the application, and if checkboxes are selected or not.




Networking: Generating Opportunities

VetsinTech Front End Web Dev Cohort Sponsored by DraftKings
5 Jun @ 5:00 PM - 29 Jun @ 7:00 PM PD $10.00

https://vetsintech.co/event/vetsintech-front-end-web-dev-cohort-sponsored-by-draftkings-16/
1 May @ 5:00 PM - 25 May @ 7:00 PM PDT

VetsinTech Python Fundamentals for Data Science by Lockheed Martin!
1 May @ 5:00 PM - 25 May @ 7:00 PM PDT $10.00
https://vetsintech.co/event/vetsintech-front-end-web-dev-cohort-sponsored-by-draftkings-15/

VetsinTech Security+ Bootcamp
12 Jun @ 7:00 AM - 16 Jun @ 4:30 PM PDT $10.00
https://vetsintech.co/event/vetsintech-security-bootcamp-9/
(On-Line) Resume Reviews for Software Engineers and QA
12 Apr 2023 @ 5:30 pm
https://www.meetup.com/qadev-seattle/events/292772981

Dev Hangout
Tuesday, April 11, 2023 at 7:00 PM to
https://www.meetup.com/pnw-dev-network/events/292689741


1.	What is node.js?
1.	Programming language that uses the V8 engine used in another chromium browsers. It allows for JavaScript code to be compiled directly to native machine code so that the computer can execute.
2.	In your own words, what is Chrome’s V8 JavaScript Engine?
1.	It allows for code to be complied and ran in the native computer rather than in the browser.
3.	What does it mean that node is a JavaScript runtime?
1.	Node is a program that can be used to execute JavaScript on the computer, in other words it is a JavaScript runtime.
4.	What is npm?
1.	It is the node package manager
5.	What version of node are you running on your machine?
1.	V19.7.0
6.	What version of npm are you running on your machine?
1.	9.5.0
7.	What command would you type to install a library/package called ‘jshint’?
1.	npm install -g jshint
8.	What is node used for?
1.	One of the biggest use cases is that it can be used to for server programming. Since it is single-threaded and event driven it only utilizes resources when there an event occurs.

1.	What are the 6 reasons for pair programming?
1.	Greater efficiency
2.	Engage collaboration
3.	Learning from fellow students
4.	Social skills
5.	Job interview readiness
6.	Work environment readiness
2.	In your experience, which of these reasons have you found most beneficial?
1.	Learning from fellow students – I have found this beneficial for the reason that I get to see how other people think and how they tackle a problem. In my experience I have not see how many people tackle a complicated problem and seeing this has been beneficial
3.	How does pair programming work?
1.	It works by allowing two people discuss and idea and implement a solution. It allows for open and honest communication that is more beneficial that working in a silo developing your own code.



1.	What does REST stand for?
1.	representational state transfer
2.	REST APIs are designed around a ____.
1.	Service being rendered via client server model.
3.	What is an identifier of a resource? Give an example.
1.	Unique identifyers for a resource can look like the following
1.	https://somewebsite.com/<api key>? City=<city>&state=<state>
4.	What are the most common HTTP verbs?
1.	GET
2.	POST
3.	PUT
4.	PATCH
5.	DELETE
5.	What should the URIs be based on?
1.	Uris should be comprised of nouns
6.	Give an example of a good URI.
1.	Good: /cars/types
2.	Bad: /delete-cars
7.	What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
1.	Being chatty is a bad thing because the API will either send to many requests or retrieve and send back too much data.
8.	What status code does a successful GET request return?
1.	200 - OK
9.	What status code does an unsuccessful GET request return?
1.	204 – NOT FOUND
10.	What status code does a successful POST request return?
1.	201 - CREATED
11.	What status code does a successful DELETE request return?
1.	204 – NO CONTENT




Professional pitch video NOTES

-	Who are you and what do you do ?
o	I am a software engineer
o	
-	Why do they care?
o	
-	What do you want ?
o	Why am I interviewing
My name is Juan I’ve been working as a Software Development Analyst in the Aerospace sector for the last 4 years.
Most recently I’ve worked on enterprise agreements where weve identified software used across the enterprise to be able to drive down cost of utilized software .
One cool thing about this that our team was able to save over 13 million dollars per year on
unused software for the systems engineering directorate
I’ve also assisted with the development of features with commercial of the shelf software by gathering requirements, generating use cases, shadowing the
development team and documenting the results of our implementation

Right now in my job search I am looking to find a position that will help me
expand on my software development skills I have learned at codefellows and in my current role. I want to make an impact on building scalable applications that

allow for the users to really utilize the data that exists within organizations


1.	What is functional programming?
1.	It is a programming approach for building the structure and elements of computer programs. 
2.	What is a pure function and how do we know if something is a pure function?
1.	A function that returns the same result given the same argument. For example, a function that appends a string to everything passed on to it. 
3.	What are the benefits of a pure function?
1.	They are easier to tests
2.	immutable
4.	What is immutability?
1.	The function is not able to change. The instance of that function will not be able to be changed and if different behaviors is needed a new instance would have to be instantiated. 
5.	What is Referential transparency?
1.	They are pure functions + immutable data, with these two the behavior of a function can be memorized. 

1.	What is a module?
1.	A module is a self-contained block of code that can be imported and used in another program. Sort of like packages in java. 
2.	What does the word ‘require’ do?
1.	It is used in Node to load and import external modules. 
3.	How do we bring another module into the file the we are working in?
1.	Use the require keyword with name and path
4.	What do we have to do to make a module available?
1.	Using either module.exports or export


Reading
Understanding the JavaScript Call Stack
1.	What is a ‘call’?
1.	This would be the call of a function
2.	How many ‘calls’ can happen at once?
1.	One call can happen at once in the cll stack
3.	What does LIFO mean?
1.	Last in First out
4.	Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
1.	 
5.	What causes a Stack Overflow?
1.	A function that calls itself over and over, a recursive function
JavaScript error messages
1.	What is a ‘reference error’?
1.	An error where you try to use a variable that has not yet been declared
2.	What is a ‘syntax error’?
1.	Something that cannot be parsed in terms of syntax
3.	What is a ‘range error’?
1.	This happens when you try to reach an index of an element or an array that is not there
4.	What is a ‘type error’?
1.	This happens when you try to access a variable with the wrong type. One example would be to use an array function on an integer variable
5.	What is a breakpoint?
1.	This is used when debugging code and adding a debugger statement in the code so that it stops its execution at that location
6.	What does the word ‘debugger’ do in your code?
1.	Breaks the code at a particular line. 

![image](https://user-images.githubusercontent.com/43771360/233610339-63bff740-a736-403c-9fa4-96423e641a49.png)

