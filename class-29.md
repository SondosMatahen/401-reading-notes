# Class 29 - reading

### The Component Lifecycle
 - The component lifecycle is exactly what it sounds like: it details the life of a component. Like us, components are born, do some things during their time here on earth, and then they die.

 - A component can only be in one stage at a time. 
   * It starts with mounting.
   * Then moves onto updating. 
   * It stays updating perpetually until it gets removed from the virtual DOM.
   * Then it goes into the unmounting phase and gets removed from the DOM.

 - The lifecycle methods allow us to run code at specific points in the component’s life or in response to changes in the component’s life.
