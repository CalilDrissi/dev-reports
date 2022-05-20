1. review the context api basics and different method of implementation. 
2. how to implement:
	1. read access to all registered users
	2. read access to just selected users
3. what are hook and how can you make custom ones. 
	1. 
4. most used hooks
	1. useState for changing state
	2. useEffect for life cycle functionality
	3. useContext to give access to global state to any component 
	4. useReducer to dispatch action to change global state
5. you can create multiple global state contexts based on each data resourse.
6. in context the app level component gets wrapped in a Provider Component
7. fd
8. Context in React Instructions
	1. create a folder in src , name it context
	2. create types.js - contains the names of all the actions tha will change state value.
	3. create a folder for each resource type
	4. inside each resource type folder create 3 files
		1. [resource]Context.js
			1. import all in this file 
			2. create initial state
			3. create actions functionality
			4. call dispatch to execute global state value changes
			5. export the provider to wrap the whole app level component with it.
		2. [Resource]State.js
		3. [resource]Reducer.js