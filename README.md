## App Overview

Eat-N-Split is a React-based web application designed to help friends easily calculate and split bills after shared expenses (like dining out). The app provides a clean, intuitive interface for managing a friends list and tracking who owes what to whom.

## Key Features

### 1. **Friends Management**

- **Friends List**: Displays all friends with their current balance status
- **Add Friends**: Form to add new friends with name and avatar image
- **Balance Tracking**: Shows whether you owe money, are owed money, or are even with each friend
- **Visual Indicators**: Color-coded balance display (red for debts owed, green for money owed to you)

### 2. **Bill Splitting**

- **Bill Input**: Enter the total bill amount
- **Expense Division**: Specify how much each person paid
- **Payment Assignment**: Choose who is paying the bill (you or your friend)
- **Automatic Calculation**: App calculates the split amount and updates balances accordingly

### 3. **User Interface**

- **Two-Panel Layout**: Sidebar for friends list, main area for bill splitting
- **Responsive Design**: Uses CSS Grid for flexible layout
- **Interactive Elements**: Buttons for selecting friends, adding friends, and splitting bills
- **Form Validation**: Prevents invalid inputs and ensures required fields are filled

## Technical Concepts Covered

### **React Fundamentals**

- **Functional Components**: All components are built as functions
- **Hooks**: Extensive use of `useState` for state management
- **Props**: Passing data and functions between components
- **Event Handling**: Form submissions, button clicks, and input changes

### **State Management**

- **Local State**: Managing friends list, selected friend, form visibility
- **State Updates**: Immutable updates using spread operator and map functions
- **Conditional Rendering**: Showing/hiding components based on state

### **JavaScript Concepts**

- **Array Methods**: `map()`, `filter()` for rendering lists
- **Object Destructuring**: Extracting properties from objects
- **Template Literals**: Dynamic string creation for image URLs
- **Optional Chaining**: Safe property access (`selectedFriend?.id`)
- **Short-Circuit Evaluation**: Conditional rendering with `&&`

### **CSS & Styling**

- **CSS Grid**: Layout system for responsive design
- **CSS Variables**: Custom properties for consistent theming
- **Flexbox**: Used within grid items for alignment
- **Transitions**: Smooth hover effects and interactions
- **Modern CSS**: Border-radius, box-sizing, and responsive units

### **Form Handling**

- **Controlled Components**: All inputs are controlled by React state
- **Form Submission**: Preventing default behavior and validation
- **Input Types**: Text inputs, select dropdowns, and disabled fields

### **Data Management**

- **Unique IDs**: Using `crypto.randomUUID()` for friend identification
- **Immutable Updates**: Creating new arrays/objects instead of mutating existing ones
- **Balance Calculation**: Mathematical operations for bill splitting logic

## Project Structure

- **React 19**: Latest version with modern features
- **Create React App**: Standard React project setup
- **Testing Libraries**: Jest and React Testing Library included
- **ESLint**: Code linting for consistency
- **Build Tools**: Webpack and Babel through react-scripts

## Learning Outcomes

This project demonstrates practical application of React concepts in building a real-world utility app, covering:

- Component composition and reusability
- State management patterns
- User interaction handling
- Form validation and submission
- Responsive UI design
- Modern JavaScript and CSS practices

The app serves as an excellent example of how React can be used to build interactive, stateful applications with clean architecture and user-friendly interfaces.
