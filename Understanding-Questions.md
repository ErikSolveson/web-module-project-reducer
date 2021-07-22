# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
-

## response first the onClick looks for the handler I made then the dispatcher starts, then the addOne goes to actions and returns a string which is now the input for dispatcher. This then hits the switch statment that does my stateful logic and 'adds 1' to the state.total

...

- TotalDisplay shows the total plus 1.
