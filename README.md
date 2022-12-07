### Goal: Write your own “documentation” for the higher order functions
**Your documentation should include:**
- A description of the purpose
  * A higher order funtion is a function that takes in another function as an argument and sometimes returns a function.
- A description of the syntax
  * We declare a function using a variable
  * We take in two parameters where one argument is a function
  * Within the brackets we have our code
- An example
```js
  const jacqueline => (music, code){
    return code(music);
  }
  const printLoudly = x => console.log(x + "!!!");
  jacqueline("a", console.log);
  jacqueline("a", printLoudly);
  let musicalNotes = ["note1","note2"];
  const shaina => (jazz,music){
    return music(jazz[i]);
  }
  shaina(musicalNotes,console.log);
```
- An explanation of the example
We took in two parameter and added them together and returned it
- Any additional notes/details
---
Your documentation here:
