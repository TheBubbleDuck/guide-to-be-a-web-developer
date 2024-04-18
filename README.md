##The Brand New Developer

#### The Disclaimer Description Reason Thing
This is a quick guide to get people who ask how to get rolling on their path to becoming a web developer. There is a lot to learn and a lot that is debateable, but this is supposed to help them get moving somewhere. Keep in mind, this is gathered from my own experience and what I have dealt with. I wrote this thinking about what I would of wanted to tell myself a few years ago when I first got started.


### Quick Start Learning
Here are a few list of things to start learning. I will be updating this repo to try and make things organized in more of a book form once I start adding content or people collaborate on it. This is geared toward the JS developer. Although I will hit more of a front-end aspect, I will throw in some pieces to help newcomers look out for when dealing with backend development.

#### The 5 Basics Food Groups

### Version Control

```
What is ‘version control’, and why should you care? Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.”

			               ---- A snippet from www.git-scm.com ----
```

I chose version control first because it is pretty important in any language you pick up. It is also is great to  start learning git from the beginning so you can pick up the habit of versioning your code.

**Git** is, if I may, the preferred choice of version control for web developers. 
Some basics you'll want to pick up at first are

- Initializing Repositories
- Fetching, Pulling, Pushing
- Branching
- Commiting (w/ messages)
- Merging/Rebasing

Once you start learning **Git**, you can also pick things up like making pull requests and working in collaborative environments.

I would suggest to any new developer to get a GitHub account. Although my account may not have the most "activity", it is common to see more and more companies looking at your GitHub. On top of that, use it as a base of operations for your work, collaborate and see what other developers are doing, and engage with the rest of us! It is the social media of developers.

**Some Articles/Links to Help out**

