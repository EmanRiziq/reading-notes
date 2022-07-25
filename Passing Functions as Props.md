## Lists and Keys

### What does .map() return?
the new array from the function

### If I want to loop through an array and display each value in JSX, how do I do that in React?
You can build collections of elements and include them in JSX using curly braces {}.

### Each list item needs a unique ____.
key

### What is the purpose of a key?
to identifi a list item among its siblings. 

## The Spread Operator
### What is the spread operator?
 spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
### List 4 things that the spread operator can do.
1- adding items to arrays
2- combining arrays or objects
3- spreading an array out into a function’s arguments
4 -

### Give an example of using the spread operator to combine two arrays.
*the image not rendering*

### Give an example of using the spread operator to add a new item to an array.
```const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```

### Give an example of using the spread operator to combine two objects into one.
```const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩 ```
