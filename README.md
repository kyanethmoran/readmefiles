# readmefiles
readme files for scavanger hunts



1) What Is React?
  This is a library (JS) that uses components to render single page applications and have improved
  speed and scalability over vanilla js code, originally created by facebook. Uses one way data binding
  and uses Javascript with JSX to render data with the virtual DOM. Uses components, views, modules
  and models. Features state and props.
	
2) What is JSX?
  Javascript/XML. It is a way to couple the logic of UI and rendering making it possible to have event
  handling, data changes, and data display all together in a singular file (the component) rather than
  having various files to each handle a facet of the code. JSX will be compiled into JS so JSX can be used
  within statements like conditionals, assignments, arguments, and returns.
	
3) Explain the different types of components.
   a) Class Components: This is where you set your state. It also contains a constructure function and
      the super method. This is the ONLY component where you can set the state.
   b) Functional Components: Functional components are how you render the elements to the page, you 
      cannot set the state here. With hooks you can now use methods in these components to maintain state
      and use lifecycle methods.
   c) Pure Componenets: Only render based on set conditions and utilize the shouldComponentUpdate() method.
      The lack of rerendering constantly leads to better performance as there are less updates to the DOM.
	
4) What are higher order components?
  This is a fucntion that transforms one component into a new component, and it demonstrates the ability to 
  reuse component logic. They are used for adding addtional functionality to existing components. These are
  pure components, if the data changeses they are re-run. A higherlevel component wraps a "normal component"
  and gives extra data input.
	
5) What is context?
  This is how you pass data through levels of components without having to go through each "level" explicitly.
  Context is typically used when data needs to be accesses from many different components at different levels
  through the different levels of the application. While it avoids manual passing of data through each level
  it also makes code reusability more difficult. An alternative to using context is component composition.
	
6) What is State and Props?
  Both state and props deal with values and data however only state can be changed and updated and represents
  information about the components. Stateless components cannot have state. State is internal and controlled by 
  the react comonent itself.
  Props are read only and can be passed from one component to another. Stateless components can have props.
  Props are external and controlled by whatever renders the component.
	
7) What Are Hooks?
  Hooks allow you to use state without writing a class. You can use preexisting hook as well as make ur own
  custom hooks. Hooks give a function component the ability to access state and lifecycle methods which
  essentially takes away the need for most class components. There are 3 rules for hooks: can only be called
  inside react function components, can only be called at the top level of a component, cannot be conditional.
	
8) What are some of the “Rules” of Hooks?
  a) only call hooks at the top level
  b) only call hooks from react functions
  c) cannot be conditional
	
9) What are error boundaries?
  This how react catches errors without making the entire application crash, however error boundaries do not
  catch errors for event handlers, async code, server side rendering, errors throen inthe error boundary itself.
  When an error is caught a a fallback UI is displayed. Error boundaries only catch errors in the components below
  them in the component tree. It is similar to how the catch {} blocks works in JS
	
10) What are Keys?
  A key is an attribute that is used with making lists of elements in react. You use the keys to pick out which 
  elements in a list are being changed updated and deleted. It is recommended to use strings for keys and for them
  to be unique for them to be usefull. Using indexes as keys is not preferred becuase if the list gets reordered it can 
  cause confusion in the code.


  
