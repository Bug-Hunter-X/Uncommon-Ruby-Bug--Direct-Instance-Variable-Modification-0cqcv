# Uncommon Ruby Bug: Direct Instance Variable Modification

This repository demonstrates a subtle bug in Ruby related to directly modifying instance variables from outside their defining class.  Direct manipulation of instance variables using `instance_variable_set` or `instance_variable_get` can bypass encapsulation, leading to maintainability issues and unexpected side effects. This can be especially problematic in larger applications.

The `bug.rb` file showcases this issue. The preferred approach is to use methods to modify object state which enhances code readability, predictability, and testability.

The `bugSolution.rb` provides a corrected version employing proper methods for data modification.
