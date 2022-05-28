# Internship or Junior Level Job Plan

- [Internship or Junior Level Job Plan](#internship-or-junior-level-job-plan)
  - [TLDR Plan](#tldr-plan)
  - [Tech Skills to Demonstrate](#tech-skills-to-demonstrate)
  - [Soft Skills to Demonstrate](#soft-skills-to-demonstrate)
  - [Things to remember:](#things-to-remember)
  - [Understanding Coding Interviews and how to prepare](#understanding-coding-interviews-and-how-to-prepare)
  - [Interview Softskills and Expected Questions](#interview-softskills-and-expected-questions)

## TLDR Plan

Note that these aren't "blockers" from applying to jobs. Ideally they are things we should be doing while it's happening!

- Work with Ryan to get your resume and linkedin spiffy. I'm good at resumes/linkedin.
- Two tech projects:
  - A custom fullstack web app, ideally that stands out and isn't a cookie cutter project - host it!
  - A simple home page with some custom HTML/CSS - provide resume, link to github, etc.
- Practice interviews with Ryan
- Job application and cover letter writing
- Learning new skills as interested or time allows (often a nice break from the above)


## Tech Skills to Demonstrate

In order of priority

| Ranking                                         | Skill                  | Goal                                                                                                                                                                                                                                                                                                                 |
| ----------------------------------------------- | ---------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Necessary                                       | Javascript             | Be able to program well in Javascript (outside of packages)                                                                                                                                                                                                                                                          |
| Necessary                                       | React                  | Be able to build components in React                                                                                                                                                                                                                                                                                 |
| Necessary                                       | Bare HTMl and Bare CSS | Be able to write HTML and CSS without relying wholely on HTML/CSS packages and libraries. At a minimum understand how HTML and CSS work and interact with the web and be able to tweak/modify/customizing existing html/css                                                                                          |
| Necessary                                       | Git and Github         | Be able to make commits and pull requests - both locally and on github as appropriate                                                                                                                                                                                                                                |
| Important to Standout                           | Testing                | Be able to write unit tests for your code (BE and appropriate FE stuff), understand the difference between a unit test and integration test                                                                                                                                                                          |
| Important to Standout                           | Debugging              | Be able to debug when something isn't working in your system including: print statements in the console or debugger, using dev tools in the browser, reading error messages, googling effectivelly, reading docs. Good debugging requires undertsanding of the system (which is a huge shining star for an employee) |
| Important to Standout                           | Deployment             | Be able to deploy a full stack project on the web using a tool like heroku, netlify, firebase or similar (or in a docker container if you're crazy)                                                                                                                                                                  |
| Important to Standout                           | Typescript             | Typescript is a javascript flavor that allows you to specify types; your editor and linters can help identify likely errors ahead of time. It's widely used in industry over raw javascript.                                                                                                                         |
| Not critical, but can make you really stand out | Performance            | Be able to talk at a high level of server-side rendering vs client side rendering, be able to talk about [n+1 queries](https://medium.com/doctolib/understanding-and-fixing-n-1-query-30623109fe89)                                                                                                                  |
| Not critical, but can make you really stand out | SQL                    | Be able to write simple select queries with filters and aggregations in SQL. Bonus points for basic joins.                                                                                                                                                                                                           |
| Rare Jewel, not a high focus                    | Python                 | Python is the probably the second most important language in the full stack tech space today (behind JS). Knowing basics of an additional language (syntax, classes, OOP, testing) will help you think as a programmer.                                                                                              |
| Rare Jewel, not a high focus                    | Django                 | Django is the frontend web app framework of choice for python.                                                                                                                                                                                                                                                       |

Suggestions on how to demonstrate:
1. **Make a custom fullstack project, something interesting and personal.** 
     - Projects from bootcamp may work, but often bootcamp projects feel cookie cutter and don't stand out - everyone does a facebook clone or whatever. 
     - Make a webapp that allows you to put pins on a map of the places you been, the mountains you've climbed, or the resorts you've skiied. Make a web app that allows you to look up your usda hardiness zone by zip code and allows you to add plants to a database along with when they should be planted by hardiness zone. 
     - Something unique goes a long way. 
     - Use git/github. 
     - Deploy it so that it's public on the web. 
     - Make sure it has testing.
     - Make the code clean.
2. **Make a simple webpage for yourself** with your bio, contact, and resume using only HTML and CSS. Do enough interesting things (styling, colors, fonts, etc) to demonstrate skills.  Deploy it so that it's public on the web.
3. Make a (relatively simple) coderpen.io (do one of the monthly challenges?) to show off how you can build something interesting in CSS and HTML with minimal JS.

The goal is not for these projects to be perfect or complete (that's nice!), but to show that you have the skills and abilities to make them perfect. 

Softer things in tech space:
- **Clean code** - find some code that someone else experienced wrote that makes you go "man, this is clean". You want to aspire to that.
- **Strong readmes and comments** - projects should have good readmes that explain the what, why, and setup. Comments should be impactful or provide clarity to confusing code.

## Soft Skills to Demonstrate

| Skill                                                                         | Why                                                                                                                                                                                                                                                                                                                                                                                                | Interview Lines                                                                                                                                                                                                                                                        |
| ----------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Learning Mindset                                                              | Software engineering is perpetually changing, and, especially for juniors or interns, you have a lot to learn. Be excited about learning and have a interest in how things work and why experience people do something a given way                                                                                                                                                                 | I actually don't know how that works or why that works that way - I'm not going to pretend to know. Here's what I'd do to start to learn it. I'd love if you can teach me faster!  Ask a bajillion questions about how and why there things work.                      |
| Be receptive to feedback                                                      | You're going to do things "wrong". It will be years before you make a meaningful PR and have no suggeted changes (or you have terrible PR reviewers). This is ok and expected! Understand that feedback, while occasionally blunt, isn't a statement of your abilities, potential, or quality - its just a negotiation about what works best for the larger group and an opportunity for learning. |                                                                                                                                                                                                                                                                        |
| Don't have a tech that is "best"                                              | I promise you your favorite tech is not the best                                                                                                                                                                                                                                                                                                                                                   | I'm most familiar with JS and React, but I'm open to learning other tools or frameworks. Languages and frameworks are just tools, some may be better for given purposes but they aren't naturally superior than each other. It's how you use a tool that's meaningful. |
| Be confident that you can learn, but be honest that you don't know everything | You want to avoid appearing like you think you know everything. You also don't want to give off the lost helpless duckling vibe. You want to be confident in your future, know the things you do know, and know that you have a lot to learn.                                                                                                                                                      |                                                                                                                                                                                                                                                                        |
| Pair Programming - how to lead                                                | Learn how to build a feature with someone following; learn how to explain what your doing and why. Usually goal for step, write test, code, repeat till it works, then next goal.                                                                                                                                                                                                                  |                                                                                                                                                                                                                                                                        |
| Pair Programming - how to follow and learn                                    | Learn how to watch someone else build a feature. Ask questions, catch edge cases, etc.                                                                                                                                                                                                                                                                                                             |
| Pair Programming - how to interject                                           | Peers and Seniors will pair program and will do something that's unclear to you (why or methodology) or do something wrong. Learn how to interject effectively - this is part timing, part communication, part relationship. I generally ask questions first then escalate to providing examples of where something may not work. Never just say "that is wrong".                                  |                                                                                                                                                                                                                                                                        |
| Understand you're a beginner and will be for sometime                         | It takes years to become an expert at software. That's ok. Don't act like you know everything.                                                                                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                        |
| Ask for help effectively                                                      | You don't want to be a know-it-all or helpless duckling, but you will need help. Learn how to ask for help effectively. Big tips: 1. spend 15-30 minutes minimum trying to figure it out on your own 2. Ask a question with context ("I'm trying to do x here beacuse Y and z is happening. Can anyone tell me how to do x? I've tried a".) 3. Be patient and work in other areas when blocked     |
| Be friendly and personable                                                    |                                                                                                                                                                                                                                                                                                                                                                                                    |



## Things to remember:

- **Practice is required** - you're a beginner and all of this information isn't seared in your head. (The languages that I was an expert in at one point, but I haven't used in 6+ months are hard for me for basic functionality!) Practice regularly - make a simple coderpenio, add a new feature to an existing project, do a leetcode, try out a new framework. You've got to be practicing to keep the skills up (until you get a job then you practice every day).
- **You'll screw up on something** - every software engineer has horror stories of times they broken things (dropped a table, took down the production server, etc). It'll happen. Your goal is to identify it happened quickly, escalate effectively, and learn from your mistakes.
- **Learn to ask for help well**

## Understanding Coding Interviews and how to prepare

To fill in

- what do interviews look like
- what do you do when you don't understand the question
- what do you do when it's not going well
- what should you expect
- common questions and how to answer them

## Interview Softskills and Expected Questions

RYAN NEEDS TO DISTILL BELOW:

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

Pair programming: If possible get some practice coding while someone is watching and evaluating you. This is a way different experience than coding alone and is something that hugely affects and surprises new devs when interviewing for the first time

Clean code: from now on make it a habit to use ESlint and prettify for all javascript projects, as well as equivalent linters and formatters for other languages

Git: bonus points for using and understanding rebase and interactive rebase