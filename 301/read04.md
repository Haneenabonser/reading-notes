## React and Forms
**React Docs - Forms**
- What is a ‘Controlled Component’?
    - It is the component that takes its current value through props and notifies changes through callbacks like onChange .
- Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  - We should update the state with their responses as soon as they enter them, because that input will be a cntrolled component by react and also controls what happens in that form on subsequent user input.
- How do we target what the user is entering if we have an event handler on an input field? 
  - By creating a function contains the passed in event parameter to get the target input element; from the target get the value and name of the input element.

**The Conditional (Ternary) Operator Explained**
- Why would we use a ternary operator?
- Rewrite the following statement using a ternary statement:                          
  if(x===y){                                 
 console.log(true);                                      
  } else {                          
 console.log(false);                            
  }                                        
    - *x===y ? 'Yes' : 'No';*


## Things I want to know more about
React forms.
