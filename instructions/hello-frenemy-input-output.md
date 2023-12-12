# Instructions

This exercise is similar to the `hello-frenemy.js` lab completed earlier in the course.

However, now you will now use `readline` and the `ask` function to get the name to respond to.

---

Create a program that:

- Gets a name from INPUT, using `readline` and the `ask` function
- Forcefully rebukes the name IF they are an enemy like:
  - 'darth vader', 'voldemort', 'palpatine', or 'lex luthor'
- Otherwise, greets a person warmly with their name as a friend.
- IF the name is exactly 'darth vader', reply 'Noooooo! That's impossible!'

## Example

```js
let enemyList = ['darth vader', 'voldemort', 'palatine', 'lex luthor'];

function respond(name) {
  if (/* the name is an enemy */) {
    /* check if their name is 'darth vader' */
    /* tell them to go away */
  } else {
    /* greet them warmly by their name */
  }
}
```

```txt
// Output
What is your name?

// Input
darth vader

// Ouput
'Noooooo! That's impossible!'
```
