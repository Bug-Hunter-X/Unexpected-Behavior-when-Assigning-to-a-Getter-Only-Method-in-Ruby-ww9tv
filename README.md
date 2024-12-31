# Ruby Getter-Only Method Assignment Bug

This repository demonstrates an uncommon bug in Ruby related to assigning values to methods that only have a getter defined.  Direct assignment does not modify the instance variable, leading to unexpected behavior if not properly understood.

The `bug.rb` file shows the issue.  The `bugSolution.rb` file provides a solution.

## How to Reproduce
1. Clone the repository.
2. Navigate to the repository directory in your terminal.
3. Run `ruby bug.rb`.