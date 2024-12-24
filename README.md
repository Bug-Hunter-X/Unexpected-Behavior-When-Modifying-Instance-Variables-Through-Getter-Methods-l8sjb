# Ruby Instance Variable Modification Bug
This repository demonstrates an uncommon error in Ruby related to modifying instance variables through getter methods.  The core issue revolves around the inability to directly change an instance variable (@value) if you've only defined a getter (the `value` method in this example) and no corresponding setter method. Attempting to assign a new value to the getter method will not change the value of the instance variable.

The `bug.rb` file showcases the problem, and `bugSolution.rb` presents a solution for correct modification of the instance variable.