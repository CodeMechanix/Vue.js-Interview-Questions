# Vue.js Interview Questions

Frequently asked Vue.JS Interview Questions and Answers

Q1. What is Vue.js? What are the advantages of it?
> Vue is a progressive framework used to building user interfaces. The core library is focused on the view layer only, and is easy to pick up and integrate with other libraries or existing projects.
Advantages of using Vue.js:
- Small in size 
- Easy to Understand 
- Simple Integration
- Flexibility 
- Virtual DOM 
- Components 
- Two-Way Communication

Q2. What are all the life cycle hooks in Vue instance?
> Each Vue instance goes through series of steps when they are created, mounted and destroyed. Along the way, it will also runs functions called life cycle hooks, giving us the opportunity to add our own code at specific stage. Below are the events, a Vue instance goes through.

> beforeCreate — The first hook in the creation hooks. They allow us to perform actions before our component has even been added to the DOM. We do not have access to the DOM inside of this.
> created — This hook can be used to run code after an instance is created. We can access the reactive data. But templates and Virtual DOM have not yet been mounted or rendered.
> beforeMount — The beforeMount hook runs right before the initial render happens and after the template or render functions have been compiled. Most likely we’ll never need to use this hook.
> mounted — We will have full access to the reactive component, templates, and rendered DOM. This is the most frequently used hook.
> 


