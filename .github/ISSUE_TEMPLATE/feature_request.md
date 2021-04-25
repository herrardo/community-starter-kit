---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

h1. Final User
When we define tasks from point of view of the final user, we have to describe what this user expects from this task:
h2. What do I expect from this task?
(Brief description of the interface and its behavior) Example:
* Display a list of queries already done by the user.
* Each query of the list has a button to delete it from the list.

h2. How can I interact with the result of this task?
(Different interactions of the user) Example:
* When the user clicks on a item of the list, then that query is searched.
* When the user clicks on the delete button, then the query is removed from the list.

h2. How does the result of this task look?
(Simple version of HTML expected, for example) Example:
```
    <ul class="queries-list">
        <li class="queries-list__item">
            <button class="queries-list__delete">X</button>
            <button class="queries-list__query">lego</button>
        </li>
        <li class="queries-list__item">
            <button class="queries-list__delete">X</button>
            <button class="queries-list__query">playmobil</button>
        </li>
    </ul>
```
(!) not strictly necessary to follow this layout. It is just an example.
h2. Other requirements to take into account
Example:
* The list of queries must be maintained in the same device over time, even closing the tab.
* If there are no queries, then nothing is displayed.

----

h1. Developer User
When we define tasks from point of view of the developer user, we have to describe what the user of X Components library expects from this task.
*!! NO DESIGN DECISIONS HERE, JUST REQUIREMENTS*.

h2. How do I use the result of this task?
Example:
* Importing and using a single component 
h2. What can I customize visually?
Example:
* Changing content of each query
* Changing content of each delete button
* Changing the complete content of the item
* Adding animation to items

h2. What can I customize in terms of behaviour?
Example:
* Changing the number of the queries to show

(!) All the naming and interface can be changed during the analysis and design if a better approach appears.

----

h2. Support attachments
* designs
* diagrams
* videos
* confluence links
* real examples links
* etc.
