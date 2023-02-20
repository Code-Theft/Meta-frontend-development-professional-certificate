### 1. What is the purpose of the useState hook in React?

- [ ] To build a value to the project of a component.
- [x] To manage the component's state
- [ ] To manage the component's context
- [ ] To bind an event handler to an element

### 2.What is missing from the code below?
```
import { useState } from "react";

export default function App() {
  const [restaurantName, setRestaurantName] = useState();
  return <h1>{restaurantName}</h1>;
}
```

- [ ] `useReducer` hook was not used
- [ ] The `useState` hook import statement
- [ ] The `setRestaurantName` function
- [x] An initial value for the state variable `resturantName`

### 3. Controlled components keep their internal state in the DOM.

- [ ] True
- [x] False

### 4. What is Unit Testing in React?

- [ ] A type of testing that involves manually testing a component's UI
- [x] A type of testing that ensures that individual units of code are working as intended.
- [ ] A type of testing that ensures that a complete application is working as intended.
- [ ] A type of testing that ensures that a component's props and state are correctly being passed down to its children.

### 5. What is the main difference between the useState and useReducer hooks in React?

- [x] `useState` is used for simple state updates, while `useReducer` is used for complex state updates.
- [ ] `useState` is used for managing component state, while `useReducer` is used for managing the component's UI.
- [ ] `useState` is used for managing component state, while `useReducer` is used for managing the component lifecycle.
- [ ] `useState` is used for managing component state, while `useReducer` is used for managing global state.

