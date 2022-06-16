# Internship or Junior Level Fullstack Job Plan

- [Internship or Junior Level Fullstack Job Plan](#internship-or-junior-level-fullstack-job-plan)
  - [TLDR Plan](#tldr-plan)
  - [Background / About the Author](#background--about-the-author)
  - [Tech Skills to Demonstrate](#tech-skills-to-demonstrate)
    - [Suggestions on how to demonstrate:](#suggestions-on-how-to-demonstrate)
    - [Softer things in tech space:](#softer-things-in-tech-space)
  - [Soft Skills to Demonstrate](#soft-skills-to-demonstrate)
  - [Things to remember:](#things-to-remember)
  - [Understanding Coding Interviews](#understanding-coding-interviews)

## TLDR Plan

Note that these aren't "blockers" from applying to jobs. Ideally they are things you should be doing continually while applying and inteviewing!

- Work with someone to get your resume and linkedin spiffy
- Two tech projects:
  - A custom fullstack web app, ideally that stands out and isn't a cookie cutter project - host it!
  - A simple home page with some custom HTML/CSS - provide resume, link to github, etc.
- Practice interviews, preferrably with someone in the tech space
- Job application and cover letter writing
- Learning new skills as interested or time allows (often a nice break from the above)

## Background / About the Author

I am a data scientist/data engineer with a great coding foundation. 

I am not a frontend or backend developer, nor have I ever been on the technical side of interviewing frontend, backend, or fullstack developers.

However, I have worked with 100s of engineers on all sorts of problems, asked them about they how the hire, how they interview, and how they excel. 

This document is the summation of my discussions with them, both implicit and explict. Several of my closer engineering friends and I had heavy discussions as I was writing this; to them I owe a deep thanks (and a shout out if they want one).


## Tech Skills to Demonstrate

In order of priority

| Ranking                                         | Skill                  | Goal                                                                                                                                                                                                                                                                                                                                                                                 |
| ----------------------------------------------- | ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Necessary                                       | Javascript             | Be able to program well in Javascript (outside of packages)                                                                                                                                                                                                                                                                                                                          |
| Necessary                                       | React                  | Be able to build components in React                                                                                                                                                                                                                                                                                                                                                 |
| Necessary                                       | Bare HTMl and Bare CSS | Be able to write HTML and CSS without relying wholely on HTML/CSS packages and libraries. At a minimum understand how HTML and CSS work and interact with the web and be able to tweak/modify/customize existing html/css                                                                                                                                                            |
| Necessary                                       | Git and Github         | Be able to make commits and pull requests - both locally and on github as appropriate. Know how to use git well in a team setting (use feature branches, don't push to master, small meaningful commits and PRs). Bonus points for knowing about rebasing and how to do an interactive rebase.                                                                                       |
| Important to Standout                           | Testing                | Be able to write unit tests for your code (BE and appropriate FE stuff), understand the difference between a unit test and integration test                                                                                                                                                                                                                                          |
| Important to Standout                           | Debugging              | Be able to debug when something isn't working in your system including: print statements in the console or debugger, using dev tools in the browser, reading error messages, googling effectivelly, reading docs, tracing the flow of data through functions and services. Good debugging requires understanding of the system (which is a huge shining star for an junior employee) |
| Important to Standout                           | Deployment             | Be able to deploy a full stack project on the web using a tool like heroku, netlify, firebase or similar (or in a docker container if you're crazy)                                                                                                                                                                                                                                  |
| Important to Standout                           | Typescript             | Typescript is a javascript flavor that allows you to specify types; your editor and linters can help identify likely errors ahead of time. It's widely used in industry over raw javascript.                                                                                                                                                                                         |
| Not critical, but can make you really stand out | Performance            | Be able to talk at a high level about server-side rendering vs client side rendering, be able to talk about [n+1 queries](https://medium.com/doctolib/understanding-and-fixing-n-1-query-30623109fe89)                                                                                                                                                                               |
| Not critical, but can make you really stand out | SQL                    | Be able to write simple select queries with filters and aggregations in SQL. Ideally undestand basic joins as well.                                                                                                                                                                                                                                                                  |
| Rare Jewel, not a high focus                    | Python                 | Python is the probably the second most important language in the full stack tech space today (behind JS). Knowing basics of an additional language (syntax, classes, OOP, testing) will help you think as a programmer.                                                                                                                                                              |
| Rare Jewel, not a high focus                    | Django                 | Django is the frontend web app framework of choice for python.                                                                                                                                                                                                                                                                                                                       |

### Suggestions on how to demonstrate:

1. **Make a custom fullstack project, something interesting and personal.** 
     - Projects from bootcamp may work, but often bootcamp projects feel cookie cutter and don't stand out - everyone does a facebook clone or whatever. 
     - Make a webapp that allows you to put pins on a map of the places you been, the mountains you've climbed, or the resorts you've skiied. Make a web app that allows you to look up your usda hardiness zone by zip code and allows you to add plants to a database along with when they should be planted by hardiness zone. 
     - Something unique goes a long way. 
     - Use git/github. 
     - Deploy it so that it's public on the web. 
     - Make sure it has testing.
     - Make the code clean. 
  
  A key part of bootcamps or getting your first software engineering job is projects - your goal is to show that you know how to program well and would fit in within a formal programming setting. This means you should demonstrate clean code, good testing practices, and a working product.

  You're secondary goal is to stand out. People hiring junior programmers see LOTS of projects. You have an advantage if you do something interesting and unique and you're at an advantage if you do something related to something you are passionate about.

  Some unique project ideas:

  - A web app that allows look up of USDA hardiness zone [formal example]](https://planthardiness.ars.usda.gov/) and gives recommended planting times for common veggies based on zone. This could even be a user contributed database!
  - Bring online plant databases into the modern age (i.e I use these plant databases regularly and they are ok at best for user-friendliness: [http://floraofalabama.org/](http://floraofalabama.org/) and [https://www.wildflower.org/](https://www.wildflower.org/))
  - A web that allows user to put a pin on a map for where they are from and for an establishment to show where visitors have come from (think the map with pins at a tourist trap, but done online)
  - Pick something you are passionate about - what can you build?


1. **Make a simple webpage for yourself** with your bio, contact, and resume using only HTML and CSS. Do enough interesting things (styling, colors, fonts, etc) to demonstrate skills.  Deploy it so that it's public on the web.
2. Make a (relatively simple) coderpen.io (do one of the monthly challenges?) to show off how you can build something interesting in CSS and HTML with minimal JS.

The goal is not for these projects to be perfect or complete (that's nice!), but to show that you have the skills and abilities to make them perfect. 

### Softer things in tech space:

- **Clean code** 
  - Find some code that someone else experienced wrote that makes you go "man, this is clean and oragnized". You want to aspire to that. Look at multiple examples as there are differnet styles.
  - Use [ESlint](https://eslint.org/) (or appropriate linter for your language!)
  - Use [prettier](https://prettier.io/) or similar (or appropriate formater for your language!)
- **Strong readmes and comments** - projects should have good readmes that explain the what, why, and setup. Within 2 minutes of skimming your repo I should know:
  - What
- **Meaningful Code Comments**
  - Code comments should be impactful or provide clarity to confusing code. 
  - Don't write comments that just say what your code is doing like:
    ```js
    var x = 1; 
    var y = 2; 
    // Add values together (This is a BAD comment)
    var result = x + y
    ```
  - If you find yourself writing comments like the above, you should probably refactor your code into smaller pieces (more focused methods, functions, or classes).

## Soft Skills to Demonstrate

| Skill                                                                         | Why                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Interview Lines                                                                                                                                                                                                                                                           |
| ----------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Learning Mindset                                                              | Software engineering is perpetually changing, and, especially for juniors or interns, you have a lot to learn. Be excited about learning and have a interest in how things work and why experience people do something a given way                                                                                                                                                                                                                                                  | - "I actually don't know how that works or why that works that way - I'm not going to pretend to know. Here's what I'd do to start to learn it. I'd love if you can teach me faster!"  Ask a bajillion questions about how and why their things work the way they do.     |
| Be receptive to feedback                                                      | You're going to do things "wrong". It will be years before you make a meaningful PR and have no suggested changes (otherwise you have terrible PR reviewers). This is ok and expected! Understand that feedback, while occasionally blunt, isn't a statement of your abilities, potential, or quality - it's just a negotiation about what works best for the larger group and an opportunity for learning.                                                                         | "Ok, I understand what you're suggesting - can you explain why? I was leanding towards doing XXX like YYY because ZZZZ; what adavantages does your method offer? What faults am I missing in my method?"                                                                  |
| Don't have a tech that is "best"                                              | I promise you your favorite tech is not the best. You want to position yourself as a humble learner, not a know-it-all. Know-it-all's suck to work with.                                                                                                                                                                                                                                                                                                                            | "I'm most familiar with JS and React, but I'm open to learning other tools or frameworks. Languages and frameworks are just tools, some may be better for given purposes, but they aren't naturally superior than each other. It's how you use a tool that's meaningful." |
| Be confident that you can learn, but be honest that you don't know everything | You want to avoid appearing like you think you know everything. You also don't want to give off the lost-helpless-duckling-vibe. You want to be confident in your future, know the things you do know, and know that you have a lot to learn.                                                                                                                                                                                                                                       |                                                                                                                                                                                                                                                                           |
| Pair Programming - how to lead                                                | Learn how to build a feature with someone following; learn how to explain what your doing and why. Usually you establish a goal for the next step step, write some tests test, code, run tests, repeat coding till the test works, then establish the next goal.                                                                                                                                                                                                                    |                                                                                                                                                                                                                                                                           |
| Pair Programming - how to follow and learn                                    | Learn how to watch someone else build a feature. Ask questions, catch edge cases, etc.                                                                                                                                                                                                                                                                                                                                                                                              |
| Pair Programming - how to interject                                           | Peers and Seniors will pair program and will do something that's unclear to you (why or methodology) or do something wrong. Learn how to interject effectively - this is part timing, part communication, part relationship. I generally ask questions first then escalate to providing examples of where something may not work. Never just say "that is wrong".                                                                                                                   | **Good**: "Should that variable actually be an array? Don't we want to store multiple values here?" **Bad**: "Line 14 is wrong, we need an array."                                                                                                                        |
| Ask for help effectively                                                      | You don't want to be a know-it-all or helpless duckling, but you will need help. Learn how to ask for help effectively. Big tips: 1. spend 15-30 minutes minimum trying to figure it out on your own 2. Ask a question with context ("I'm trying to do x here beacuse Y and z is happening. Can anyone tell me how to do x? I've tried a".) 3. Be patient and work in other areas when blocked  When in doubt, ask the person you need help from how to ask for help in the future! | "I've been asking a lot of questions - would you prefer me to save them up and ask  you a batch at the end of the day? How long should I try to figure things out on my own before I reach out? Any resources Is should know about?"                                      |
| Be friendly and personable                                                    | In interviews and coworkers you want to be authentic but not at the expense of being pleasant and friendly. When in doubt follow the golden rule and ask people how you can best work with them?                                                                                                                                                                                                                                                                                    | "Do you want me to provide comments while your programming this section or wait until it's completed so we can go over it together?"                                                                                                                                      |
| Understand you're a beginner and will be for sometime                         | It takes years to become an expert at software. That's ok. Don't act like you know everything.                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                           |




## Things to remember:

- **Practice is required** - you're a beginner and all of this information isn't seared in your head. (The languages that I was an expert in at one point, but I haven't used in 6+ months are hard for me - even basic functionality!) Practice regularly - make a simple coderpenio, add a new feature to an existing project, do a leetcode, try out a new framework. You've got to be practicing to keep the skills up (until you get a job then you practice every day).
- **You'll screw up on something** - every software engineer has horror stories of times they broken things (dropped a table, took down the production server, etc). It'll happen. Your goal is to identify it happened quickly, escalate effectively, and learn from your mistakes. Own your mistakes - that breeds respect from senior devs and managers (who have all screwed up worse than you).
- **Learn to ask for help well**

## Understanding Coding Interviews

FILL IN AND CLEAN UP - this is just notes at this point.

- what do interviews look like
- what do you do when you don't understand the question
- what do you do when it's not going well
- what should you expect
- common questions and how to answer them

Pair programming: If possible get some practice coding while someone is watching and evaluating you. This is a way different experience than coding alone and is something that hugely affects and surprises new devs when interviewing for the first time

Good idea to have a "personal story" and be able to speak to it. Ex. Interviewers may ask questions like:

- What were you doing before the bootcamp?
- Why did you decide to go to a bootcamp?
- Why not just teach yourself web dev?
- What interests you about programming/web dev?
- Why do you want to be a web developer?

They may not ask these exact questions but knowing how to answer them will give you more confidence when speaking to these things.

Be able to speak informatively about the tools you already use. This is especially important when presenting a project to an interviewer, which is a pretty popular thing for interviewers to ask new devs. Ex. you might get questions like:

- You went to a bootcamp that uses React as a major tool– why is that? What is it about React that makes it so effective for creating frontend applications vs. other ways of doing it?
- You chose to use a css framework for this project. Why not use custom css? What are some of the trade-offs of using this framework vs. others vs. css from scratch?
- You use nodejs for your server code. What are the benefits of using node vs. similar frameworks?



