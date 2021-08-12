# class05

1. static applications and websites render in the user’s browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side

1. a. Break The UI Into A Component Hierarchy
   b. Build A Static Version in React
   c.  Identify The Minimal (but complete) Representation Of UI State
   d. Identify Where Your State Should Live
   e.Add Inverse Data Flow
2.  component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

3. build a version that takes your data model and renders the UI but has no interactivity

4. use states

5. Is it passed in from a parent via props? If so, it probably isn’t state.,Does it remain unchanged over time? If so, it probably isn’t state., Can you compute it based on any other state or props in your component? If so, it isn’t state.

6.  * Identify every component that renders something based on that state.
    * Find a common owner component 
    * Either the common owner or another component higher up in the hierarchy should own the state