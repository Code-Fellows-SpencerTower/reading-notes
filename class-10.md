# JS

## Chapter 10: Error Handling and Debugging (pp.448)

- Execution contexts
  - global context
  - functon context
  - eval context
- Two phases of execution context: 1. Prepare 2. Execute
- Variable scope
  - global scope
  - function-level scope
- execution is not always linear - some tasks must be executed before others will trigger (i.e. functions)
- Stack:
  - .js interpreter processes each line of code, stacking occurs when a line of code needs data from a function (it has to jump to another place in the code to retreive data to run that line)
  - the new function gets 'stacked' on the current line being processed
- *lexical scope* - functons linked to the object in which they were defined
  - making scope the vars in the current context and vars in parent context
- use the console to find the area of code where the error occurs
- there are 7 types of errors in JS
- use `try`, `catch`, `finally` in code to catch and handle an error