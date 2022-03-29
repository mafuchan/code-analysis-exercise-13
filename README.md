# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}

```

| Input               | Output           |
| -----               |------            |
|  "Matt", "Crecraft", 42 | { firstName: "Matt", lastName: "Crecraft", age: 42 } | 
|  "Anna", "Crecraft", 39 | { firstName: "Anna", lastName: "Crecraft", age: 39 } | 
| "Daniel", "Crecraft", 10| { firstName: "Daniel", lastName: "Crecraft", age: 10 } | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function takes the input of firstName, lastName, and age and the output of 'person' returns the full name and age.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
