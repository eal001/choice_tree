Author: Elliot Lee
Date: 8 - 22 - 2021

# Adi's Choice Program #
This program intends to be a simple set of scrtipts that eventually will be built out into a GUI app
They will create, build and traverse a choice tree to efficiently store and quickly traverse options.
It was inspired by a hard-coded way to graphically determine lab capabilities. 

The create.py script will be run to build and modify the existing data that the tree will store.
The traverse.py script will be run simply to acquire the existing information in the tree.
The decode.py is a helper function to take an existing file and build out the tree from an encoded form
The encode.py is a helper function that will take the existing data structure and turn it into storable data
Each of the other .py files hold classes and definitions that are helpful for the application to run

## known bugs ##
when loading in a new choice tree, the menu frame doesnt immediately reset

## planned features ##
plan to be able to select/ edit all nodes on a specific depth
plan to add a prompt for the node's children that will act as a question/else for the choices