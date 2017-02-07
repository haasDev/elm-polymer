# The Rundown
1. What are Web Components
  * Why do we need web components. What are they looking to solve?
    1. Cut back on the amount of javascript we're sending. "Use the platform"
    2. Provide better encapsulation of styles and scripts
    3. Provide greater modularity - natively
  * Browser support
2. What is Polymer
  * What is it good at?
    1. Providing a simple API to build web components around. (Especially if you are familiar with Angular).
    2. Leverages the browsers native technologies
    3. small file size 32kb minified and gzipped.
  * Where does it fall short?
    1. Performance is near the bottom of all major frameworks
    2. Lacks a coherent architecture to follow
    3. Very small community and 3rd party options
    4. No error messaging -- Biggest downfall by far
  * according
3. How can web components help you in elm?
  * Ports : What are they and how to use them
  * how to use web components inside elm
  * Can help to abstract away difficult parts of an elm app while you are learning.
  * Web Component Open Source examples
    1. https://elements.polymer-project.org/
    2. https://vaadin.com/elements
4. How does elm help Polymer?
  * adds virtual DOM to really help with performance (elm's performance overall is outstanding)
  * Great architecture to follow for building out an app
  * Best error messaging you will find anywhere
5. Drawbacks of using Polymer and Elm together
  * Both have small selection of open source options (although Elm's is growing!)
  * less of your code is in elm introducing opportunity for runtime exceptions which of course you do not have in your elm code.
6. Resources
  * Elm Discuss - https://groups.google.com/forum/#!msg/elm-discuss/8Q2xwRh6UYc/vjmMxV4UCwAJ;context-place=forum/elm-discuss
  * Richard Feldman's talk - https://www.youtube.com/watch?v=ar3TakwE8o0
7. Q&A
