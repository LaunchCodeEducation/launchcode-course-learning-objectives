At the end of class 2 students will be albe to create a simple TODO Angular application that uses data binding, and static data.

Class 2

* Directives are used in templates to manipulate DOM elements.
* Structural directives shape the page by adding and removing elements.
* Structural directives start with a `*`, such as `*ngif`, `*ngfor`.
* Only one structural directive can be assigned to a host element.
* Understand that `*ngIf` adds or removes the host element and it's descendents.
* Know that each iteration of `*ngFor` creates a copy of the host element and it's descendents.
* Can use current item as a local variable
  
  * Example:
  <li *ngFor="let user of users">
   {{user}}
  </li>
  
* Know how to use local variables `index`, `first`, `last`, `even`, `odd`.
* Attribute directives alter the behavior of HTML elements.
* Many attribute directives can be applied to one host element.
* click handlers
* data binding / user input
