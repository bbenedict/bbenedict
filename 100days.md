### 100 days of ~~coding~~ learning

I'm doing something along the lines of the 100 days of coding project. 
Instead of coding a single project, I hope to explore different areas
like development enviroments, technologies and languages.  So maybe I
should call it 100 days of learning something technical.

These are my areas of focus

* ML/AI
  * Coursera ML/AI courses
  * O'Reilly Python Machine Learning books
* React/UI/UX
  * D3js
  * React 16/17 exploration of hooks, performance, accessibility and other areas
* Full stack 
  * React/Express/Node/Mongo (otherwise known as the project that will never be done)
  * React + GraphQL 
* And now for something completely different (expect to see these around day 80 or so)
  * Smalltalk best practices
  * A console in Rust
  * Clojure or Elm or Haskell or ...
  
## day 1

Linked my github repo to [codesandbox.io](https://codesandbox.io) and started two projects.  Second project was a react app where I installed styled-components to observe the package life cycle and understand the IDE better.  

## day 2

It's time for my next programmng assignment from [Coursera Machine Learning](https://www.coursera.org/learn/machine-learning).  "Now you will implement the cost function and gradient for the neural network".  I completed the cost function today and will tackle the gradient next.  There is a HUGE difference in learning between auditing the course versus doing all the programing exercises.  The course is taught by [Andrew Ng](https://www.andrewng.org/), who is an Adjunct Professor from Stanford.  I highly recommend this course and Professor Ng.  I am also doing all my assignments in MATLAB using [MathWorks](https://www.mathworks.com/), which is another interesting online development environment.

## day 3

"Now, you will implement the backpropagation algorithm."  Assignment complete for backpropagation and gradient checking.  Time for egg nog...

## day 4

Happy Holidays to everyone around the world!  We exchanged gifts this morning.  What I received pretty much changed my agenda for day.  Not sure this qualifies as learning but it is some serious fun. Who you gonna call? Legos&reg; [Ghostbusters™ ECTO-1](https://www.lego.com/en-us/product/ghostbusters-ecto-1-10274)

<div>
<img src="./IMG_2669.jpg" alt="Legos Ghostbusters box|" title="Legos Ghostbusters box" height="200" />
<img src="./IMG_2667.jpg" alt="Legos Ghostbusters assembly in action|" title="Legos Ghostbusters assembly in action" height="200"/>
 </div>

## day 5

Jumped back into https://codesandbox.io to play with the useReducer hook in React.  This hook is a convenient way to introduce a local reducer within a component.  It's recommended as, "preferable to useState when you have complex state logic that involves multiple sub-values". [See the docs here](https://reactjs.org/docs/hooks-reference.html#usereducer).  useReducer seems very helpful, but I am not sure I would use it if I already had redux in place.  Then again, I have many examples of useState and redux in use in the same components, so why not?

## day 6

Completed a programming exercise for [Coursera Machine Learning](https://www.coursera.org/learn/machine-learning) studying models with different bias and variance properties.  Very interesting developing intuitions for what might be wrong with various models.

## day 7 

Starting a new simple-react app on my desktop using Visual Studio.  I know many people use a pre-packaged framework as a starting point, but I prefer to take an existing app and hack out all the existing features and data.  That's the main reason I am using react 16 here.  I'll be using simple-react to explore topics like accessibility and performance.  Today is more about house keeping to get a base app running.

## day 8 

Added redux to simple-react app.  Just about ready to start accessibility testing.

## day 9

First round of accessibility changes on simple-react app.  These changes were driven by the Lighthouse report in Chrome available in the devtools.  Simple changes including better contrast for colors, using alt text for all images and labels on all input fields.

## day 10

Resuming Coursera Machine Learning to stay on track with the course schedule.  I did some work with Support Vector Machines (SVM) using them with Gaussian kernals.  I then completed a few spam classification problems designed to be used with SVM.  4 more weeks of classes to go!

## day 11

Explored useContext with React today.  Yet another way to pass data between components in the component tree.

## day 12

Made good progress on the Coursera Machine Learning course over the holidays.  I am actually a little ahead of schedule right now.  The coding work today covered two areas.  I implemented parts of the K-means Clustering algorithm. I then used Principal Component Analysis(PCA) to perform dimensionalty reduction.  And finally, I topped the day off by completing my Legos&reg; [Ghostbusters™ ECTO-1](https://www.lego.com/en-us/product/ghostbusters-ecto-1-10274) project.
<div>
<img src="./IMG_2675.jpg" alt="Legos Ghostbusters box|" title="Legos Ghostbusters car complete" height="200" />
</div>

## day 13

Some experiments with useMemo in React.  The code is working, but I am pretty sure I am not taking full advantage of the useMemo hook and it's ability to return a memoized value.  Will revisit at a later date, hopefully with a better use case.

## day 14

Accessibility improvements for the simple-react app.  Adding regional tags such as header and nav to improve the screen reading experience.  I am using VoiceOver on Mac to validate changes.  This is a VERY eye opening experience.  You are trying to navigate from say a Chrome browser tab to your application, and every key you press causes an audio snippet to begin playing.  I really wanted to take my headphones off while learning as a result, but that defeats the purpose of this learning.

## day 15

Created a custom hook in the codesandbox-react app.  I also came up with a better example for useMemo that works more as expected.

## day 16

Added eslint and a11y rules to the simple-react app.  Put in the obvious rules first like alt text and links with href.  I'll add more to the rules as I add more support for accessibility in this app.

## day 17

I coded a more complex scenario for accessibility adding support for a chart.  Think of this as a complex image that requires a secondary or contextual explanation.  The W3C provides an excellent [tutorial for handling complex images](https://www.w3.org/WAI/tutorials/images/complex/). My ability to navigate with VoiceOver is improving, though I still have a long way to go to feel comfortable relying on voice only for interacting with websites.  A very educational experience.

## day 18

Supporting font size scaling for the visually impaired in simple-react app.

## day 19

Working on my last programming assignments for Coursera Machine Learning.  After this, I just have a two weeks of lectures to complete to finish the course.  Today I am working on Anomaly Detection.  The task is to estimate the parameters &mu; and &sigma;<sup>2</sup> for a Guassian distribution of a matrix of features.

## day 20

I implemented parts of a Collaborative Filtering system for recommendations.  The specific work was to produce a vectorized implementation for calcualting the gradient of a cost function given a matrix of users x features and movies x features.  As of today, I have completed all programming assignments for Coursera Machine Learning.  QED!  

## day 21

Time to open up a new thread for learning.  I'm starting the O-Reilly book Introduction to Machine Learning with Python.  We'll see how much the Coursera ML course helps with better understanding what's happening behind the scenes of some of these libraries.  First day of learning is all about spinning up the IDE, in this case Jupyter Notebooks.  Got stuck in pip install hell for a while.  Installs unrelated to this project pushed me to python 3.8 (thanks a lot AWS CLI) and it took me a while to get the right scikit-learn, numpy, pandas versions for my version of Python and Mac OSX.  Trained a simple model today so hopefully those issues are behind me.

## day 22

Finished the linear regression models from the O-Reilly book.  Trying to create Jupyter notebooks that might act as a real time reference in the future.

## day 23

First attempt at k-means clustering.  Working example but needs some clean up.

## day 24

Cleaned up...

## day 25

Worked with some more examples from the O-Reilly book Introduction to Machine Learning with Python.  I also decided to set up a notebook page dedicated to plots and graphs to consolidate specific examples with unique attributes or methods for creating the images.

## day 26

No coding today but I am pretty sure this counts as learning.  
<div>
<img src="./bob-benedict-stanford-ml.png" alt="Certificate of Completion, Machine Learning, Stanford Online, Coursera" title="Certificate of Completion, Machine Learning, Stanford Online, Coursera" height="300" />
</div>

## day 27

Spent some time testing more features of CodeSandbox.  I wanted to explore the full developmnt life cycle a bit more by adding automated tests to my test app.  They use Jest, which worked fine for my purposes.  

## day 28

Started work on Suport Vector Machines in the python O-Reilly repo.  Just have the basics working for now.

## day 29

More accessibility changes in simple-react app using the html attributes role, aria-label, h1 header properly.  I think I am pretty close to have a strategy to improve accessibility in our application.  Next step is to schedule a "brown bag" discussion.

## day 30

Had to segue into elasticsearch land for today's entry.  Fixed some issues with our scripts that reload search indexes.  

## day 31

... and then I had to do some mysql work to fix some anomolies in our database.  

## day 32

Although this is not listed in my initial list, I've wanted to explore git-flow more in depth especially the use of release branches.  I've primarily used feature branches merged into develop and then main for my team projects, along with hotfix branches as needed.  I used a temp repo and created various "feature branches" to see how it all works. 

## day 33

Started work on Neural Networks from the ML/python O-Reilly book.  Today was mostly reviewing the parameters from the scikit libraries https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html

## day 34

Added the examples from O-Reilly including a new graph in the graphs and plots collection.

## day 35

Created a model parameter tester for scikit neural network classifier.  The tester iterates through the different solvers, confgiruations for hidden layers, and other parameters to see what combination gets the best result on the test set.  Included also the worst result for ceiling analysis.  This should come in handy when I try other neural network libraris on the various datasets.

## day 36

Another segue day looking at my non-open source data set extracted from a MySQL database.  If you look what I did tomorrow, you'll see one of the changes I need to make to the data set for creating better models.

## day 37

More Python O-Reilly book examples this time exploring categorical data.  I also added some techniques to clean up the data that I learned in a basic Udacity class some time ago.  This work will come in handy when I resume working on my non-open source data set.

## day 38

Resumed work on the non-open source data set.  Converted the project to jupyter a notebook.

## day 39

Significant work on the non-open source data set.  Generating charts on answers provided by users.

## day 40

Now using dataframes to create graphs from questions that have the most responses from an account list.  This is going to come in very handy for deciding which questions are interesting to look at.

## day 41

I'm starting a new repo today: simple-node-graphql.  Could this be the challenge to REST that everyone is saying it is?  We shall see.  Seems like a simpler way to implement a server API by having a single endpoint and specfiying the data you need at time of request. 

## day 42

Deep dive into GraphQl docs to better understand how queries and resolvers work.  I really wish people who write blog posts would go beyond the level of detail provided already in the documentation (which is pretty good in this case).  And if you use the same name for your query, your resolvers and your data, the reader has to guess if those names mean the same thing and how each of these items are connected.

## day 43

Side tracked into SQL world for the old day job.  We may have found our first MySQL bug in the way the database chooses which index to use for query optimization.  I was able to figure out how to force an index on a JOIN.  Our problem is solved.  Need to figure out how to report a bug to Oracle.

## day 44

I was able to get back to my GraphQL work.  I finally have a working reference implemenation for the equivelent of REST GET with nested resources.  I also refactored the code to make it more clear how queries link to resolvers and data (see day 42).  For example, the query getUsers returns an array of UserObjects that includes the LocationObject for each user retrieved from the userList.

## day 44

Added principal component analysis (PCA) to Python O-Reilly book examples.

## day 45

Added cross validation to Python O-Reilly book examples.

## day 46

I am starting a new thread based on the learnings from GraphQL.  I really like the query language approach with a single end point on the server.  My plan is to leverage those concepts and adapt them to my approach to REST, which is built on Prototypal Inheritance in Javascript.  Part of this is also to work around some of the drawbacks or challeneges of GraphQL such as the N+1 problem and the lack of wildcard support in queries.

## day 47

Success!  I have a working implementation of a REST-based query language.  

## day 48

Cleaned up of my working implementation of my REST-based query language and uploaded to a privat repo for now.  The next set of problems to solve include authentication support, overriding the base services controller, and better error response.  Then I need to build a Reactjs client that leverages the approach.  Is it possible to define a model on the server and have all the connections automatically made such that client queries just work?  We'll see.

## And then life happens...

I had one of those interruptions that forces you to put all your side projects on hold until the ship is righted.  One of the things I was looking forward to upon resolving the situation was resuming my 100 days of learning.  And so, without further ado...

## day 49

I resumed work on my REST-based query language by implemention a react client that queries the server.  First version works pretty well.  I am optimistic this is a good approach.

## day 50

Re-factoring of the client and related server work.  Now supporting object creation from the client.

## day 51

Before my "life happens" interruption, I had started reading about sentiment analysis in the O-Reilly book Introduction to Machine Learning with Python.  I swicthed back to that work to finish what I started.  The implementation was a simple "bag of words" approach.

## day 52

Added better logging to the server side of the REST-based query language project.

## day 53

I spent some time with data transformation and scaling using the O-Reilly book.

## day 54

Created a few example scikit-learn pipelines based on examples in the O-Reilly ML Python book.

## day 55 

Started a new thread of learning today!  I am leaning D3.js using Amelia Wattenberger's *Fullstack D3 and Data Visualization*, which is sponsored by Fullstack.io.  I spent most of the time setting up the sample repo, installing live-server and getting a basic chart working.  This book is extremely well written and the examples are very relevant.  I highly recommend you have strong Javascript skills to get the most value from the text.

## day 56

This day was a little more productive.  I worked through the scatter plot example.

## day 57

I did the bar chart example today.  D3.js creates charts by essentially creating an svg at run time.  I am surprised by how much of the chart is just svg objects versus something generated from JS libraries.

## day 58

Spent some time on animations and transformations adding to existing D3.js work.  

## day 59

I jumped ahead in Amelia Wattenberger's D3.js book to look at how charts are created within a Reactjs application. The book recommends using Reactjs to render the svg objects instead of D3.js, which in turn becomes more of a powerful set of utilities to define scales and do other operaions.  Now that is a bit of a surpise.  I am much more likely to create charts in Reactjs than not.  I'll do the remaining examples in Reactjs instead once I refactor the current app a bit.

## day 60

Switched the server config for D3.js in React to use webpack-dev-server.  The server is launching and rendering a simple scatter chart with just the circles.

## day 61

Re-factored the app with the goal to simplify chart generation.  In truth, this was not a very productive effort.

## day 62

A much more productive effort on re-factoring the scatter chart and the app as a whole.  Added axis and labels.

## day 63

Added a bar chart to the D3.js app in React.  The method used in the book D3.histogram() was replaced by D3.bin().  I also figured out how to control the number of bars.  D3 makes smart guesses for how many bars to use, which makes sense for a histogram but less so for a straight bar chart.

## day 64

Made a quick seque to cypress.io to explore client side testing for a React app.  I suspect cypress.io will replace some of the other threads of learning I proposed as the start of this project.

## day 65

More exploration of cypress.io.  I am debating how to handle service responses for a React app that uses Node/Express for the backend.  Approach A, use stubs.  Approach B, use seed data and run the server in test-ci mode.  We'll see what I ended up recommending.

## day 66

Resuming my exploration of D3.js, I started work on a doughnut chart.  We use these a lot in our application.  I was able to get a basic chart displayed but I need to refactor to the code (as usual) to make it more clear what is happening.

## day 67

A nice productive day refactoring a doughnut chart using D3.js in a React app.

## day 67

I created a custom doughnut chart using D3.js that displays a single value percentage like you might see in a dashboard.

## day 68

Delved into Rust for a few hours.  This was a nice introduction to the language, but I think I am going to shelve this thread for now.

## day 69

I did some more work with cypress.io.  For the back end, I brought up a server with seed data.  Seed data replaces the typical fixtures for test data.  My login spec is working.  Running a server with seed data will work well for development, but I am concerned it won't slot into CI as well as we need it to.

## day 70

Another side bar, this time back to accessibility.  I am really going through the details now of what it takes to make a full accesible e-learning app.  I watched sereveral videos on YouTube of people with disabilities using screen readers.  All my teams are going to understand accessibility going forward.

## day 71

Amelia Wattenberger wrote another fantastic blog post about her approach to [using D3.js with Reactjs](https://wattenberger.com/blog/react-and-d3).  I wouldn't be surprised to see an update to her book *Fullstack D3 and Data Visualization*.  She uses the Reactjs hook useRef to access the SVG object which then enables more of the D3.js libary.  I re-wrote two of my charts to use this approach.  

## day 72

I resumed my cypress.io work to solve the CI vs. server challenge.  I am trying to write one set of tests, exercising the interface through navigation and interaction, that work with stups or with a server (see day 69).  Turns out the cypress.io stub feature requires you to simluate the calls for GET and POST, which means your tests are not using their navigation methods like visit and click as much.  Miragejs seems like the right solution.  You intercept HTTP calls by defining routes and from there return your mocked data.  The code needs some re-factoring.  When doesn't it?  But I think at this point I have a solution that enables us to run client side tests with a server, which is better for integration tests, and without a server, which is better for CI.

## day 73

I dabbled with another one of the langauges listed in my original goals.  This was interesting.  But the learning curve to appreciate the benefit of the language felt longer than I wanted to spend.  I might have to re-think how to spend my last 25+ days on this project.

## day 74

Experimented with performance tools using the simple react app.  Was interesting and something I can definitely use in future apps.

## day 75

Found one potential solution to the last 25+ days challenge.  Blockchain!  I started working through various python tutorials.  This is fascinating stuff.

## day 76

My second day of blockchain experimentation.  I understand the basics of how it works.  But I feel like I am missing the security aspects and how the integrity of the chain is maintained.

## day 77

I made significant progress on my blockchain implementation.  I added digital signing and also validation of the hashes.  I'm far enough along to create a new repo to capture my work.  Something tells me this is an area I will continue to learn more and more about.

## day 78

Had to do a research on research day to find my next source of learning.  I ended up on is Tensorflow and the Keras api.  Back into neural nets we go.

## day 78 

I found a fantisic course on Keras and Tensorflow on YouTube.  It was sponsored or creatd by [DeepLizard](https://deeplizard.com/) and listed on YouTube as part of (FreeCodeCamp.org)[https://www.freecodecamp.org/]. You'll find the course here: [Keras with TensorFlow Course - Python Deep Learning and Neural Networks for Beginners Tutorial](https://www.youtube.com/watch?v=qFJeN9V1ZsI&t=1791s).  It's very well done.  I recommend it if you are starting out with Tensorflow and Keras.

## day 79

Day two of the YouTube course Keras with TensorFlow Course - Python Deep Learning and Neural Networks for Beginners Tutorial.  Covered more training and testing, with cross validation, and plotting everything in a confusion matrix.  I should be able to complete everything in one more day.

