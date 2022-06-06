This is a simple Redux example without any react integration

# REDUX
State management  system for cross-components or app-wide state

## REACT CONTEXT DISADVANTAGES
- Complex Setup / Management - Not good for enterprice application with lot of components, in such case end up with nested context provider hierarchy
- Performance Issue, React Context is not optimized for high frequency state changes

## CORE REDUCER CONCEPTS DIAGRAM
![Core Redux Concept](docs/imgs/core-redux-concept.png?raw=true "Core Redux Concept")

## REDUCER FUNCTION
- It is a standard JS function but it is called by Redux Library and always recieve the old/existing state and action.
- Should be a pure function (Same input always leads to same output)
![Reducer Function](docs/imgs/reducer-function.png?raw=true "Reducer Function")