WIP 


# 1. Describe (in plain English) what Array.map() does
* Array.map() iterates over, and runs a function for, each element in an array. 

# 2. Describe (in plain English) what Array.reduce() does
* It iterates over an array, invokes a callback on each element, and returns an accumulator calculated from the previous iteration. 

# Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

With normal Promise .then() syntax

``` Plaintext

superagent.get('apiurl')
 .then(data => {
   console.log(data)
 })
 .catch(error => console.error(error));

```
Again with async / await syntax

``` Plaintext

async function suuuuper() {
  let data = await superagent.get('apiurl');
  console.log(data);
}

suuuuper();


```

# 3. Explain promises as though you were mentoring a Code 301 level student. 
* A promise is essentially telling JavaScript "Hey, do this thing! Take the time you need. I'm going to do other stuff. Give me your answer when you're done working, and I'll handle the rest."

# 4. Are all callback functions considered to be Asynchronous? Why or Why Not?
* Not by default. They can be both synchronous and asynchronous depending on the how they are called. 