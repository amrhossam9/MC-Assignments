# Name: Amr Hossam Mohamed Younes

## React Native To-Do List

### **Introduction**
This report provides an analysis of a React Native To-Do List application. The application enables users to add tasks to a list dynamically using a simple user interface.

### **Screenshot**
<p style="border: 2px solid black; display: inline-block;">
    <img src="./Pics/Pic01.png" alt="Screenshot" width="250">
</p>

### **Code Overview**
The application is implemented using React Native. It utilizes functional components and hooks to manage state and user interactions.

### **Functional Components**
1. **State Management:**
   - `useState` is used to manage the list of tasks (`tasks`) and the current input value (`newTask`).
   
2. **Event Handling:**
   - `handleInputChange`: Updates `newTask` whenever the user types in the input field.
   - `addTask`: Adds the entered task to the list if it is not empty and clears the input field.

3. **Rendering UI Elements:**
   - `TextInput` is used for user input.
   - `Button` is used to trigger the addition of a new task.
   - `FlatList` displays the list of tasks dynamically.

### **Key Features**
- **User-friendly Interface**: The application provides a simple and clear layout for task management.
- **State Management with Hooks**: `useState` ensures efficient state updates.
- **Dynamic List Rendering**: `FlatList` ensures optimized rendering of the to-do list.
- **Minimalistic and Readable Code**: The component structure and function names make the code easy to understand and maintain.