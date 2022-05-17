# 100 Days Of Code Log

<!-- blank version

## Day X: XXX XX XXX 2022

**Today’s progress:** XXX

**Thoughts:** XXX

**Links:** [xx]() | [xx]()
-->

## Day 22: Tuesday 17 May 2022

**Today’s progress:** Today we learned to use Express + node.js + Nodemon to create a local server and send some data to it! Also learned the difference between the commonjs require and module.exports and the ES6 import/export syntax. I learned how res.send(x) does the same as res.json(x) when x is a js object... at least I think that's what it does! Also about the app.get("/", function(req, res) {res.send("message")}) method to post "message" to the server. 

**Thoughts:** Very confusing start but by the afternoon I felt I really had the measure of it!

**Links:** [import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import) | [export](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/export) | [module.exports and require](https://nodejs.org/en/knowledge/getting-started/what-is-require/)

## Day 21: Monday 16 May 2022

**Today’s progress:** This morning I began the effort of coding the website I wireframed yesterday. Didn't get too far, but it'll be an ongoing project. In school we installed node.js (for me, via the nodist version manager) and learned how to use js in the console - very cool, I can see why that's so revolutionary. Met with my week 4 partner Owen B, we both enjoy video games so that was nice. I struggled with getting nvm to work properly, but eventually figured out a solution (copied below for posterity). No idea why it was broken but at least I fixed it...

> solution for `ERR! cb.apply is not a function`
> (at least, this worked for me, Windows 10)
> Basically, it seems like something in the graceful-fs module that comes preinstalled with npm was screwy. `npm -v` ran fine, and node runs my code fine, but I wasn’t able to install any new modules from npm (i.e. `npm i chalk` was not working for me)
> So, I removed it, and replaced it with the current version directly from the author’s github page
> 1. Delete the module ‘graceful-fs’ from your Nodist install location, i.e. by deleting the folder (actually you may want to first copy/paste it somewhere else just in case). For me it was located at C:\Program Files (x86)\Nodist\npmv\6.9.0\node_modules\graceful-fs
> 2. Download the repo 'graceful-fs' as a zip file from https://github.com/isaacs/node-graceful-fs
> 3. Extract the zip file into the node_modules folder as a folder with the name `graceful-fs` (i.e. replace with what you deleted/removed in step 1)
> 4. Try `npm i chalk` again — at least for me, it's magically now working, with no error message!

**Thoughts:** Looking forward to the week!

**Links:** [Chalk](https://www.npmjs.com/package/chalk) | [Nodist](https://github.com/nullivex/nodist) | [useful micro npm packages](https://github.com/parro-it/awesome-micro-npm-packages)

## Day 20: Sunday 15 May 2022

**Today’s progress:** Weekend recap tasks today! Starting with a user persona, I made low- and high-fidelty wireframes to design my (eventual) website / portfolio. I decided on a black & white 'almost-brutalist' design with pop art accents.

**Thoughts:** I am quickly realising that wireframes are not a waste of time nor a hassle - they actually do make it much easier to design. I'm not exactly sure why i didn't believe it at first!

**Links:** [Colour palette](https://coolors.co/100e0f-f7d221-efe5e0-db1083-15a7e0) | [Mondrian generator](https://codepen.io/Sanja_kaz/pen/wvyKKqj)

## Saturday 14 May 2022

**No coding:** Had a relaxing day off coding. I played (a lot of) Hearthstone, some Tiny Tina's Wonderlands and did some chores around the house.

## Day 19: Friday 13 May 2022

**Today’s progress:** Hackathon Friday! Putting into practice all we have done this week on idea generation, listening and collaborating, user personas/stories, and low- and high-fidelty wireframes. Zainab and I created a pretty basic website for a language-learning app, but we got an incredible amount of work done in a very short space of time. I also had a good bit of fun playing with CSS positioning of some circles haha.

**Thoughts:** My coding partner and I worked really well together on Friday, encouraging each other, writing – and sticking to – a plan, collaborating to make our ideas even better, and splitting up the work into manageable chunks. 

<!-- **Links:** [xx]() | [xx]() -->

## Day 18: Thursday 12 May 2022

**Today’s progress:** Mindset Thursdays: Idea development and ownership, and good/bad listening. Some good advice from Joe: "Even if it was 'your' idea to begin with, by the end of the project it your team's idea." Positional vs generative approaches to having ideas. Also 'deep listening', plus four different types of bad listeners: Lost, Interrupting, Shrewd and Dramatic. We also had a CSS postioning lesson from Helena on flexbox. Followed by a guest speaker, Olivia Winteringham, past bootcamper now working in UI for Santander. A useful piece of advice from her: "SOC prepares you for 'learning at pace'" – which is a transferrable skill that employers value.

In the afternoon we looked at user personas and user stories in a group of four, and had a presentation at at the end. A useful thing I learned was that UX/UI doesn't necessarily need demographic info like age, ethnicity, marital status, but it's more important to look at behaviours, motivations and attitudes. E.g. how comfortable they are with technology, what they use their devices for, and their frustrations/pain points. 

**Thoughts:** XXX

**Links:** [Hubspot user persona generator](https://www.hubspot.com/make-my-persona) | [Google Jamboard](https://jamboard.google.com/)

## Day 17: Wednesday 11 May 2022

**Today’s progress:** In the future if I'm looking for my notes on today (Week 3, Day 3 of SOC), then they are in the back section of my first notebook because I had the wrong tab open :) 
Today we had a guest speaker, Luke Edwards from Immediate Media (a magazine/media publishing company), who talked about sort of 'the day in the life of a UI designer', including a bit of detail on sprints, dev days, retros, and working on tickets. One great piece of advice he gave was "Planning can be boring but it's really important". Which resonanted, haha. But the BEST advice was **"Read the ticket. Then re-read the ticket"**. I'll have to keep that in mind. 

We are still looking at UX/UI this week, and we had an overview of visual design pricniples such as heirarchy, balance and colour, an overview of what a UI designer actually does, and Lighthouse, an accessbiity tool built into Chrome. In the PM, my partner Zainab and I worked together on wireframing and eventually creating a high-fidelity design using Miro and Figma. Right before the end of the day, we also looked at tips for CSS organisation (useful!), and the CSS cascade and specificity. 

**Thoughts:** Lots of non-SOC things to do today, and I'm running out of time to do them. Coursework remains great.

**Links:** [School of Math in Miro](https://miro.com/app/board/uXjVO1riJLE=/) | [School of Math in Figma](https://www.figma.com/file/t87ZxSyRvwQy6y7DdvdBE5/WireFrame---School-Of-Math?node-id=0%3A1)

## Day 16: Tuesday 10 May 2022

**Today’s progress:** Still in UX/UI week, and in the AM we had a talk from Javaid Karim and Alex Fairholm of Nester investments. They spoke about the company and the need to create a user interface that also captured complex data to fulfil legislative requirements about financial products. One great piece of advice from Alex was around creating portfolios that not just show your work, but that show the challenges you overcame and how you solved problems. Also today we had a quick overview on user-centred design, and my partner Zainab and I worked on a simple idea for an application process for a maths 'bootcamp' for gifted children. We mapped out a user flow for the application process with a flowchart. Oh, and we created a simple 'dark mode' for a website that applied itself on a button click!

In the evening, I attended a virtual talk at ConFig (Figma conference) on Designing for Neurodiversity, presented by Treyce Meredith of Dropbox. I found it super fascinating and really appreciated the lessons he offered on the difference between Access and Success, and these three important principles: Be Abundant, Be Forgiving, Be Nurturing.

**Thoughts:** Quite tired today, struggling a little with the work and keeping up with life admin.

## Day 15: Monday 9 May 2022

**Today’s progress:** Today at SOC we looked  at Agile and UX/UI concepts, with a talk from Pavaan Buddhdev about the 'magic' of UX/UI: storytelling, attention/misdirection and wonder. Did 'can't unsee' game (silver!)

**Thoughts:** Not actually much coding today, but learning about valuable concepts behind being a software developer :)

**Links:** [Pavaan](https://twitter.com/p44v9n) | [Can't Unsee](https://cantunsee.space/)

## Sunday 8 May 2022
**No coding:** Brunch at Brickwood w Marley, BBQ with K&J, L&R and Roxanne. Pub quiz in the PM for George's birthday! Far too busy socialising and getting sunshine :sun: to do any code today! 

## Day 14: Saturday 7 May 2022

**Today’s progress:** Today I worked on the SOC w2 recap tasks. I made an interactive shopping list with a Sort button that sorts by the priority of the items on your shopping list. I did spend some time making it look pretty! The recap tasks were fairly easy-ish, i.e. I didn't find them overly challenging, although I did hvae to google a few things, especially manipulating strings. I enjoyed making a random cat picture app :) 

**Thoughts:** XXX

**Links:** [xx]() | [xx]()

## Day 13: Friday 5 May 2022

**Today’s progress:** Hackathon day, made a basic Pokedex with the PokeAPI

**Thoughts:** Not as much progress as I would have liked, but still a great outcome and lots of practice with fetching data from APIs.

**Links:** [xx]() | [xx]()

## Day 12: Thursday 4 May 2022

**Today’s progress:** To Fill out

**Thoughts:** XXX

**Links:** [xx]() | [xx]()

## Day 11: Wednesday 3 May 2022

**Today’s progress:** Asynchronous code in the AM to fetching from APIs in the PM... I mean, look at us go... Managed to complete the bonus tasks today on the workshop, and pretty happy with that. Learnt of the importance of `await` : ALWAYS AWAIT A PROMISE. We used the [kanye.rest](https://kanye.rest) API to pull some Kanye quotes and put them in a list, while also avoiding duplicates. I felt like the problem wasn't too difficult to solve, and this time I remembered to check if JS already had a method to do the thing I wanted to do (YES - `includes()` exists). 

**Thoughts:** Pretty happy with today's stuff, all brand new and I think I pretty much understand it. 

**Links:** [fetch() @MDN ](https://developer.mozilla.org/en-US/docs/Web/API/fetch) | [includes() @MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes) | [kanye.rest](https://kanye.rest)

## Day 10: Tuesday 2 May 2022

**Today’s progress:** Start of Week 2 of SOC! In the morning, we had a chat from some previous bootcampers who now work for Wise. Some great advice from them on allowing yourself to rely on your mentor; practice working well with others in a team; keep a diary/journal (or #100DaysOfCode log!) so you can look back on your progress; measure your performance by how much your are _improving_; a key transferable skill you are gaining from SOC is being able to learn; ask more questions; put the hackathon projects on your github as a mini portfolio! In class, we launched right into DOM manipulation and event listeners. From learning about the DOM before lunch to adding event listeners for clicks, keyups and changes in the afternoon, a fairly huge leap!

**Thoughts:** I kept up well with class today, but I don't feel like I'm being challenged by the content, as I'm helping my partner this week keep up to speed. I would like more opportunities to get creative and test ideas and look stuff up, but I'm trying to embrace the opportunity to consolidate what I already know by teaching someone else.

**Links:** [addEventListener on MDN](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener) | [Wise.](https://withwise.com/) _not transferwise lol_

## Day 9: Monday 2 May 2022

**Today’s progress:** Another 7 kyu kata on Codewars today. Squared individual digits in a number. Not quite an hour's work but it was the long weekend :P 

**Thoughts:** Much better at breaking down the problems into smaller things

**Links:** [Square Every Digit](https://www.codewars.com/kata/546e2562b03326a88e000020)

## Day 8: Sunday 1 May 2022

**Today’s progress:** Some more Codewars today. Did a few of the easier katas at 8 kyu. The one I did yesterday was 6 kyu, so these were a comparable breeze. I'm using the experience of having small, simple challenges to ensure that I'm planning for each stage. I still need to find out more about the inbuilt functions for manipulating arrays and strings. For example, I built some lovely code that looped over an array and concatted each element into a new string – I could have just used `join(" ")` ... Well, practice makes perfect.

**Thoughts:** I am clearly still at the unknown unknowns stage of Javascript. Don't even know what to look up to help me do things! Hopefully that will come with experience.

**Links:** [Codewars – Sentence Smash](https://www.codewars.com/kata/53dc23c68a0c93699800041d)

## Day 7: Saturday 30 April 2022

**Today’s progress:** Started out with Codewars today. Biggest takeaway - Javascript uses `**` for exponentiation, not `^` ...  _\*\*cries in maths assumptions\*\*_

**Thoughts:** You know what they say about assumptions...

**Links:** [Codewars – Narcissistic numbers](https://www.codewars.com/kata/5287e858c6b5a9678200083c)

## Day 6: Friday 29 April 2022

**Today’s progress:** Day 5 and first hackathon with SOC. Today, tasked with creating a rock scissors paper game in the browser. There was a working product by the end, although some bits of the code were preeeeety hacky - way too much repetition instead of making neat functions, for example. I used a design generator called Neumorphism to create a sick background for our game. I also met with my mentor, Mark, who had some great advice about not getting too far ahead of myself with specialising, and just focus on learning to be a programmer. The rest will come.

**Thoughts:** Need to work on the 'making a plan' aspect of programming, so that my code is neater, scopes are clearly defined (not just making everything global and being done with it...). It's great to have a mentor, I already feel like he's got my back. 

**Links:** [Rock, Paper, Scissors](https://bookish-fiesta-9c352109.pages.github.io/) | [Neumorphism](https://neumorphism.io/#0dd9cb)

## Day 5: Thursday 28 April 2022

**Today’s progress:** Day 4 of School of Code! Today, some more javascript, understanding objects {} and arrays []. Some things are coming back to me, like zero-indexed arrays and how to manipulate elements of an array. Also learnt some new functions, like `length`, `map` and `Math.random`. Tried again to understand CSS grids, failed. More practice needed.

**Thoughts:** Bit tired again today, but excited to be doing 'real' things with JS!

**Links:** [Arrays Workshop](https://github.com/SchoolOfCode/w1d4_js-arrays-workshop-hannah-brycen)

## Day 4: Wednesday 27 April 2022

**Today’s progress:** Day 3 of School of Code! Today we got stuck into our first touch of Javascript. I had _maybe_ seen a line or two of Javascript before today (and, fortunately, did some C back in uni), but I was coming into this pretty cold. Paired again with my code buddy Brycen, I really surprised myself by getting a lot further with our github classroom tasks than I expected! We created a webpage that returns a 'secret' after you click a button. Brycen worked on a _Super Duper_ secret button using CSS animations, while I styled the page in CSS.

**Thoughts:** More chaos! Felt a bit tired this morning when waking up, really groggy, not sure why

**Links:** [Super Secret Info Page](https://vigilant-goggles-6823b854.pages.github.io/)

## Day 3: Tuesday 26 April 2022

**Today’s progress:** Second day of School of Code bootcamp! Today we covered some vs code basics, and some coding concepts like computational thinking, and breaking down the problem. We 'found patterns' by drawing boxes in a sort of wireframing-ish exercise on an existing webpage. Brycen and I then worked on the 'CSS Koala' challenge, which was to recreate a pure-css koala. We nailed it! I learnt slightly more about css positioning, although tbh I'm not really sure I fully get it yet. In the aftenoon, after some git basics and a lovely 30min walk, we went back to CSS Koala and Brycen and I decided to animate the shit out of it. The trick was to use a `>` in our selectors for the animation: `main > * { blah }`. 

**Thoughts:** Making our weird little psychedelic css koala was a joy. The walk was really nice too and I feel a little more refreshed than I was at this time yesterday.

**Links:** [Github Classroom – CSS Koala](https://github.com/SchoolOfCode/w1d2_create-a-koala-workshop-hannah-brycen) | [Twitter link to gif](https://twitter.com/hannahdoesacode/status/1518990716332040192?s=20&t=U2iNkgMmKPKPnxB4a8sp5Q)

## Day 2: Monday 25 April 2022

**Today’s Progress:** First day of School of Code bootcamp! Today I learned about some advanced CSS selectors, and about working with CSS on a grid

**Thoughts:** Definitely haven't committed these to memory, but I guess don't need to. Just knowing they exist and roughly how to use them will make it possible to use them down the line. 

**Links:** [CSS Diner](https://flukeout.github.io) | [Grid Garden](https://www.cssgridgarden.com)

## Day 1: Sunday 24 April 2022

**Today’s Progress**: CSS animations with FreeCampCode for the Responsive Web Design course – applied visual design. Learnt @keyframes, and another animation-related CSS stuff

**Thoughts:** Very easy, made me feel smart :joy:

**Link to work:** [FreeCodeCamp - Applied Visual Design](https://www.freecodecamp.org/learn/responsive-web-design/#applied-visual-design)