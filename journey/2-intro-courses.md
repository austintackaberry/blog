So I decided that I am going to teach myself programming with the goal of switching careers into being a software engineer. In my first post I mentioned that I stumbled across the Google Guide to Technical Development. The first course recommendation was Udacity Introduction to CS, so that is where my journey began.

I should talk about my previous coding background: I took one semester course in visual basic in high school, and in my freshman engineering course there was a programming component. We touched on labview, matlab, C, and maybe a little Python. It was a crash course, but we did go far enough and quick enough to get into pointers in C.

I was excited, and I had a lot of energy. I hadn't done a ton of research on what it took to grow my competence enough to actually make the career switch, but I knew it would take a lot of effort and a long time. I devoted just about all of my free time to this course and knocked it out in 17 days. It's 100% in Python, and it's done using the built-in Udacity text editor. There are quick videos, quick quizzes, and some longer problem sets. The syntax, loops, and functions went fairly quickly since I had seen them all before albeit 6 years ago (wow can't believe it's been 6 years since I was a college freshman). Recursion was another story. Recursion is hard. It takes a while to wrap your head around the concept of a function calling itself. Understanding the difference between calling the function recursively setting that value equal to a variable and returning the function recursively was difficult to understand. By the end of the course, you have a web crawler that is just about equivalent to Altavista from the 1990s which is pretty cool, and it helps you to understand how recursion can be useful. You learn roughly how programming languages and the internet work. You learn Moore's Law which is the observation that computing power grows exponentially (this is pretty crazy coming from oil and gas where nothing grows exponentially).

As of right now in 2017, people are arguing over whether or not Moore's Law is dead, but in any case the fact that Moore's Law is/was in existence up to now corroborates with the premise that software engineering is booming. If computing power is growing exponentially, you can do more things without having major breakthroughs. For example, let's say you wanted to do some crazy AI web application 10 years ago, but found out that it took too long to run and because of that, the user experience suffered to the point that no one would use it. If computing power is continually increasing, your product will be useful at some point in the future without you needing to have any further breakthroughs in making your code more efficient.

After finishing Udacity CS101, I felt accomplished, but now I had to decide what to do next. The reddit.com/r/learnprogramming (I will refer to this as RLP from now on) subreddit wiki was very helpful in trying to add structure to learning programming which is inherently chaotic. At this point I wasn't sure what kind of software I wanted to focus on: android development, iOS, web, etc. I noticed that whenever someone asked about how to get started on RLP, everyone recommended Harvard CS50 on edX. They said it was very challenging and gave you a good solid core understanding of CS concepts. One person even went so far as to say that they learned more in CS50 than they did their first 2 years in their CS major. Though this may say more about their education than it does CS50, it was promising nonetheless.

I finished Udacity CS101 on June 15th, 2017 and began Harvard CS50 edX on June 16th, 2017. I pretty much put my head down and went all out until July 16th. You might be thinking, "I thought you said learning to code is chaotic. Your learning seems pretty structured and focused." My answer to you is ah just you wait. I will talk more about that in a bit, but for now let me share my thoughts about CS50.

### General Overview
By June 16th, I had completed  8 of 9 problem sets (psets). CS50 is fantastic. I read that it is the single most popular course at Harvard. People who aren't even CS majors sign up to take the course. On campus, they have tshirts, free food, a hackathon, etc. You don't get any of that on edX, but you do get the following: a great IDE developed by CS50 TAs, a community of support on reddit, stackoverflow, facebook, twitter, etc., debugging tool (debug50), and a tool to immediately check if your pset solution is correct (check50). There is even a little fun CS50 tv show with little 2 min episodes after each lecture. I could go on. You don't have to take notes on the lectures because there's a webpage that has all the notes. There are short videos done by TAs explaining some of the concepts in more detail. There are walkthroughs that help you set up the pset solutions.

### Scratch and C - pset0 to pset5
Pset0 is in Scratch, a visual programming language that warms you up to programming. The next 5 psets are in C which is the exact opposite of Scratch. It is the lowest level programming language. You have to do manual memory management in C. A lot of things that seem like they should be easy (especially after having taken Udacity CS101 in Python), are not. You want to add an element to an array? Oh that should be easy, just append.something should work right? Nope. You have to make a new array that includes that extra element unless you had previously allocated extra memory for that original array. **The concepts get pretty difficult especially on the 4th and 5th C psets. Pointers are difficult. Trees and Tries are difficult.** The most challenging and most rewarding pset for me was the 5th C pset where you make a spell checker. Sounds kind of easy right? You have some sort of dictionary, and if your word is in the dictionary, then it's spelled correctly...But this is C we're talking about. You have to make the dictionary, starting with a text file of words...a lot of words. You can't just iterate through the file, that will take too long. You want your program to run quickly. Tries or hashtables allow you to find your word in your dictionary in the amount of time it takes to iterate over each character in your word, not the number of words in your dictionary. Pretty neat, right? Right. But it is mind-bending, keyboard-breaking, hole-in-wall-making-ly difficult and time-consuming.

