# W0D2
Week 0 Day 2 After-Class Assignment: Github

# Objective
Practice advanced Git workflows by implementing feature branching, handling merge conflicts, and writing unit tests.

# Instructions

Initialize Git Repository  
   - Run `git init` to create a new repository.  

Create Feature Branch  
   - Create a new branch: `feature/update-message` using `git checkout -b feature/update-message`.

Modify Code  
   - Update the `hello_world()` function to return "Hello from [your name]!" instead of "Hello, Git World!".

Add Unit Test for Updated Message  
   - Modify the `test_hello_world()` in `test_main.py` to reflect the updated return value.

Commit Changes  
   - Commit your changes on the `feature/update-message` branch.

Create Another Feature Branch for New Functionality  
   - Create a second branch, `feature/add-greeting`, and implement a new function `greet_person(name)` that returns "Hello, [name]!".

Test and Commit New Functionality  
   - Write a new test for `greet_person(name)` in `test_main.py` and commit your changes.

Simulate a Merge Conflict  
   - Switch back to the `feature/update-message` branch, modify the `hello_world()` function again to return "Welcome to Git!".

   - Commit this change and switch back to `feature/add-greeting`.

   - Merge `feature/update-message` into `feature/add-greeting` to trigger a merge conflict.

Resolve Merge Conflict  
   - Resolve the conflict in `main.py` by selecting the desired changes.

   - After resolving, commit the merge.

Push to GitHub  
    - Push all branches and commits to GitHub. 

