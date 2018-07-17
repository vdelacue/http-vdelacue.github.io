---
layout: post
title: BlocJams
phrase: Turn the music up!
feature-img: "img/bloc-jams-header.png"
thumbnail-path: "img/bloc_jams_logo.png"
short-description: BlocJams Digital Music Player

---
### **Summary**
Bloc Jams is a free digital music player site that allows the user to listen to the music of their choice. The site features unlimited streaming, ad-free, with the added feature of mobile enabled platforms. Users can listen to their music on the go or at home without limit or ad distractions.


### **Explanation**
Bloc Jams was my first major project during my career at Bloc.io. The site consists of a Landing (home) Page that provides information regarding the attractive features of the site: including being able to choose your own music, unlimited streaming, ad-free listening, and mobile enabled platforms to listen to music on the go. From the home page the user is able to navigate to the Library Page (‘collections’). This page includes lists of albums that the user is free to choose. Once the user selects an album they are directed to an Album Page that includes a fully functional and interactive player bar with volume controls. Here the user can see the lists of songs within an album and can play, pause and skip songs at their discretion as well as adjust volume.  

The Bloc Jams project was split into two phases. Each phase was intended to develop a different group of skills needed in fronted-end web development. 

#### *Phase one* of the application used:
>* **HTML** to provide the basic structure and backbone of the application layout.  
>* **CSS** to style and for flexible layouts, flexible images and cascading style sheet media queries that create the desired views.
>* **Plain/Vanilla Javascript** to create interactivity..

From the start of *Phase One* Vanilla Javascript was utilized for animation and DOM Scripting for events and functionality. After the basic structure was setup some distinctive and attractive features were added with Vanilla Javascript. These features included loops that were used to populate albums in Collections and song rows in Album. In the Album page the states of the play/pause button were set and reset according to user interactivity. Click behavior and Event Listeners like MouseOver and MouseLeave were setup throughout the site to maximize user interactivity. Finally a fully functional player bar is found at the bottom of the Album page with icons and an adjustable seek bar and volume bar.

The site at this point was already functional and could be deemed finished, however, to delve further into developing the fundamental tools of front-end web development I was tasked with using 'JQuery' to refactor a large portion of the 'Vanilla Javascript'. Doing so consolidated the lengthy and complex Plain Javascript code that was needed to create optimal responsiveness. Now phase one was complete and with it a strong foundation in frontend web development. 

But wait there is more ...

*Phase two* consisted of rebuilding this entire application from the ground up using React, a framework that requires a solid foundation in frontend web development. Thus *phase two* would not have had the same impact it did without *phase one*. I needed to build the application in basic HTML, CSS, and Javascript to appreciate the better suited framework for single page applications, React. During phase two a lot of creative liberties were exercised and executed.

#### *Phase two* of the application used:
>* **React** as the more effecient framework for single-page application.
>* **JSX** to produce React "elements" using a declarative XML like syntax that works with Javascript.
>* **bootstrap** and **CSS** for responsiveness and to style the page views.
>* **babel** to compile Javascript.
>* **npm** to manage and install various Javascript Node.js packages.

In *phase two* I chose to style the pages completely differently using CSS and bootstrap. Below you can see the phase one home page vs phase two home page. Although both have accomplish the same end result phase two is written with a lot less code and took a tenth of the time to create. However, because of phase one I know what phase two is doing behind the scenes and what the browser is reading from the code. 



### **Problem**
This project fell victim to a common issue in front-end web development, lengthy and complex code. This also brought up the issue "am I Using the best suited framework for single page application?". 


### **Solution**
Refactoring was needed in both phase one and phase two because of a common issue in front-end web development, lengthy and complex code. Vanilla Javascript was refactored with JQuery in Phase One and the entire application from phase one was refactored in phase two using React.

In order to understand the functionality and what JQuery accomplishes, I needed to first write in Vanilla Javascript. JQuery consolidates lengthy and complex code to create optimal user interaction. Writing Bloc Jams in Vanilla Javascript and then refactoring it into JQuery lead me to appreciate and understand the use of both JQuery and Vanilla Javascript. Many programmers are more commonly use JQuery with Javascript instead of taking the time to write the entire code in Vanilla Javascript. 

Similarly, phase one was instrumental in being able to understand and execute phase two. Phase two involved refactoring all the code in a new project using React. It is important to see that phase one forced you to write the entire site using the basic fundamentals of front-end web development, HTML CSS and vanilla javascript. Many of the frameworks, libraries and packages used today bypass the need to write such lengthy code and make frontend web development much easier. However it is important to understand what all these frameworks libraries and packages are accomplishing behind the scenes. This knowledge is essential to really understand programming and what is happening when a user enters and interacts with a site or application. Phase one although not commonly practiced taught fundamentals that paved the way for phase two.

 

### **Results**
By using React to rebuild Bloc Jams I was able to leverage the power of a full programming language Javascript to build view this includes temporary variables, flow controls, and directly rendering Javascript values in scope.

### **Conclusion**
There are many programmers out in the world that blindly use libraries, frameworks and packages without knowing what they are executing or doing behind the scenes. It is very similar to the way people use the english language and use acronyms without knowing their meaning or what they stand for. Of course you can properly use many words without knowing their origin or true meaning. For example, many people use the word zip code every day not knowing that it stands for “Zoning Improvement Plan” a system of postal codes used by the United States Postal Service (USPS) since 1963. Laser stands for “Light Amplification by Stimulated Emission of Radiation”, Scuba stands for “Self-Contained Underwater Breathing Apparatus, Taser stands for “Thomas A Swift Electric Rifle, CARE Package stands for “Cooperative for Assistance and Relief Everywhere” Packages, and so on…

The point is, all these acronyms are used by people regularly in communication, without these people being aware of the meaning behind these words. A similar situation occurs in programming. Many shortcuts, abbreviations, packages, libraries and frameworks have been created and adopted by programmers. These programmers have not bothered to learn what these consolidated lines of code actually mean. Luckily, thanks to this project I do not fall victim to this “TechnoTardic” Naiveté. Thus with phase one and two concluded, I was given a solid foundation for frontend web development.
