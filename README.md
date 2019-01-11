# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

HTML is the language that tells the browser what to display. But the browser isn't the only thing that reads that language. Three other things read the HTML you write:
First, other developers read your HTML. When you're working on a large project, multiple people work on the same code. Writing code in a way that is easy for others to understand is essential to effective collaboration. Plus, you'll be thankful that others do the same for you.
Second, everyone should be able to access your content. Everyone. People with limited vision or other circumstances have screen readers and other assistive tools that read your HTML and help them navigate the web. Your HTML has a direct impact on how those tools function for those people.
Third, the web is constantly being crawled by programs for companies like Google and Bing to index the web and provide search results. If you want to optimize for those web crawlers and their algorithms, it's wise to write your HTML in ways that make it easy for those crawlers to give you a high score.

To do all of that, we write our HTML with certain guidelines we call "semantic HTML". It structures your code in ways that is easier for developers (including yourself), screen readers, and web crawlers to navigate and to understand the heirarchy of the page – that is, what's most important and what's least important.

2. Name two big differences between ```display: block;``` and ```display: inline;```.

First, the width of a ```block``` element is set based on the width of its parent container, whereas the width of an ```inline``` element is based on the content it contains.

Second, the default height of a ```block``` element is based on the content it contains, whereas an ```inline``` element doesn't impact vertical spacing.

The general guideline is that ```block``` elements are for building webpages and layout, whereas ```inline``` elements are for styling the stuff inside the ```block```.

3. What are the 4 areas of the box model?

Content, padding, border, and margin.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

The cross axis.

5. Explain why git is valuable to a team of developers.

Git allows a team to collaborate on a single piece of software by controlling versions of that software. Branching is quite useful because it allows individuals to work on a specific section of the code base. For instance, one developer might be working on authentication while another is simultaneously working on the landing page. When they are finished, they can submit their changes to the top-level branch (called "master" in Git but that's a pretty awful word, really, with some nasty connotations and I don't know why Git uses it), and perhaps a more senior developer can review that submission and, if it's good-to-go, merge it into the live code. It's great!

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add PM as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on this Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your Project Manager as a Reviewer on the Pull-request
- [ ] PM then will count the HW as done by  merging the branch back into master.
 


## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [x] Build the HTML and CSS to create the missing navigation and header.
* [x] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [x] box1: `teal`
* [x] box2: `gold`
* [x] box3: `cadetblue`
* [x] box4: `coral`
* [x] box5: `crimson`
* [x] box6: `forestgreen`
* [x] box7: `darkorchid`
* [x] box8: `hotpink`
* [x] box9: `indigo`
* [x] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [x] Copy and paste your home page navigation and header into the about page
* [x] Update the header image with the about page image
* [x] Link the `Home` navigation item back to the `index.html` page.
* [x] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [ ] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing
* [ ] Add responsive breakpoints to your code by using media queries
