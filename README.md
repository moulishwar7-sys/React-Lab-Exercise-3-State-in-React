# React-Lab-Exercise-3-State-in-React

## Name : Moulishwar G
## Register Number : 2305001020

# Aim
To create a simple React application that demonstrates the use of State using the useState() Hook.

# Program:
## App.jsx 
```python
import { useState } from "react"; 
function App() { 
 const [count, setCount] = useState(0); 
 const [name, setName] = useState("Moulish"); 
 return ( 
 <div> 
 <h1>React State Example</h1> 
 <h2>Student Name: {name}</h2> 
 <button onClick={() => setName("Madhu")}> 
 Change Name 
 </button> 
 <hr /> 
 <h2>Count: {count}</h2> 
 <button onClick={() => setCount(count + 1)}> 
 Increase 
 </button> 
 <button onClick={() => setCount(count - 1)}> 
 Decrease 
 </button> 
 </div> 
 ); 
} 
export default App

```

# Output:

<img width="538" height="395" alt="image" src="https://github.com/user-attachments/assets/c7d094db-304e-4b6d-ab9a-949b5807955b" />

