# Turing

## GIT
1.  How can you see all local branches with merged work? => **git branch --merged** | git branch --merged main
2.  Which command can you use to discard changes to a file inside a git repository? => **git checkout -- <filename>** | git restore <filename>
3. which of the following are true about tags in git? => **D**
  A. branches contain full copies of the files in their histories
  B. Tags can only point to a branch
  C. Tags cannot be pushed to a remote
  D. Tags cannot be moved and can be cryptographically signed => **True**
  E. None of the above
4. When is it necessary to use **git mv** for moving a file? => It simplifies the process of moving/renaming and staging the change in one command.
5. In Gitflow, the following branch types are part of the standard workflow => **Main/Master branch, Develop branch, Feature branches, Release branches, Hotfix branches**
6. Which command can be used to configure vimdiff and the default diff tool for git  => **git config --global merge.tool vimdiff**
7. How can you stash your changes interactively? => **git stash push -p | git stash save -p**
8. When do you use git rebase instead of git merged? => **Use git rebase when you want a clean, linear history and want to avoid merge commits.**
9. Which of the following is not a git configuration scope => **User** While Global, Local, and System are valid configuration scope
10. How can you replace several commits with one? => **squashing using interactive rebase eg git rebase -i HEAD~3**
11. Which character append at the end of a commit reference points to the parent of that commit? **^**
12. git pull is a shorthand for which command? => **git pull = git fetch + git merge**
13. Which command can be used to identify all the branches that have been merged into master? => **git branch --merged master**
14. Which of the following commands can be used to delete all files and directories that git does not track from your working directory? => **git clean -fd**
15. after installing git and prior to issuing the first commit, which two configuration properties does the tool expect you to configure? => **username and useremail**
16. Which command can you remove a file from git without removing it from your file system? => **git rm --cached <file> | git reset <file> | git unstage <file>**
17. how can you restore a branch you just deleted? => **Create a new branch on the same commit after looking up the commit hash with reflog git reflog and git checkout -b <branch-name> abc1234**
18. what happens when you run git commit without the -m argument? => **Git will open the default text editor for you to enter a commit message.**
19. Which is the first step in a typical git workflow? => **stage the files**
20. Which command returns the shortest unique SHA1 for a commit inside the current repository? => **git rev-parse --short <commit>**
21. Which of the following cannot be done with git checkout?? => **Remove a file from the staging area**
22. Which command shows the author for each line of text? => **git blame <filename>**
23. How can you stash your changes, not including anything in the staging area? => **git stash push --keep-index | git stash push -k**
24. What is the command to view the history of commits for the repository? => **git log**
25. remove untracked file from your working directory => **git clean**
26. git command to stash a change with a message. => **git stash save 'Message'**
27. tag command option that creates an annotation tag in git. => **-a**
28. A head is nothing but a reference to the last commit object of a branch. => **YES**
29. Stages in which the git file can reside. => **Modified | Staged | Committed**
30. Which of the following is not part of the data structure of a git repository? => **Body ELement** Branch Pointer, Head Pointer, and Commit Object are part
31. Which Check summing technique is used in git? => **SHA-1**
32. Which git command creates a copy of the existing git repository? => **git clone**
33. git command that displays the file that has been modified? => **git log --patch | git log -p**
34. which of the library git depends on? => **zlib, openssl, libiconv**
35. git command to get a high-level overview of the project history. => **git log --online**
36. Where is the metadata of the project stored by Git? => **git directory**
37. How do you view commit history in Git? => **git log**
38. What shortcut to stage all the changes you have? => **git add .**
39. What language is used in git? => **C**
40. command to stage your entire directory and every non-empty directory inside your current directory. => **git add .**
41. git command to check the created, modified, and deleted files in gitbash before committing. => **git status**
42. set your user name during a git initial setup. => **git config --global user.name 'Omobayode'**
43. What contains values for every user on the system? => **gitconfig file**
44. Which flag enables showing the diff introduced in each commit by the git log command? => **-p**
45. What command staged all new and updated files? => **git add -A**.
46. What command renames the current branch? **git branch -m**
47. What does the command git reset do? **Undoes changes by moving the HEAD to a previous commit**
48. After you add a file it becomes? => **Staged**
49. which command creates an empty git repository in the specified repository? **git init**
50. git reset --hard used to? **uncommitted the changes, unstage the changes, and delete the changes**
51. Git is Distributed Version Control System
52. What is the area where uncommitted changes are temporarily held after adding? => **staging area**
53. which command configures the use of emacs as the default editor? => **git config --global core.editor emacs**
54. What command is the convenient way of setting configuration options for defining the behavior of the repository and many others? => **git config**
55. command used to connect the remote repo with the local repo? => **git remote add**
56. How does git think of its data? => **Snapshot**
57. Git belongs to what generation of Version Control system? => **3rd**
58. git command to check stored stashes? => **git stash list**
59. which option of remote command, add a new remote git repository as a short name to reference easily? => **add**
60. which version onward did git offer, reverting a file back to what it looked like when last committed? => **1.6**
61. command not valid with git stash command. => **git stash list push**
62. what represents the last commit in the current checkout branch in git? => **Head**
63. Which command lists only the last two diff introduced in each commit? => **git log -p -2**
64. What is the default text editor for the Bash shell with a Windows-based git install? => **VIM**
65. Which of the following is not a DVCS(Distributed Version Controlled Syaytem)?  => **rcs**
66. What command gets the list of commits made in the last two weeks? => **git log --since=2.weeks**
67. Command to create git branch? => **git branch**
68. Command used to show a limited number of commits? => **git log -n**
69. Git command to compare two specified branches? => **git diff ...**
70. What is a commit hash in git? **A unique identifier for a commit**
71. What is the version of the repository that diverges from the main working project? => **Branch**
72. Arranging customer names in ascending order is an example of? => **Information Processing**
73. git commit -m <?> is for? => **Comment**
74. git command to show all parameters in git? => **git config --list**
75. git is a ------ Version Control Tool. => **Decentralized**
76. A reference to the remote repository from where a project is initially cloned is called? => **Origin**
77. Who is attributed with inventing git? => **Linus Torvalds**
78. Which option in the output of the log command, shows the list of file modified after the commit information.




