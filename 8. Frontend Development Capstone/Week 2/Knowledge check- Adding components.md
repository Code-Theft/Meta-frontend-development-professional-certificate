### 1. Choose the correct statement about the following code:
```
<>  

    <h1>...</h1>  

    <p>...</p>  

</> 
```

- [ ] This is a valid HTML tag
- [ ] This is not valid React code
- [ ] This is valid JavaScript code
- [x] This is valid React code.

### 2. In React, you can only have one root element in a component.

- [ ] True
- [x] False

### 3. Which of the following statements are true about JSX? Choose all that apply. 

- [x] JSX elements can have multiple children.
- [ ] JSX elements must be self-closing.
- [x] JSX allows you to include expressions in your code.
- [x] JSX allows you to use JavaScript functions as attributes

### 4. What is the output of the following JSX code block?
```
const myList = ['apple', 'banana', 'orange']; 

const listItems = myList.map((item) => 

  <li key={item}>{item}</li> 

); 

return ( 

  <ul>{listItems}</ul> 

); 
```

- [ ] `[<ul>,<li>apple</li>, <li>banana</li>, <li>orange</li>,<ul>] `
- [ ] `<ul> [<li>apple</li>, <li>banana</li>, <li>orange</li>] </ul>`
- [ ] `<li>apple</li><li>banana</li><li>orange</li>`
- [ ] `<ul><li>apple</li><li>banana</li><li>orange</li></ul>`

### 5. Which of the following is true about props in React?

- [ ] The prop value must be wrapped in quotes.
- [x] Props should be used for values that will not change within a component.
- [ ] Props should only be used for simple data types, such as strings and numbers
- [ ] Props are mutable and can be changed within a component.
