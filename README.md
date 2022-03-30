# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

|       Input      |                           Output                             |
| -----------------| ------------------------------------------------------------ |
|      { isActive: true, username: "BBBrisk"}     |                    Welcome back, BBBrisk!                      | 
|      { isActive: false, username: "JoeyBoy"}       |     Hey JoeyBoy! Would you like to renew your subscription?      | 
|      { isActive: false, username: "MarkeyMark"}    |    Hey MarkeyMark! Would you like to renew your subscription?    | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>
      This program checks if a given user is active or not and then returns a message with their username 
      based on the account's status. This is done by checking against an array called username which seems to be a subset 
      of the array entitled user
    </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
