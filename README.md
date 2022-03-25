# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
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

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|       |        | 
|       |        | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td></td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible


## Inputs and Outputs

| Input | Output|
| :---: | :---: |
|```js user.Tiffany = {isActive: true, username:"twarre30"}``` | Welcome back, Tiffany! |
| user.Jamey = {isActive: true, username:"tuday"} | Welcome back, Jamey |
| user.Brad = {isActive: false, username:"bslagle"} | Hey Brad! Would you like to renew your subscription? |


## Tiffany


```js
 
function (user){					// Tiffany
  if (user.isActive){					// true
    return `Welcome back, ${user.username}!`		// Welcome back, Tiffany!
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`  // does not run
  }
}

```

## Jamey


```js

function (user){                                        // Jamey
  if (user.isActive){                                   // true
    return `Welcome back, ${user.username}!`            // Welcome back, Jamey!
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`  // does not run
  }
}

```

## Brad


```js

function (user){                                        // Brad
  if (user.isActive){                                   // false
    return `Welcome back, ${user.username}!`            // skips
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`  // Hey Brad! Would you like to renew your subscription?
  }
}

```

## Summary

This functions determires if a user is active and if so says Welcome and if not active asks if you want to renew.


 












 
