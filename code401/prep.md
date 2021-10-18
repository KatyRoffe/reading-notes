# 401 Prepwork

## [How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

- Simple Steps (spend most of the time working through steps 1-3)
    1. Read the problem through completely. **At least twice.**
        - make sure you can explain the problem to someone else
        - the better you understand the problem, the easier it will be to solve it
    2. Solve the problem manually with sample data. **Use three sample sets.**
        - by first solving a problem manually, you know what you will be automating later
        - write down every single step no matter how small
        - for example, to reverse a string, writing down each character in that string would be a separate step
    3. Optimize the manual steps.
        - if there are steps that can be combined into a single action, figure out how to do that here
    4. Write the manual steps as comments or pseudo-code.
        - this outlines the structure of the code based on optimized steps
    5. Replace these comments/pseudo-code with real code.
        - figure out the syntax that would best execute the comments/pseudo-code
    6. Optimize the real code.
        - make sure variables are named meaningfully, get rid of duplications, etc
        - basic refactoring

# [Act like you make $1000/hr](https://medium.com/swlh/pretend-your-time-is-worth-1-000-hour-and-youll-become-100x-more-productive-f04628bb3e6d)

- busy doesn't necessarily nmean productive
- most business is distraction and procrastination
- be focused: have a clear vision of your goals and make tangible steps towards what matters in your life
- do what matters with hard focus, but do less of it. don't stay up late working and being stressed
- don't tolerate distractions - produce great quality in a short amount of time

# [How to think like a programmer](https://www.freecodecamp.org/news/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2/)

- Have a framework and **practice** it
    1. **Understand** exactly what is being asked
    2. **Plan** out the exact steps of the solution
    3. **Divide** the one big problem into smaller sub-problems
        - solve one by one
        - start with the simplest (the one you are the closest to answering already)
        - then solve the problems that don't depend on others being solved
        - solve the remainder
        - connect the dots
    4. **When Stuck** take a breath
        - be curious, not irritated, about why the code doesn't work
        - debug: go step by step to see where the code went wrong
        - reassess: return to the general as opposed to the abstract if necessary
        - research: someone else has already solved the problem you're working on, go find out what they did
    5. **Practice!**
        - no one gets better without practice
        - a little struggle is good: it helps us learn
        - find ways to problem solve everyday

# [The 5 Whys](https://www.mindtools.com/pages/article/newTMC_5W.htm)

- When a problem occurs, find the root cause by asking "why?" five times
- When a counter-measure occurs, follow it through to prevent the issue from recurring

    1. Assemble a team
    2. Define the problem
    3. Ask the first Why
        - why is this problem occuring?
        - make the answers grounded
    4. Ask why four more times
        - do this for every answer provided for the first why
    5. Know when to stop
        - when the root cause is found, useful responses are not easy to come by when asking why
    6. Address the root cause
        - figure out the counter-measures
    7. Monitor the measures
        - see how effectively they eliminate or minimize the initial problem and prevent it from recurring

# [The Super Mario Effect](https://www.youtube.com/watch?v=9vJRopau0g0)

- a fear of penalizing failure often results in a negative impact in learning
- focusing on the endgoal regardless of the amount of times it takes allows for a change in learning experience
- the super mario effect allows someone to focus on the princess and not the pits
- reframing the learning process to focus on the endgoal helps to allieviate the fear of failure and makes learning come more naturally

# [What the Heck Is the Event Loop?](https://www.youtube.com/watch?v=8aGhZQkoFbQ)

- JS is a single-threaded programming language
  - it has a single call stack (it can do one thing at a time)
    - the call stack records where we are in the program
- blocking
  - when things are slow
  - in a single call stack, there's not really a way to bypass slow portion of synchronous code
  - can fix this by using asynchronous code instead
- the event loop
  - looks at the call stack and the tasks queue
  - if the stack is empty - it grabs the first item in the queue to run it through the stack