## HTML and CSS
1. How do you add comments in HTML? => **<!-comment->**




## React
1. What is React primarily used for? => **Building user interfaces**
2. Which feature of React allows it to efficiently update the UI? => **Virtual DOM**
3. JSX stands for... => **JavaScript XML**
4. In JSX, how do you express JavaScript variables? => **Inside curly braces**
5. Which of the following is the correct way to comment in JSX? => **{/*Comment here*/}**
6. What is the correct syntax for embedding a JavaScript expression in JSX? => **{expression}**
7. JSX is processed into... => **JavaScript Objects**
8. JSX elements must be wrapped in an enclosing tag. What is this concept known as? => **Encapsulation**
9. What does the following JSX code render?{'Hello' + 'World'} => **HelloWorld**
10. Identify the error in the following JSX: <div>Hello World</div><div>welcome</div> => **Missing enclosing tag** Both of them must be wrapped in an enclosing parent tag
11. What are Props in React? => **Data passed from a parent component to a child component**
12. A functional component in React is... => **A function that returns a React element**
13. Which of the following is the correct way to define a component's initial state in a class component? => **Inside the constructor() method**
14. In React, what is the role of a key prop in a list of elements? => **It helps React identify which items have changed**
15. How are state and props different in React? => **State is internal and controlled by the component itself, while props are external and controlled by whatever renders the component**
16. What is the primary purpose of props in React? => **To pass data and event handlers to child components**
17. Consider this code snippet:<div> <Mycompoenent/> </div> What does MyComponent represent here? => **A child component**
18. Which of the following is true about React components?=> **They can only return one root element**
19. What does the setState() function do in a class component? => **Updates the component’s state and re-renders the component**
20. Which lifecycle method is called right before a component is unmounted from the DOM? => **componentWillUnmount()**
21. What is the correct order of lifecycle phases in a React class component? => **Mounting -> Updating -> Unmounting**
22. In which lifecycle method should you make API calls in a class component? => **componentDidMount()**
23. What is the primary use of the componentDidUpdate method in a class component? => **To update the component in response to prop or state changes**
24. How does React determine whether to re-render a component in response to state changes? => **It uses the shouldComponentUpdate lifecycle method**
25. Consider this code:
componentDidMount() { this.setState({data: 'new data'}); }.
When is the new data available for render? => **After the component re-renders**
26. What is a potential issue with this setState usage?
this.setState({value: this.state.value + 1}); => **It may lead to outdated values due to the asynchronous nature of setState**
27. Identify the issue in this code:
class MyComponent extends React.Component {
render() {
return

{this.state.count}
; } } => **State is not initialized in the constructor**
28. Identify the issue in this code:
class MyComponent extends React.Component {
render() {
return

{this.state.count}
; } } => **State is not initialized in the constructor**
29. What is wrong with this lifecycle method usage?
componentDidMount() { this.setState({value: this.props.initialValue}); } => **Props should not be used to set state**

