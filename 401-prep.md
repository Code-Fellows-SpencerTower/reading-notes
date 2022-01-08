# 401 Prep Readings

[How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

- “Measure twice, cut once”
  - Resist the urge to start coding as soon as possible
- Take the time to understand the problem completely before trying to solve it
- Be able to explain the problem to someone else before you attempt to solve it
  - Read it 2-4x
- Dont try to “oversolve” the problem on your first iteration
  - keep it simple
- Solve with 3 different inputs
  - Make sure the solution works with more than one input
- Cut larger / more complex problems in half
  - Use same steps on each half

Recommended steps:
1. Read the problem completely twice.
2. Solve the problem manually with 3 sets of sample data.
3. Optimize the manual steps.
4. Write the manual steps as comments or pseudo-code.
5. Replace the comments or pseudo-code with real code.
6. Optimize the real code.

[How to think like a programmer — lessons in problem solving](https://www.freecodecamp.org/news/how-to-think-like-a-programmer-lessons-in-problem-solving-d1d8bf1de7d2/)

- have a framework for solving problems and practice using it
- problem solving is prioritized among employers
- problem solving is just as valuable as technical ability
- practice problem solving to get better at it

1. Understand 
    - be able to explain the problem out loud in simple terms
    - write it down or explain it to someone

2. Plan
    - write down the steps for solving first (eg pseudo code)

3. Divide
    - break the problem into sub-problems
    - solve each one, starting with the simplest problem
    - connect the dots between the sub-problems to complete the larger problem

Debug
- Be curious about bugs rather than frustrated
- go step-by-step through code to find the problem
- take a step back and look at it from a more general perspective

[5 Whys - Getting to the Root of a Problem Quickly](https://www.mindtools.com/pages/article/newTMC_5W.htm)

- developed by the founder of Toyota, Sakichi Toyoda
- when there is a problem, drill down to the root of the problem by asking "Why?" 5 times
- uses "counter-measures" rather than solutions
- "counter-measures" seek to prevent the problem from arising again
- 5 Whys are useful for simple to moderately difficult problems, ot necessarily complex problems
- asking "Why?" 5x allows you to track down the root of the problem through multiple lines of questioning

Steps:
1. Assemble Team
2. Define Problem
3. Ask the First "Why?"
    - answer must be based on what has actually happened to cause the problem, not speculation
4. Ask "Why?" Four more times
5. Know when to stop
6. Address the Root Cause(s)
    - decide on counter-measures
7. Monitor Counter Measures
    - track how effective counter-measures have been at preventing the problem from recurring

[What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ&ab_channel=JSConf)

Javascript runtime - V8 Chrome
Heap - where memory allocation takes place
Stack > WebAPIs > Callback Queue > Event Loop > Stack
- JS is a single-threaded programming language, so it has a single call stack
  - it can only do one thing at a time
Blocking - "slow" code in the stack
Browser is constrained by what your doing in JS
- cant do a render if there is code on the JS stack
  - render is "blocked"
  - putting too much slow code on the stack will block rendering
- queueing asynchronously frees the stack and allows the browser to render between each element


[The Super Mario Effect - Tricking Your Brain into Learning More](https://www.youtube.com/watch?v=9vJRopau0g0&ab_channel=TEDxTalks)

- 2.5x more attempts and higher success rate for study participants who were not penalized for failing to solve a puzzle
- Super Mario Effect - treating life's challenges like video games
- focus on beating the game rather than mistakes made
- "Life gamification" - framing the process as a game, you are more likely to keep trying/learning
- fear of failure is removed from the process and learning happens more naturally
