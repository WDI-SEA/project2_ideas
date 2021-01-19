# Project 2 Ideas!

Your second Project will be your first foray into building a full-stack application, from scratch, on your own.

Project 2 is really exciting! It can also, by nature, sound a bit overwhelming.

We want to see you succeed! So over this weekend, we want you to come up with some ideas for your Project 2. 

**We will be looking for 3 project ideas, turned in via pull request to this repository, that illustrate a rough concept of what you might do for your project 2!**

## Technical Requirements for P2:

Your app must:
- Have at least 2 models (more if they make sense) that represents the main functional idea for your app. This doesn't include join tables or the user model which should be part of your class's boilerplate code.

> Note: If your app idea doesn't really call for more models, let your instructors know and they can suggest ideas for other sufficiently difficult replacements for this requirement.

- Include sign up/log in functionality, with hashed passwords & an authorization flow
- Incorporate at least one API. Examples include Yelp, Tumblr, Facebook, and others on Mashape. Maybe grab an API from this [list of free APIs](https://github.com/public-apis/public-apis)
- Have complete RESTful routes for at least one of your resources with GET, POST, PUT, and DELETE
- Utilize an ORM to create a database table structure and interact with your relationally-stored data
- Include a readme file that explains how to use your app
- Have semantically clean HTML, CSS, and back-end code
- Be deployed online and accessible to the public



## Write your 3 ideas below this line:
<hr>
## Idea 1: Genshin Impact Character Tracker
Track your Mond-stats 
Instead of having to log in to your game each time you want to see what your character's stats are, or what weapons equipped by your characters have ascension material dungeons for today, document your character statistics in the Genshin Impact Character Tracker for ease-of-reference.

You can also take notes on what ascension materials you still need for your characters or their weapons, and which specific artifacts you need for each character. You can add, edit, and delete these goals on your dashboard.

You'll have to log in because your character details are specific to your account, and there need to be Sequelize models for character, details about their weapon, and details about their artifacts.

Because you're building your characters, you can also edit their information.

There are some APIs for Genshin Impact characters and their artifacts, but they're not very robust so I might have to use a web scraper as well.

<hr>
## Idea 2: Book Buddy
Instead of commenting how you feel about a book after you've finished reading it, you can comment on it throughout reading through it and journal your feelings for a book. You can also just track which books you want to read, are currently reading, and have finished reading if you would rather not review/comment on any.

Log in to view which books you've read and write, update, or delete your comments / reviews as you read through the book.

I can probably find an API that stores the word count of each book, or how many chapters are in each book, to help with tagging where each comment belongs (Or, the user can write down which page they're on). I can also find an API to help populate the author of a book, for if you know the name of the book and can recognize but not come up with the author's name.

An API to grab book covers for each book would also be useful. Else, I can use Wikipedia or another book catalogue to web scrape images. 

Models would be needed for books (author, title, number of pages), comments (which page the comment was made, when the comment was created, when the comment was last edited)

<hr>
## Idea 3: 
Important Purchases
Same as book buddy but for storing the cost and information regarding large purchases you've made. That way you can remember how much you paid for something, plus the details about that transaction.

For example, cost, date of purchase, warranty details, specifications.

Another table would be for user-generated categories, since one item can have multiple categories. An example of a category could be 'health,' 'over $1k,' or 'planned' vs 'impulse' purchases. 

Can also creating a shopping list of things that eventually need to be purchased or will be purchased, and use an API to grab Amazon links for similar items. 





