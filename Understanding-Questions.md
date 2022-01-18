# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.

1) calls the addOne action function
2) calls reducer ADD_ONE case
3) gets updated total (total: state.total + 1 ) from the reducer
4)rerenders the display with updated total from state
...

* TotalDisplay shows the total plus 1.
