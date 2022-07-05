# 100 Days Of Code Log

<!-- blank version

## Day X: XXX XX XXX 2022

**Today’s progress:** XXX

**Thoughts:** XXX

**Links:** [xx]() | [xx]()

-->

## Day 61: Tuesday 5 July 2022

**Today’s progress:** Today we again deployed a front-end to Netlify, but also added in a back-end that's hosted on Heroku. It was a simple shopping list app, and we were given much free reign to basically test out anything we wanted to practice.

We managed to get the deployments working fairly easily, then created a delete route on the back end and a delete button on the front that talked to each other. Pro tip: re-deploy or reset the app after changing environment variables!!

In the afternoon we began on adding user login functionality with the aim of making individual shopping lists for a logged-in user. We managed to capture the userID and make it available to do fetch requests with it, but didn't quite finish it off. Hopefully we will be able to continue on this tomorrow and get it working!

**Thoughts:** It's very much coming together, today was another very satisfying day.

**Links:** [Back](https://w11-shoppinglist.herokuapp.com/items) | [Front](https://courageous-kashata-489ed5.netlify.app/) | [Free for Devs](https://free-for.dev/#/)

## Day 60: Monday 4 July 2022

**Today’s progress:** Week 11 of SOC and paired with Noah this week :) Today we did deployment for front-end apps using Netlify. Started by reading the docs on Netlify and understanding what it's supposed to do, including topics like forms, environment variables, serverless functions and Netlify identify. I also first heard the term 'Jamstack', which seems to be basically everything we've been learning so far. Spun up a super basic React app with CRA, deployed to Netlify, and then added a form that automatically sends the data to the Netlify dashboard.

**Thoughts:** Extremely satisfying day!

