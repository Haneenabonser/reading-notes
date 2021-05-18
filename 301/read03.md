## Passing Functions as Props 

**Lists and Keys**
- What does .map() return?
    - The map() method returns an entirely new array with transformed elements and the same amount of data.
- If I want to loop through an array and display each value in JSX, how do I do that in React?
    - Use JavaScript map() function and return the value, then use render to display each value.
- Each list item needs a unique key.
- What is the purpose of a key?
    - A “key” is a special string attribute you need to include when creating lists of elements, it helps React identify which items have changed, are added, or are removed.                   



**Spread Operator**
- What is the spread operator? 
    - Spread operator is the use of a syntax of three dots(...) followed by the array (or iterable*). It expands the array into individual elements. 
- List 4 things that the spread operator can do.
    - Copying an array
    - Concatenating or combining arrays
    - Using Math functions
    - Using an array as arguments
- Give an example of using the spread operator to combine two arrays.
    - const myArray = [`🤪`,`🐻`,`🎌`]
    - const yourArray = [`🙂`,`🤗`,`🤩`]
    - const ourArray = [...myArray,...yourArray]

- Give an example of using the spread operator to add a new item to an array.
    - const fewFruit = ['🍏','🍊','🍌']
    - const fewMoreFruit = ['🍉', '🍍', ...fewFruit]

- Give an example of using the spread operator to combine two objects into one.
    - const objectOne = {hello: "🤪"}
    - const objectTwo = {world: "🐻"}
    - const objectThree = {...objectOne, ...objectTwo}



**How to Pass Functions Between Components**
- In the video, what is the first step that the developer does to pass functions between components?
    - Create the function where he want to change the state inside.

- In your own words, what does the increment function do?
    - It increment the count inside the state by one.
- How can you pass a method from a parent component into a child component?
    - Using props.
- How does the child component invoke a method that was passed to it from a parent component?
    - Create another function inside the child component.