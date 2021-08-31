# forms
## What is a ‘Controlled Component’?
a component that renders form elements and controls them by keeping the form data in the component's state
## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
update the state with thrier responses ,The most basic way of working with forms in React is to use what are referred to as “uncontrolled” form inputs. What this means is that React doesn’t track the input’s state. HTML input elements naturally keep track of their own state as part of the DOM, and so when the form is submitted we have to read the values from the DOM elements themselves.
## How do we target what the user is entering if we have an event handler on an input field?
The event also applies to elements with contenteditable enabled, and to any element when designMode is turned on. In the case of contenteditable and designMode, the event target is the editing host. If these properties apply to multiple elements, the editing host is the nearest ancestor element whose parent isn't editable.
#  conditional operator
## Why would we use a ternary operator?
to simplify your if-else statements that are used to assign values to variables. 
## Rewrite the following statement using a ternary statement:
  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
 
 

