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
  * React 16 exploration of hooks, performance, accessibility and other areas
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

Accessibility improvements for the simple-react app.  Adding regional tags such as header and nav to improve the screen reading experience.  I am using VoiceOver on Mac to validate changes.  This is a VERY eye opening experience.  You are trying to navigate from say a Chrome browser tab to your application, and every key you press causes an audio snippet to begin playing.  I really wanted to take my headphones off while learning as a result, but that defeates the purpose of this learning.

## day 15

Created a custom hook in the codesandbox-react app.  I also came up with a better example for useMemo that works more as expected.

## day 16

Added eslint and a11y rules to the simple-react app.  Put in the obvious rules first like alt text and links with href.  I'll add more to the rules as I add more support for accessibility in this app.