**Links:** [Implement Netlify Forms in React App - The CORRECT Way](https://www.youtube.com/watch?v=vCaSywNc9wQ) | [Netlify docs](https://docs.netlify.com/) | [Frabjous Kashata](https://frabjous-kashata-3d530f.netlify.app/)

## Day 59: Sunday 3 July 2022

**Today’s progress:** Catching up on Week 10 as I missed most of last week due to covid :( Thursday in class was an intro to Auth0 and a workshop. Today I've been watching a bunch of introductory youtube videos on authentication and authorization, in preparation for having a crack at the workshop. Ok so I got part 1 of the workshop working, enabling a user to log in and out and displaying the user's metadata so that was something.

**Thoughts:** Difficult to catch up when the workshop's instructions were so vague and I don't know what I missed in class.

**Links:**

Auth0

-   [Authentication](https://www.youtube.com/watch?v=tZPENgB_Rd0)
-   [Authorisation](https://www.youtube.com/watch?v=gnZo3BJgjpI)
-   [Auth vs explained](https://www.youtube.com/watch?v=2iTTBJd46ow)
-   [Authentication vs authorisation](https://www.youtube.com/watch?v=85BBfKo6bdo)

Other

-   **Hi! My name is...**, talk by James Bennet (27m) on the problems with usernames as unique identifiers, potential security risks, and some nerdy Unicode stuff https://www.youtube.com/watch?v=NIebelIpdYk
-   **User names to reserve**: more on malicious/security-risk usernames, ~10min read https://ldpreload.com/blog/names-to-reserve
-   **The Tripartite Identity Pattern**: better ways of using usernames, logins and public IDs, ~8min read http://habitatchronicles.com/2008/10/the-tripartite-identity-pattern/

### Day XX Saturday 2 July 2022

COVID

### Day XX Friday 1 July 2022

COVID

### Day XX Thursday 30 June 2022

COVID

### Day XX Wednesday 29 June 2022

COVID

## Day 58: Tuesday 28 June 2022

**Today’s progress:** Codewars: baby shark lyrics generator. How to write documentation. Then writing documentation for our project. Idman and I also manged to get a new test up and running, but not before breaking some other tests lol. Here is some useful code that should help avoid the ECONNREFUSED error:

```
if (process.env.NODE_ENV != "test") {
	app.listen(PORT, () => {
		console.log(`listening on port ${PORT}`);
	});
}
```

**Thoughts:** XXX

**Links:** [Codewars - Baby shark lyrics](https://www.codewars.com/kata/5d076515e102162ac0dc514e/train/javascript) | [readme.so](https://readme.so/editor)

## Day 57: Monday 27 June 2022

**Today’s progress:** Week 10! This morning we had a team retro, which went pretty damn fantastically. We really worked great together as a team, and we had a lot of positive feedback for each other. Apparently this week we are doing deployment as well, which will be cool. IN the afternoon we practiced code reviews by looking at the code for Team Bruh's project, Wack.

**Thoughts:** XXX

**Links:** [Project retro on Trello](https://trello.com/b/uVUIHpNi/week-9-project-retrospectives) | [Atlassian Play Book - Retros](https://www.atlassian.com/team-playbook/plays/retrospective) | [Code reviews video (37mins)](https://www.youtube.com/watch?v=PJjmw9TRB7s) | [Team Bruh: Wack](https://sage-unicorn-717860.netlify.app/)

## Day XX: Sunday 26 June 2022

No coding today

## Day 56: Saturday 25 June 2022

**Today’s progress:** Today I started on my journey to learn Ruby, via Codecademy. I tried to teach myself about a decade ago (_ahhhh!_), so I don't really remember anything. It's fairly straightforward so far, it'll just be getting the hang of syntax and a few other differences between it and JS (e.g. immutable methods).

**Thoughts:** `elsif` is very annoying :D

**Links:** [Codecademy - Learn Ruby](https://www.codecademy.com/courses/learn-ruby)

## Day 55: Friday 24 June 2022

**Today’s progress:** Presentation day! We finished most things on the app on Thursday afternoon, although Ben and Tom worked on getting the Upload form to not just take in new data but also display it on the app immediately. Which fortunately went really well, no dramas! We spent the morning working on the presentation, then after lunch practiced it a few times before presenting around 3.30pm. It was quite nerve-wracking going last, as we (OK, me) had a lot of downtime before the judges arrived in which to get nervous. But, the presentation went well. Tom's mentor's suggestion of appointing someone as the facilitator of questions was an amazing idea, and I think I handled the role pretty well, giving the others time to think before either answering myself or handing over to someone to answer it.

**Thoughts:** Our team worked amazingly together. Here was my short final reflection on the week

> I’d like to echo how well we worked together – we came together to make decisions so that nothing was really decided in a vacuum. For me, even though I spent time on learning new things and going outside my comfort zone, in some ways I stuck to my strengths on this project, and in future I think I should try to work on aspects I am less confident with.

## Day 54: Thursday 23 June 2022

**Today’s progress:** Today I worked on some styling for our app, including some cool bubble animations for the Go buttons, and started/finished the slide-out menu for the upload form. Troubleshot some CSS problems.

## Day 53: Wednesday 22 June 2022

**Today’s progress:** More project week :) I continued to work on the front end today, finishing the folio display list. We also got the front and back ends linked up and successfully talking to each other. Then Ben and I worked on adding search and filter functionality, as well as a reset button that clears the search/filtering. Tom and Idman worked on the upload form for posting new folios to the db and displaying them.

## Day 52: Tuesday 21 June 2022

**Today’s progress:** Second day of project week! Idman and I worked on the front end today and have a skeleton of an app sketched out, with which components will be used and where. Ben and Tom have been working on the back-end database, setting up the routes and CRUD ops. I created cards for the folios and the beginnings of a display grid that takes in data from the backend to display the individual folios. I also created some logos and set up brand colours.

## Day 51: Monday 20 June 2022

**Today’s progress:** Project week! Idman, Ben, Tom and I used the whole creation process we've been through in the course – Disney ideation, jamboards, Miro wireframes and planning. Tom and I split off to create a questionnaire for other bootcampers that would help inform the requirements of our project.

**Thoughts:** XXX

**Links:** [xx]() | [xx]()

## Day 50: Sunday 19 June 2022

**Today’s progress:** Worked on the week 8 recap task ("practice anything you think you need a refresher on") by attempting to use another API to make a website, similar to the hackathon project that Lorentz and I had done. Unfortunately it seems I used an API that I couldn't access – or at least, couldn't figure out how to access! (I have since realised that the API link no longer resolves, so I guess it was never being maintained - so probably not my fault!!) Watched some vidoes and practiced some troubleshooting, plus now I'm really quick at spinning up `create-react-app` lol.

**Links:** [National Museum of Australia - Convict Love Tokens](http://love-tokens.nma.gov.au/api)

## Day XX: Saturday 18 June 2022

Day off coding

## Day 49: Friday 17 June 2022

**Today’s progress:** _(filled out later)_ Hackathon Friday! Lorentz and I used the Cocktail API to make a React app that loaded a Margarita cocktail on page load and had a search function that displayed all cocktails with that name in. We used the list mapping method shown earlier in the week. And I ofc made it look pretty :) Great week.

## Day 48: Thursday 16 June 2022

**Today’s progress:** _(filled out later)_ **_WATCH VIDEOS_** (Notes in wrong place of notebook 1) Git branching reminder and practice. Guest talk: Talis, Nadeem and a cospeaker. On HTML verbs and RESTful APIs. I found it very difficult to concentrate. Something about mapping over arrays in the last part of the day, maybe?

## Day 47: Wednesday 15 June 2022

**Today’s progress:** _(filled out later)_ **_WATCH VIDEOS_** A talk from Mark and Haley at Experian. I asked a question about their gender diversity at senior leadership levels and their diversity and inclusion policies. This set off a whole bloody stressful thing, finding out that some people in the course do not share similar values (or, at least, have chosen ignorance). Afternoon was React testing, which I probably need to go over sometime...My tests were inexplicably failing to run!

## Day 46: Tuesday 14 June 2022

**Today’s progress:** _(filled out later)_ Some computer sci theory in the morning, learning about the finite state machine, which naturally led into an intro to `useReducer`. `useReducer` can handle multiple difference states that you access via (e.g.) `select` statements in the reducer function.

## Day 45: Monday 13 June 2022

**Today’s progress:** Week 8 of school and new partner is Lorentz! Today we are learning about pure functions in React and the important of purity so that React works. In the morning I managed to get my blog page from the recap task working with an 'Add comment' function. In the afternoon we looked at `useEffect` and its uses and limitations.

**Thoughts:** Realised that the way I did my form (ahem...`getElementById`) was Not Good, lol. Probably should rework it. The best way seems to be to save states for the diff values needed from the field. See link that Afam sent

**Links:** [React docs Beta - Pure components - Challenges](https://beta.reactjs.org/learn/keeping-components-pure#challenges) | [React form onSubmit handler](https://epicreact.dev/how-to-type-a-react-form-on-submit-handler/)

## Day 44: Sunday 12 June 2022

**Today’s progress:** Worked on the w7 recap tasks and have set up a blog with comments using React. So far, it's completely static - next step is to be able to add comments and have React update the page automagically.

For the destination list that was from Friday's hackathon, I managed to figure out the edge cases of the first and last arrow buttons (OK... just by setting `visibility: hidden` lol)

**Thoughts:** XXX

**Links:** [xx]() | [xx]()

## Day 43: Saturday 11 June 2022

**Today’s progress:** Made some changes to the hackathon holiday destinations list today. Added a 'Sort alphabetically' button, as a challenge issued to me yesterday by my mentor. Was slightly too easy actually, just needed a new function with `setArray([...array].sort())`. The sort method automatically sorts alphabetically so it was quite straightforward. The other challenge was to be able to manually reorder the items in the list with arrow buttons or a drag and drop.

_Updated a few hours later..._ Spent absolutely ages getting Font Awesome to work in React but it works :D I've now added sort buttons, but haven't addressed the edge cases of the top and bottom items in the list. Tomorrow!

**Thoughts:** Extremely tired today as I went out last night! But feeling better as I had some water and did some coding :)

**Links:** [Sort method MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) | [Font Awesome in React](https://fontawesome.com/v5/docs/web/use-with/react#using-icons)

## Day 42: Friday 10 June 2022

**Today’s progress:** React-a-thon Today! Raj and I made a 'to-do list'-style app that was actually a list of holiday destinations. Mentor meeting after school and Mark has given me homework to do 😂

**Thoughts:** It was awesome and I'm really proud of how much we got done

**Links:** [W7 React Hackathon](https://github.com/hcmcfarlane/w7d5-fork-hackathon_react-athon-hannah-and-rajesh)

## Day 41: Thursday 9 June 2022

**Today’s progress:** Trenton Moss from Team Sterka did the mindset session today (sort of a mini Insights Discovery). He introduced us to his 'Platinum Rule' : Treat others as _they_ wish to be treated. Great advice tbh. We learned about the spread operator, how to spread nested objects (etc) and the importance of immutability in React. The workshop in the afternoon was about using the spread operator to add, remove and replace data in arrays in objects. 🎵 _Spread and slice makes everything nice!_ 🎵

**Thoughts:** Looking forward to the hackathon!

**Links:** [Spread syntax - MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)

## Day 40: Wednesday 8 June 2022

**Today’s progress:** Have caught up on sleep now, so feeling a lot better and ready for more React! Today I also had my enablement coach meeting, where I got some amazing feedback, which really boosted me. Today we started on state changes with React and it seems to have sunk in! Made a fun little project in the workshop that took in some text and printed it out in different fonts. JSX is starting to come together, although I'm confused as to why style changes need so many damn braces haha. Also tried to do some more of the FreeCodeCamp responsive web design course. Want to finish the first three before I get a job... We'll see! I also tried the first code challenge on the React docs Learn page on states.

**Thoughts:** It's all coming together now... Sooon...

**Links:** [React State](https://beta.reactjs.org/learn/state-a-components-memory) | [xx]()

## Day 39: Tuesday 7 June 2022

**Today’s progress:** Didn't get much sleep last night, as my flight home from Tenerife was delayed. Muddled through a bit! Morning we had a guest talk from Nick Truby from BT who showed us how he works with React in his day-to-day job. More on React – today delving into JSX, what Babel is, and how to have child elements in React. Then we spun up React apps using `npx create-react-app` (CRA) rather than the CDN, although mine didn't work as nodist still doesn't have support for updated version of npx. We also learned about the conventional ways to structure a React app, with components in subfolders and so on.

**Thoughts:** Tired, but really enjoying learning React.

**Links:** [CRA](https://create-react-app.dev/)

## Day 38: Monday 6 June 2022

**Today’s progress:** Did school from the hotel lobby today :) Intro to React! Fab guest talk in the AM from Piper Bates about their work and their journey from bootcamper to developer. In the PM we learnt about how React is a library, not a framework, and how it reacts to DOM changes using the virtual DOM, how it contains easily reusable components, and what those components look like. We initially used React from a CDN, and used `React.createElement` and props to create some functional components.

**Thoughts:** Hooray!

**Links:** [React docs](https://reactjs.org/) | [Beta React docs](https://beta.reactjs.org/) (written with hooks) | [Piper Bates](https://twitter.com/ProgrammerPiper)

## Days 36, 37 Thursday 2 June–Sunday 5 June 2022

**Today’s progress:** On holidays over the Queen's Jubilee bank holiday, so I only did a few hours coding over the long weekend. I worked on the week 6 weekend recap task, did some more practice with Cypress and supertest, and read/watched a few blogs and videos on React in preparation for Weeks 7–8!

**Thoughts:** Really excited to get into React. Also extremely relaxed from lying in the sun most days.

**Links:** [Fireship - React in 100 seconds](https://www.youtube.com/watch?v=Tn6-PIqc4UM)

## Day 35: Wednesday 1 June 2022

**Today’s progress:** Testing with supertest and Cypress.

**Links:** [Supertest docs](https://www.npmjs.com/package/supertest)

## Day 34: Tuesday 31 May 2022

**Today’s progress:** Recap of Jest and the importance of test-driven development. Guest talk in the arvo on intro to testing with Cypress: Jordan Powell and Robert Guss. Extremely generous with their time today, we had a very comprehensive session with plenty of time for questions.

**Thoughts:** I hope we get to try out Cypress ourselves tomorrow.

**Links:** [Cypress docs](https://docs.cypress.io/) | [TDD video from Fireship](https://www.youtube.com/watch?v=Jv2uxzhPFl4)

## Day 33: Monday 30 May 2022

**Today’s progress:** Started on testing today with Jest.

**Thoughts:** Seems straightforward, it will only get worse I imagine.

**Links:** [Jest docs](https://www.npmjs.com/package/jest)

## Sunday 29 May 2022

**Today’s progress:** No coding today as I was working.

## Day 32: Saturday 28 May 2022

**Today’s progress:** Week 5 recap task on a cats API and meeting up with some of the London SOC cohort :) An absolutely amazing evening

**Thoughts:** Love meeting people in real life, it gives me a real boost

## Day 31: Friday 27 May 2022

**Today’s progress:** Hackathon Friday! Making a full-stack API. Jay and I managed to get the front-end linked up and reading from our Heroku db, which felt pretty amazing. Had my mentor meeting this afternoon too, and Mark gave me some incredible ideas for fun things to do with the data.

**Thoughts:** Great day! Looking forward to the recap task over the weekend.

**Links:** [Mockaroo - db generator](https://www.mockaroo.com/)

## Day 30: Thursday 26 May 2022

**Today’s progress:** Mostly a recap of yesterday's concepts. I practiced some more complex PostgreSQL statements in the evening. My friend Rish from Australia had a layover in London and he generously popped over for lunch – it was amazing to see him!

**Thoughts:** Pretty good day, revisiting the concepts we looked at on Wed.

**Links:** [PG Exercises](https://pgexercises.com/)

## Day 29: Wednesday 25 May 2022

**Today’s progress:** Today we linked our app to a Heroku db using the node package `pg` and `const pool = new pg.Pool()`, which creates a connection pool. The links (e.g. username, password, host, port) are stored in a (gitignored!) file called `.env`, and we used a node package called `dotenv` to make them accessible to our pool using `process.env.PGUSER` and so on.

Then we made a query function that allows us to send SQL queries to that Heroku db:

> `function query(text, params, callback) { return pool.query(text, params, callback); }`

That meant we could use code like `const res = await query(sqlString)`, where `sqlString` is the SQL query we want to send – meaning we can create a table on the Heroku server and populate it with data from a file. All quite exciting

**Thoughts:** Pretty fast pace today and lots of people seemed pretty confused. There were quite a lot of concepts thrown at us, but I'm feling fine with those concepts just sitting there for now and being secure in the knowledge that we'll be practicing them so much that it will all fall into place.

**Links:** [xx]() | [xx]()

## Day 28: Tuesday 24 May 2022

**Today’s progress:** More on SQL today – in particular, the last of the CRUD operations, DELETE, and INNER JOIN and the different possible types of JOINs. I also looked at some useful SQL functions (see link), and Jay and I did some SQL codewars.

After lunch, my carbon monoxide alarm went off, and I smelled gas in the kitchen. I called the fire brigade immediately, who couldn't actually find anything wrong – concluding that the CO alarm was faulty. Fortunately though, 999 had also sent out a gas man from SGN, whose CO alarm quite dramatically started blaring as I walked him into the kitchen. He realised that the flue on the boiler was dislodged, and was spewing gas everywhere. **_PANIC TIME_**.

We rushed around to open up all the windows and clear the house before we died. He switched off the gas and condemned the boiler on the spot, also kindly giving us a portable stovetop and some heaters to tide us over. He was very concerned and told me probably _too many_ times how I nearly died, or could have died overnight. The landlord has been contacted and we are hopefully getting a new boiler tomorrow. Meanwhile, no hot water... Will try to make up some time this eve. I think today I deserve a takeaway for dinner...

So that was quite the interruption to my SQL learning today haha.

**Thoughts:** Nearly died today so thoughts are mostly adrenaline!

**Links:** [SQL Bolt](https://sqlbolt.com/) | [DB Fiddle - joins test env](https://www.db-fiddle.com/f/4FJEKAFU4SS5uECGdLeXgM/0) | [18 important SQL fns](https://learnsql.com/blog/18-important-sql-functions-learn-2018/)

## Day 27: Monday 23 May 2022

**Today’s progress:** Intro to SQL! I'm having some weird flashbacks to my first year of uni (2007!) when I took an intro to information technology class. We must have done some SQL stuff then because I vaguely remebered the syntax. Great day, with a good talk from Kyle Simpson, author of _You Don't Know JS_, who offered some good advice on applying for jobs where you don't meet 100% of the criteria, ensuring that the web is made accessible, and about leaving things better than you found it, for the benefit of the next generation of programmers. Some of his diversity/accessibility stuff was good, some of it was not that great. Overall though, he was an engaging speaker.

**Thoughts:** Looking forward to SQL week, and figuring out how this links to JS!

**Links:** [intro to SQL - DB-fiddle](https://www.db-fiddle.com/f/dg2RJvBX1aZda3ECwQUSoe/4) | [Relevant XKCD - Query](https://xkcd.com/1409/) | [SQL on w3 schools](https://www.w3schools.com/sql/default.asp) | [Kyle Simpson – "Keep Betting on Javascript"](https://www.youtube.com/watch?v=51QNMy9MlZY) – 2019 youtube talk

## Day 26: Sunday 22 May 2022

**Today’s progress:** Week 4 recap task. This task was fairly easy, as it was basically a replica of what we did during the week except with a database of users rather than recipes or books. Still, it was useful to cement my knowledge of all the CRUD-type request syntaxes, and ensure that I fully understood everything that we did during the week. I implemented one nifty thing I didn't do this week - when the client tries to update a user via a PUT request, I wrote some code to ensure that the user ID cannot be overridden. I mean it was only one line of code but I felt smart for doing that. I am considering adding some even better sanitizing/error-handling features tomorrow morning before school starts at 11.

**Thoughts:** Confident!

**Links:** [xx]() | [xx]()

## Saturday 21 May 2022

**Today’s progress:** No coding today. Spent time with friends, relaxed, and had a kind of average pho. We went to play some retro games at the Science Museum and I got to bed early :)

## Day 25: Friday 20 May 2022

**Today’s progress:** "Hackathon" day as per usual for Fridays! A really good day - my partner and I managed to get through the main tasks of setting up our node express handlers for GET (all recipes), GET (recipe by id), POST, PUT and DELETE. We were able to get the form on the HTML page (which was given to us) to display, and even automatically give each new recipe an id number. It was a great day and we worked well together. In the evening after school I had my mentor meeting with Mark, which was great as usual - I asked him about the sorts of uses for the API that his company provides and we talked about what back-end engineering is, as well as briefly on how to have ideas.

**Thoughts:** Think I am getting the hang of this back-end stuff. It was a good week in general, really - in no small part perhaps due to not doing any freelance work the last two weeks, which has freed up my time on the weekends to actually relax and prepare for the week ahead.

**Links:** [xx]()

## Day 24: Thursday 19 May 2022

**Today’s progress:** Mindset Thursdays! Self-critique and resilience. I definitely am a perfectionist, one of the self-criticism archetypes we talked about. Joseph's advice was to use that strive to always to better to work on constant improvement rather than achieving "perfection":

-   Set deadlines and stick to them
-   Pick one thing and set check points for feedback on it
-   _Leverage your talent_ by using that feedback and learning quickly
-   **Stretch goal:** release something before you think it's ready

I think this is really good advice and will try to stick to it. We then also had 10 mins prepare, then to present to a small group about something we've learned, I chose RESTful APIs although I don't _really_ know much about them.

On the coding side, we looked at middleware, including loggers, rate-limiting and `express.json()`, an _extremely_ useful middleware that parses json data in POST reqs. We used POSTman to send POST requests to the books data 'app' we've been using this week.

For the afternoon, in a team of four (Owen, Emma K, Simon B and me), we had to research a topic (express rate limiting) and present it to the group at the end of the day.

**Thoughts:** Good day, I felt I really had a handle on the stuff. Joseph's mindset session was useful as always!

**Links:** [npm express-rate-limit](https://www.npmjs.com/package/express-rate-limit)

## Day 23: Wednesday 18 May 2022

**Today’s progress:** Today we looked at how to use the client's query request (like `localhost:3000/books?title=night`) to send back the data for the books with 'night' in the title. I could see straight away how this relates to search buttons, which is cool. We also looked at what a RESTful API is.

**Thoughts:** I was quite tired today but everything made sense :)

**Links:** [REST API](https://restfulapi.net/)

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
>
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

**Today’s progress:** Today at SOC we looked at Agile and UX/UI concepts, with a talk from Pavaan Buddhdev about the 'magic' of UX/UI: storytelling, attention/misdirection and wonder. Did 'can't unsee' game (silver!)

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

**Today’s progress:** Started out with Codewars today. Biggest takeaway - Javascript uses `**` for exponentiation, not `^` ... _\*\*cries in maths assumptions\*\*_

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

```

```
