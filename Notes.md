# Notes

## Section 2

\- Available key modifiers: <https://vuejs.org/v2/guide/events.html#Key-Modifiers>

\- We can use `@` as `v-on`. It's a shortcut:

Example:  `<button v-on:click="action">Button</button>` --> `<button @click="action">Button</button>`

\- We can use `:` as `v-bind`. It's a shortcut:

Example: `<a v-bind:href="link">Link</a>` --> `<a :href="link">Link</a>`

## Section 3

\- On Vue.js version 2.1 or higher, you now actually have access to a v-else-if  directive:  <https://vuejs.org/v2/guide/conditional.html#v-else-if.>

\- While `v-if="CONDITION"` attaches or ditaches the element, `v-show="CONDITION"` just hide/show it. So, if you're using a `v-if` condition and set it to false, you can't see the element if you inspect the page (because it's ditached), but if you use `v-show` and inspect, you will see the element there (because it's hidden / not being displayed). `v-if` is also better performance-wise to have less elements in the DOM.

## Useful links

- Installation - <https://vuejs.org/v2/guide/installation.html>

- Vue School - <https://vueschool.io/>

- Official Docs - Getting Started: <http://vuejs.org/guide/>

- Official Docs - Template Syntax: <http://vuejs.org/guide/syntax.html>

- Official Docs - Events: <http://vuejs.org/guide/events.html>

- Official Docs - Computed Properties & Watchers: <http://vuejs.org/guide/computed.html>

- Official Docs - Class & Style Binding: <http://vuejs.org/guide/class-and-style.html>

- Official Docs - Conditionals: <http://vuejs.org/guide/conditional.html>

- Official Docs - Lists: <http://vuejs.org/guide/list.html>