30. In React, how do you attach an event handler to an element? => **Using the onEvent attribute**
31. What is the correct way to bind a method to a component instance in a React class component? => **this.method = this.method.bind(this) in the constructor**
32. Why is it generally a good idea to bind event handler methods in a class component's constructor? => **To allow access to the 'this' keyword**
33. Which of the following is true about event handling in React? => **React events are named using camelCase**
34. What is a SyntheticEvent in React? => **A custom event system for handling native events**
35. How do you pass an argument to an event handler in React? => **By using an arrow function in the onClick attribute** | **By using the bind method**
36. What is wrong with this event handler definition?
handleClick() { console.log(this.state.value); } => **'this' is not bound to the component**
37. Which operator is commonly used for inline conditional rendering in React? => **&& (Logical AND)**
38. What is the purpose of using the ternary operator in React? => **To render one of two components based on a condition**
39. How can you prevent a component from rendering in React? => **Return null in the render method**
40. What will the following code render?
{isLoggedIn && } => **if isLoggedIn is true**
41. How does the following code render different components?
{isLoggedIn ? : } => **Renders if isLoggedIn is true, otherwise**
42. Identify the issue in this conditional rendering code:
{isLoggedIn ? } => **Missing the false condition**
43. What's wrong with this code snippet for conditional rendering?
{isLoggedIn && || } => **It combines two different conditional rendering patterns incorrectly**
44. What is the purpose of keys in React lists? => **To uniquely identify list items**
45. What type of value should be used for keys in React? => **Any unique identifier**
46. In React, when is it necessary to use keys? => **When rendering a list of items**
47. What can happen if you don't provide unique keys for items in a list in React? => **Performance issues and bugs in the UI update logic**
48. What is the correct way to assign a key inside a map() function in React? => **Use a unique property of each item**
49. What's wrong with using indexes as keys in React for the following code? => **It can cause rendering issues if the list changes**
50. What is a controlled component in React? => **A component whose state is controlled by React**
51. In React, how do you handle form submission? => **Using an onSubmit event handler in the form element**
52. How do you collect form input values in React? => **By storing the values in the state on every change**
53. What is the main difference between controlled and uncontrolled components in React? => **Controlled components manage their own state, while uncontrolled components store their state in the DOM**
54. How would you create a basic text input field in a React component? => **<input type='text' value={this.state.value}/>**
55. What is the correct way to handle a form input change in React? => **onChange={(event) => this.setState({value: event.target.value})}**
56. What does "lifting state up" mean in React? => **Moving state to a parent component for shared access**
57. Why is lifting state up beneficial in React applications? => **It enables multiple components to share and synchronize state changes**
58. In the context of lifting state up, what is a common pattern for two-way data binding between parent and child components? => **Using a callback function passed from parent to child**
59. What is a potential downside of lifting state up in a large React application? => **Difficulty in managing state across distant components**
60. How do you lift state up from a child component to a parent component? => **By passing a state setter function from parent to child**
61. What is the correct way to update the parent's state from a child component? => **Use a callback function provided by the parent**
62. Identify the problem in this code:
class Parent extends React.Component { updateState() { /.../ } render() { return ; } } => **updateState should be bound to this in the constructor**
63. What's the issue with this lifted state approach?
class Parent extends React.Component {
constructor(props) {
super(props);
this.state = { value: '' };
} render() {
return <Child value={this.state.value} onChange={value => this.setState({value})} />; } } => **onChange handler in Child is not implemented correctly**
64. In React, what is favored for reusing component logic? => **Composition**
65. What is a key advantage of composition over inheritance in React? => **Composition provides a clearer component hierarchy**
66. How does React achieve code reuse with composition? => **By rendering props children**
67. What is an example of composition in React? => **Passing components as props to other components**
68. Why might you choose composition over inheritance when designing React components? => **Composition allows for easier code refactoring and maintenance**
69. Which React code snippet demonstrates composition? => **<Parent> <Child/> </Parent>**
70. How can you use composition to pass content into a component in React? => **By passing content as a child between component tags**
71. What is a higher-order component (HOC) in React, and how does it relate to composition? => **A function that takes a component and returns a new component**
72. What's wrong with using inheritance to extend a React component like this:
class EnhancedComponent extends BaseComponent { /.../ }? => **Inheritance can lead to a more complex and less predictable component structure**
73. What is React Router used for in a React application? => **Routing between different components based on URL**
74. Which component in React Router is used to configure a route? => **<Route/>**
75. What does the component do in React Router? => **It provides conditional logic for rendering components**
76. How do you navigate to a different URL using React Router? => **Using the component**
77. How do you define a route parameter in React Router? => **<Route path = "/:id" />**
78. How can you programmatically navigate to a new route in React Router? => **Using this.props.history.push('/new-route')**
79. What is the use of the exact prop in a component? => **To ensure that the route only matches the exact path without any sub-routes**
80. What is the purpose of the useState hook in React? => **To manage local state in a functional component**
81. When is the useEffect hook run in a React component? => **After every render of the component, including the first render**
82. What does the useEffect hook replace in class components? => **componentDidMount, componentDidUpdate, and componentWillUnmount methods**
83. What is the correct way to conditionally run an effect with the useEffect hook? **By setting a specific condition in the dependency array**
84. What does the useCallback hook do? => **Memoizes a callback function to prevent unnecessary re-renders**
85. How do custom hooks enhance the functionality of React components? => **By allowing state and lifecycle features to be reused across multiple components**
86. How do you initialize state with the useState hook? => **useState(initialState)**
87. What is the correct way to update state based on the previous state using useState? => **setState(prevState => prevState + 1)**
88. How can you implement a fetch request with useEffect that updates the state when the data is retrieved? => **By creating a separate async function outside of useEffect and calling it inside useEffect**
89. Identify the issue in this useState usage:
const [count, setCount] = useState(0); setCount(count + 1); => **The state update should be inside a component or effect**
90. What could cause an infinite loop in a component using useEffect? => **Omitting the dependency array | Including a state variable that constantly changes within the dependency array**
91. How do you prevent a memory leak in a component that subscribes to an external data source using useEffect? => **By unsubscribing from the data source in the return function of useEffect**
92. What is the primary use of the Context API in React? => **To manage global state across the entire application**
93. How does the Context API help in avoiding "prop drilling"? => **By allowing components to subscribe to context changes directly**
94. What is a potential drawback of using the Context API excessively? => **Difficulty in managing and tracking state changes**
95. How do you consume a context value in a functional component? => **Using the useContext hook**
96. How can you dynamically change the value of a context in a component tree? => **By updating the state that's passed to the context provider's value prop**
97. What might be the issue if a component is not receiving the expected context value? => **The component is not wrapped with the Context.Provider | The context value is not updated correctly**
98. How do you address a performance issue caused by unnecessary re-renders in components consuming a frequently updated context? => **Splitting the context into multiple smaller contexts**
99. What is a Higher-Order Component (HOC) in React? => **A function that takes a component and returns a new component**
100. Why are Higher-Order Components useful in React? => **They make components more reusable**
101. What is a key consideration when using Higher-Order Components? => **They should not alter the component's signature**
102. How do you apply a Higher-Order Component to a React component? => **HOC(Component)**
103. What is the correct way to pass additional arguments to a Higher-Order Component in React? => **HOC(additionalArg)(Component)**
104. What could cause a React component wrapped in an HOC not to update as expected? => **The HOC does not pass down props to the wrapped component**
105. How do you avoid namespace clashes in props when using multiple Higher-Order Components? => **By using unique prop names across all HOCs**
106. What is the main purpose of custom hooks in React? => **To reuse stateful logic between different components**
107. What are the benefits of using advanced hooks like useReducer and useContext together? => **They allow for global state management without third-party libraries | They simplify the process of prop drilling**
108. What should you consider when creating a custom hook? => **Its impact on the component's lifecycle | The types of components it will be used in | How it manages state and side effects**
109. How do you create a custom hook in React? => **By creating a function that starts with use and uses other hooks**
110. How can you optimize performance in a component that uses many custom hooks? => **By using the useCallback and useMemo hooks | By minimizing the number of state updates**
111. What is a common mistake to avoid when using custom hooks? => **Using them inside conditional statements | Defining them inside components | Calling them outside of functional components**
112. How do you troubleshoot a memory leak in a component caused by a custom hook? => **By ensuring cleanup functions are defined in effects**
113. What is the purpose of using React.memo in a functional component? => **To prevent a component from re-rendering unless its props have changed**
114. How does the useCallback hook contribute to performance optimization in React components? => **By caching functions to prevent unnecessary re-creations**
115. What is the main benefit of code splitting in React? => **To reduce the initial loading time of the application**
116. How can you implement lazy loading of components in React? => **Using React.lazy and Suspense**
117. In what scenario is using shouldComponentUpdate or React.memo not effective for preventing unnecessary re-renders? => **When the component always receives new object references as props**
118. How do you identify and address unnecessary re-renders in a React application? => **Using the React DevTools Profiler | Using console logs in the render method | Reviewing the code for inefficient patterns**
119. What can cause a memory leak in a React component, and how do you fix it? => **Not cleaning up event listeners or subscriptions in useEffect**
120. What is the primary benefit of using TypeScript with React? => **Static type checking and easier error detection**
121. How does TypeScript enhance the development of large-scale React applications? => **By offering enhanced readability and maintainability through type annotations and interfaces**
122. In TypeScript, how can you define the types of props in a React functional component? => **Using type assertions | Using generic types**
123. How do you define state in a TypeScript class component? => **state: StateType = initialState; inside the class | this.state = { ... } inside the constructor**
124. How do you type a React component with generic props in TypeScript? => **By using the React.ComponentType with generics | By using the React.FC type with a generic parameter**
125. What is a common issue when using TypeScript with React and how can it be resolved? => **Type errors due to incorrect prop types, resolved by ensuring prop types match the expected interface or type**
126. How can you troubleshoot TypeScript errors related to the context API in a React application? => **By ensuring the context value matches the type defined in the Context creation**
127. What is the main purpose of using Jest in React applications? => **For unit and integration testing**
128. How does React Testing Library differ from enzyme in testing React components? => **React Testing Library focuses on rendering components and user interactions, while enzyme focuses on internal component state and methods**
129. What is a best practice when writing tests for React components using React Testing Library? => **To focus on testing the component as users would interact with it**
130. How do you mock a module or function in Jest? => **Using jest.fn() to create a mock function | Using jest.mock() to mock an entire module**
131. How do you test a component that fetches data from an API using React Testing Library? => **By mocking the fetch function and simulating a response**
132. What common issue should you be aware of when testing asynchronous behavior in React components? => **Tests completing before asynchronous operations**
133. How do you identify and resolve issues related to event handling in tests using React Testing Library? => **By ensuring the correct event types and payloads are used | By manually triggering events in the component**
