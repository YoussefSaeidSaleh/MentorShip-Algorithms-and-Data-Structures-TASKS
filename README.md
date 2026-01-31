index.htlml 
TASK 1

Fast Product Search Interface
for E-Commerce

Scenario: You9re a junior web developer at an online store with thousands
of products. The company needs an efficient product search feature so
customers instantly find what they want without waiting.
Assignment: Create a single HTML file containing the following:
Render a search interface:
An input box for the user to type a product name.
Display a scrollable, sorted list of 503100 product names (use a
static array of strings).
Efficient Search Logic:
Implement product search using both:
Linear search: Check each product consecutively.
Binary search: Split the array each step and search efficiently.
Highlight the found product in the list and visually show each step
checked (e.g., color/items as the algorithm examines them).
Performance Comparison:
Display how many comparisons each algorithm made for the
current search.
Show a simple bar chart (divs or canvas) for linear vs binary search
comparisons.
Bonus:
Animate the steps of each search in the UI.
Add a quick <recursion demo= with interactive Factorial and
Fibonacci calculators, displaying the recursive call stack visually.
Hints:
All code (HTML, CSS, JS) must be in a single HTML file.
Use Array.sort() in JS to keep your data sorted.
Use colored backgrounds, text, or borders to indicate which items are
checked in each search step.
Comparison chart can be built by changing the width of divs, or using the HTML5

##################################################################################################

warehouse-inventory.html 
TASK 2

Warehouse Inventory List Manager
Scenario: You9ve been hired to create a product inventory system for a local
warehouse. They need to add and remove items, monitor their stock, and
undo/redo mistakes quickly.
Assignment: Make a single HTML file that provides these features:
Inventory Management UI:
An input form to add new products (name, quantity).
A visible list showing current inventory (each item as a box or card).
Linked List Implementation:
Store product items in a custom doubly linked list class written in
JavaScript (not just an array).
Each product node should include links to <previous= and <next=
items, shown visually with arrows.
Undo/Redo Functionality:
Let the user undo or redo their last change (use stacks/arrays to
track history).
Buttons for <Undo= and <Redo=.
Inventory Stats & Actions:
Show total items and the most recently changed item.
Allow editing and removal of any product node.
Bonus:
Visual comparison of the list vs array operations (e.g., show how
many steps to add/remove in each structure).
Hints:
Update the DOM with every add, edit, remove, undo, or redo.
For visual arrows, use Unicode characters, SVG, or simple CSS.
All code (HTML, CSS, JS) must be in a single HTML file no frameworks!
