# KeeperReactApp

Rendered through CodeSandBox: https://xkgkg2.csb.app/

A google keep clone designed using React.

Technologies learned and used:
- Node.js
- NPX
- REACT (React, React-Dom, React-scripts)


Note to self:

+ When trying to monitor the state of a component, call the useState method from react. This will give you a state variable and a function to affect that state variable.
  - Example: "const [notes, setNotes] = React.useState([]);"
  Notice the ES6 assignment operator!
+ If elements are being repeated, think about turning them into components. These components can then be rendered using different props.
+ Each component is a separate JSX file.
  - In the component file, you need to export the "returning" function. Example: "export default CreateArea;"
  - In App.jsx, you need to import the component. Example: "import CreateArea from "./CreateArea";"