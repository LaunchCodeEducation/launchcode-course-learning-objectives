At the end of angular class 2 students will be able to declare click handelers, take in user input, and display it and show lists of data using a loop directive.

Class 2

* Directives are used in templates to manipulate DOM elements.
* Structural directives shape the page by adding and removing elements.
* Structural directives start with a `*`, such as `*ngIf`, `*ngFor`.
* Only one structural directive can be assigned to a host element.
* Understand that `*ngIf` adds or removes the host element and it's descendents.
* Know that each iteration of `*ngFor` creates a copy of the host element and it's descendents.
* Can use current item as a local variable

  * Example: <li *ngFor="let user of users"> {{user}} </li>
  
* Know how to use local variables `index`, `first`, `last`, `even`, `odd`.
* Handle a click with a `(click)` directive and function in component to respond to the click.
* Understand how `(click)` relates to DOM `anElement.addEventListener("click", aFunction);`
* Use template reference variables and a click handler to take in user input

  * Example: `<input #name (click)=addThing(name)>`
