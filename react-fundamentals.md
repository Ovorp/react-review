### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
    React is a JavaScript library created by Facebook. It uses the idea of components to organize data and the structure of the UI.

2.  What is create-react-app?
    Create-react-app is a command in the terminal that is used to quickly create a project using react. It sets up all the dependencies and other files you need for react to work.

3.  What is Component Based Architecture?
    The idea of component based architecture is to break down websites into small reuseable chucks and then use those chunks to build a site. Like legos.

4.  What is JSX?
    JSX is what is used in react to structure the content of the site or what the user sees. It looks like HTML but there are some semantic differences.

5.  What is the virtual DOM?
    The virtual DOM is what is used by react to speed up rendering time. It is a copy of the DOM that you interact with when you use react. Once there are differences betweent he virtual DOM and the actual DOM react pushes all the changes at once to the DOM. This also reduces the number of times the DOM has to be changed.

6.  What is unidirectional (one-way) data flow?
    Unidirectional data flow is the idea that data can only flow from parents to children elements. The idea is that if you have multiple children elements you can't accidently change data in the parent when you change the data in the children.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?

9.  Explain what this code does:

```jsx
import React from 'react';

const Mentor = (props) => (
  <div className="mentor-container">
    <h1 className={props.title === 'Lead Mentor' ? 'lead' : ''}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

10. Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

11. Use `create-react-app` to create a new React application called `student-directory`

12. Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