- [GitHub Article](https://help.github.com/articles/good-resources-for-learning-git-and-github/)
- [git-scm book](https://git-scm.com/book/en/v2)

###The JavaScripts
JavaScript is not Java. Java is not JavaScript. Let's just get that out of the way.
Understanding the nuances of JavaScript takes time and experience. When I started out, it took me awhile to learn that I should favor === over == in my equality conditionals. Learning when and when not to use ternary operaters came later on. I don't think there is ever a complete understanding of JavaScript, especially as it evolves through out its EcmaScript lifecycles. At the time of this writing, ES6 will be in the birth pangs of its life. 

**Basic Understanding**

At the least, get an understanding of JavaScript, how to write out logic, and other basic details. For those who are coming to development rather new, take some time learning how JS works in general. Check out [CodeCademy](http://www.codecademy.com/).

**The Documentation and the Future**

If you really wanted to, you could dig into some of the current ES5 (and possibly ES6) documentation online and just going ham. However, it isn't always easy to understand it all if you aren't coding anything. Development is definitely a hands on type of thing.

**You Down with OOP?**

Learning **Object-Oriented Programming** concepts is definitely a plus. It isn't something that is necesarrily new, but JavaScript has definitely taken steps toward OOP design. Take some time to look up what OOP really is and then check out how you can apply it to JS. With ES6 around the corner, it also becomes a bit easier to implement and read with some of the new classables.

**Working With Data**

In many cases, apps and sites are driven by some sort of data, be it posts, images, comments, blogs, advertisments, etc. This data has to come some where and be handled by someone. That someone really is more of a something, and that would be good ol' Mr. JavaScript. The most common form that a lot of this data comes in is in the form of **JSON**. You can check out this [TutsPlus Tutorial](http://code.tutsplus.com/tutorials/understanding-json--active-8817) for some more information. You'll also see the term **API** come up a lot. When working with data, you'll be interacting with **APIs** to retrieve data. Learning basics of making an HTTP request to get this data is pretty key. How you do it is up to you whether using $.ajax, $http, custom XHR.

**Sharpen That Knife**

For some general practice using JavaScript, try [CodeWars](www.codewars.com) Kata system. I personally find them fun to try and come up with new ways to approach problems I've solved, view things from other developer perspectives, and just enjoy the logic we've all come to enjoy when coding.

**Keep It Clean**

Try picking up a sense of coding style. Although it changes from place to place, standard to standard, trying to maintain a sense of readability in your code. Code Quality is something that helps other people dig through your code easily, implement it elseware, etc. 

**Frameworks Work**

JavaScript, nowadays, comes in many forms of use and implementations. JS Frameworks are really popular. Try checking out some popular frameworks like [AngularJS](https://angularjs.org/), [ReactJS](https://facebook.github.io/react/), or  There are plenty more out there, but I am personally into React on the frontend. Backend stuf has it's own mess of things to include Next, Graphql/Apollo, and all kinds of stuff. Typical Node/Express is really good base in JS.

Frameworks aren't a necessary step quite yet for newer developers. However, it is great to at least get your hands dirty in them to see what they offer and how they work. Keep in mind that frameworks are a created to help solve issues that developers face. However, that doesn't mean they are the end all be all. 

There is still so much to learn!

### CSS and Preprocessers
CSS isn't just about making something "Look Pretty". Styling is a very important part of overall user experience and can greatly improve or destroy how users "experience" an app or site. Understanding CSS in general is obviously important. Newer developers should take time to really dig into how CSS works. As you progress, you'll want to dive into things like [Less](http://lesscss.org/) or [Sass](http://sass-lang.com/) preprocessing. I am personally a fan of Sass over Less, but that is just an opinion.

### HTML, Templates, and Markup
Understanding fundamentals of HTML mark up is the third piece of the Front-End-Trinity of Web. Understanding the basics of HTML, elements, and laying out a page is vital. Many colleges will likely teach this in its most basic forms (from the many people I have spoken with and personal experience). This will drive your understanding of templating languages.

Templating languages can vary from framework to toolset. This isn't a must, but it is definitely something you will see pop up.

Angular uses its own templating system as does React's JSX syntax. You can also checkout [Jade](http://jade-lang.com/) as a template engine as well.

#####Documentation and Comments
This might be one of those iffy's poeple may argue about, but overall documentation and commenting is important in all programming languages, technical skills, etc. It is what keeps collaboration and ease of access alive in development. Although this is probably never a mandatory anywhere, it is a great base skill set to have when developing. Starting out with the habit of commenting your code cleanly



#### Other Noteable Notes
- Package Managment is very convenient and widely used. Learning [npm](https://www.npmjs.com/) & [bower](http://bower.io/) will help a lot when handling dependencies and building out applications
- Node.js and io.js are powerful platforms for building applications and are common when using build systems
- [grunt](http://gruntjs.com/), [gulp](http://gulpjs.com/), and [webpack](http://webpack.github.io/) are three very popular build systems. I am most familiar with gulp and just started (and very much liking) webpack. 
- Use [google](www.google.com) (yes, I linked to google.com =P ) and [StackOverflow](www.stackoverflow.com). Look up stuff as much as you need to see how other developers have solved issues.
- Do tutorials and try new things. Tutorials are a great way to just get your hands dirty. However, try branching out and doing more than what tutorials have you do. Make everything your own piece of work and really learn what exactly you are doing. I don't know how many times I have done a tutorial, gone through the motions, and ended up realizing I don't remember what I did. 
- [Bootstrap](http://getbootstrap.com/) and [Foundation](http://foundation.zurb.com/) are very common FE-Frameworks to get you started with basic UI components. Use and customize them as needed. (these are old so probably don't matter anymore)

####Quick Start Ends Here
The quick start may end here, but there is still much to learn. I'll eventually add more (to include a glossary) of topics and directional points like build systems, automation, package bundling, npm and more later. 

Once again, these are things that I have found to be helpful in my journey as a developer. This is meant to be as a reference point to help new developers with the question, "How do I start and what do I learn or do?". If you have questions, ask me. If you would like to add and modify this, feel free to make a PR!!

