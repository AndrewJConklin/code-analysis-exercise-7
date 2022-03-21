# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (a, b, margin){
  if (!margin){
    margin = 0
  }

  if (a < b - margin){
    return -1
  } else if (a - margin > b){
    return 1
  } else {
    return 0
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input                                           | Output |
| (1, 2, 5)   | 0      |
| (3, 10, 3)  | -1     | 
| (10, 2, 3)  |  1     | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program takes in 3 inputs: a, b, and margin and returns a single value (either -1, 1, or 0). If a is less than b - margin, then the function returns -1. If a - margin is greater than b, then the function returns 1. If Neither of the prior 2 expressions are true, then the function returns 0. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
