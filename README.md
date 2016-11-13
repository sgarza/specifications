# How to write software functional and technical specifications

This document is intended to be as the template and manual for an ongoing and ever changing process to solve problems for any project, everyone can participate and collaborate to expose examples, special cases and discuss.


Well-defined problems lead to breakthrough solutions. When developing new products, processes, or even businesses, most companies aren’t sufficiently rigorous in defining the problems they’re attempting to solve and articulating why those issues are important. Without that rigor, organizations miss opportunities, waste resources, and end up pursuing innovation initiatives that aren’t aligned with their strategies. How many times have you seen a project go down one path only to realize in hindsight that it should have gone down another? How many times have you seen an innovation program deliver a seemingly breakthrough result only to find that it can’t be implemented or it addresses the wrong problem? Many organizations need to become better at asking the right questions so that they tackle the right problems.


>If I were given one hour to save the planet, I would spend 59 minutes defining the problem and one minute resolving it,” **Albert Einstein**.


## Problem Discovery

When we try to solve business problems, we can often put pressure on ourselves to find solutions quickly.

The problem with this is that we can only partially solve the problem, or we can end up **[solving the wrong problem](https://hbr.org/2012/09/are-you-solving-the-right-problem/ar/1)**, with all of the delay, expense, and lost business opportunity that goes with this.

**[The Problem-Definition Process](/PROBLEM_DEFINITION_PROCESS.md)** encourages you to define and understand the problem that you're trying to solve, in detail. It also helps you confirm that solving the problem contributes towards the project's objectives.

This stops you spending time, energy, and resources on unimportant problems, future bugs, or on initiatives that don't align with the project's overall strategy.

## Modeling/Prototyping

This step is about discarding weird ideas that may not work and choosing the best one that fits into the constraints. The diagrams, your old tests, and your documentation on the system will be key here to keep you focused.
Remember to discard everything that doesn’t work with the problem definition. Not only does this help improve the quality of your final solution, but it also reduces complexity.

You may believe that a prototype is a bad implementation of the solution but you shouldn’t think of it that way. On the contrary, a prototype is a simplified system that proves if the component can be built, and if it will work for the final solution.

Try to make your prototype as simple and as standalone as possible, this will make easier to share and run your prototype. You can use services like [bl.ocks.org](http://bl.ocks.org/) or [codepen](http://codepen.io).

>**Tip:** Mock everything you can mock like database records or a library data-structure. If you mocked something and is not in your Product Definition > Assumptions, go back and add it.

Include a link or the code of the prototype, describe what it does and explain how to run it.


## Specification

The Specification is generally viewed by developers as the document that provides a solution to a problem, but this isn’t the case. The Specification is the **guide with which you build the solution**. It’s basically the result of all the previous work.

If you’re stuck in a part of the Specification, there is a high probability that you skipped or missed something in a previous stage, so go back and figure it out.


### Hypothesis

This is the foundation for your solution. It is a single sentence in which the solution is based. In some cases, it can be more than one sentence but keep it simple: it’s better to create more specs instead of trying to fit all into one.

* A hypothesis is an educated guess about how things work.
* Most of the time a hypothesis is written like this: "If _____[I do this] _____, then _____[this]_____ will happen." (Fill in the blanks with the appropriate information from your own experiment.)
* Your hypothesis should be something that you can actually test, what's called a testable hypothesis. In other words, you need to be able to measure both "what you do" and "what will happen."


### Solution Proposal

This is the general idea of the solution you came up with. It’s meant to be a small description of how the solution works.

* **Use a “Black Box” diagram** It helps get the general picture of your solution and how it interacts with other components.


### Functional Specification

This is a detailed version of the solution proposal. Here you should be using diagrams, mockups screenshots and text in an organized way that describes the different states, buttons or APIs on your solution. All the components and moving pieces of your solution should be specified. **Think of this section as the anatomy of the solution.**

* Include the challenges for the current system when implementing this solution.

### Technical Specification

This is the real deal. This is where you describe the steps to implement the solution with color codes, dimension sequences, algorithms, and protocols. Anyone following this part of the document should be able to implement the solution you created (assuming the right skills).


### Usage Examples/Snippets

Include one or more usage cases of your solution with actual code examples describing whats the expected result or output of the example.






