#Om
---
###Why another js framework
###FRP
###OM
---

### Why another js framework

### What are we trying to acheive?
* Rapid development
* Routing for Single Page Applications
* Modular components
* Abstraction of dom interaction

### Intersection traffic light

####Problems with js frameworks
* Need expertise of the framework in order to make simple ui changes
* Communication between components is difficult
* Hard to maintain large applications
* Long turn around time for business "pivots"

####Concrete Examples
* Performance issues
* ng-repeat upgrade compatibility issues
* Scoping issues need to broadcast to children (callback hell)
* Drag and drop with ng-repeat has major issues
* Need to `watch` for ng-repeat to finish before you can do certain things
* To get best modularity out of angular you need terse, complex, large code (ng-repeat)

####How to manage state?
* Sharing local state is hard
* Components should be able to affect other components without sharing state
* Changing global state should not have to rerender everything

---

###FRP

####Basics
* Comes from haskell 1998
* Still evolving through research
* Declarative = composable

####Animation Example
* Imperative != composable
* Declarative = composable

---

###Om

####React
* Library (No more dom manipulation)
* Focuses on components
* Declarative

####Om Improvements
* Immutable Data Structures
* No need for templating language
* Cursors

####Demo

####Implications
* Interface Builder
* Faster pivots
* Composable components
* Ability to scale to large app