### Python - pset6
The next language you learn in CS50 is Python. And to show you how much easier it is to learn and use, they have you redo your first 3 psets in Python. When you first look at it, you think it is going to take forever, but then it doesn't take that long and you hate C and love Python. You think, great, C sucked but now I get to learn Python, this is going to be easy! Then boom.

### Python and others - pset7 and pset8
*SQL, HTML, Javascript.*

*CSS, JQuery, JSON.*

*Bootstrap, Django, Flask.*

What are all of these? Which are languages? Which are frameworks? What's a framework? Ahhh!
Luckily, you don't have to build websites from scratch using everything I listed above. The next couple psets involve completing websites that are partially built; however, looking at code using languages and frameworks that you just briefly learned is very daunting. It's like starting an essay in high school, or a project in college. Half the battle is just starting. Once you start and understand one aspect of the code, you realize it's doable, get on a role and boom 5 hours go by and you're learning and caught up in the pset.
**Pset7 is a stock trading app.** Users can register, log in, log out, buy stock, sell stock, look up stock. Once you finish, you feel very accomplished. I (kinda) made that! Before CS50, a stock trading website seemed like magic. Now it seems difficult, and though I'm sure there's a lot more to it when there are real users, you at least now know approximately what is involved and how it works.
**Pset8 is called "Mashup" and it is a Google Maps map where you can search for a location and you will see the top 10 news stories at that location.** There's a lot of javascript which is difficult because it is asynchronous and functions are first class citizens. Asynchronous code just means that code can be running in one spot while other code is running elsewhere. I'm not sure I'm qualified to explain functional programming much, but I'll give it a shot. The programming you have done up until javascript has been object oriented which means you focus on objects, variables having values and the values changing. You work with functions but only, so that you end up with values that can be stored in a variable. Functional programming focuses on functions rather than objects. When this button is clicked, DO this. A lot of functions in javascript take functions as inputs or return functions as outputs. There are more qualified people that can explain functional programming, but this is a perspective of someone who is in the process of learning it. My main point here is that it makes you think differently, forces you to break your tendency to think sequentially. Similarly to pset7, once you have completed pset8, you feel very accomplished because you (kinda) built a useful, complex web app!
This is where my CS50 journey pauses. I am currently doing freecodecamp and Colt Steele's Web Developer Bootcamp. When I am a little further along, I will come
back and do the final project.

### Review
Now for my review and whether or not CS50 is for you. I stated previously that **I think CS50 is fantastic.** It helps you understand a lot of the core CS concepts, and then gives you the confidence to build cool projects. It is very difficult and fast-paced, but if you stick with it, I think it will pay off. When I try to explain it to bootcamp students it is hard to articulate why it's important to start in C and learn core CS concepts. Maybe I just want it to be valuable because I took it and liked it. The real reason is probably because neither of us are far enough along to really know what is the best way.
Web development bootcamp students are getting a crash course on building projects and making websites. They are getting prepared to immediately add value to a company. The other school of thought is similar to the traditional education system. You learn the core concepts, and you will be able to pick up everything else during internships or personal projects. **As a self-taught learner you have the opportunity to control your own education.** I don't know for sure, but from what I've read it seems like it is beneficial to know the core concepts for interviews and also on the job and for your long-term career.

If we assume that you need to understand the core concepts, then intro courses need to have a balance between core concepts and the WOW factor. If we were all robots with no emotions, then I am sure that all intro courses would be core concepts with no projects. Given that we are humans and not robots, if intro courses are all core concepts and no projects then people would shy away because they think it's dry and boring. In general I am the type of person that prefers the core concepts. I don't need to start my programming journey by doing a tutorial to build a fancy web app. I would prefer to get a foundation, knowing that though it might be boring or stale, I am willing to put in the time now, so that learning other concepts later will be easier and come quicker. Having said all that, I was pretty pumped to finish the stock trading and maps web applications. Also, I haven't touched on this yet, but David Malan is an amazing speaker, one of the most engaging speakers I have ever listened to. Though the lectures can be 2 hours and they can be talking about pointers and tries in C, the time flies by and I am engaged the whole time.

If all you want to do is web development, nothing more and nothing less, then CS50 probably doesn't make sense for you. I am sure it would be helpful, but in terms of return on investment, I am sure you would get more value in starting at FCC or Colt Steele Web Developer's Bootcamp. Having said that, if the kind of jobs you are looking for have interviews that involve HackerRank or whiteboarding, then that's a different story. If you want to learn the fundamentals, and you are determined and motivated to get it done no matter how long it takes, then CS50 is for you. Make persistence your friend, and CS50 will be your friend.