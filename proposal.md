# PC Part Store Inventory Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  

- Create a data structure that will be used to help track inventory for an online PC parts store.

Describe at a high level a program that could solve that problem.

- An implementation of a hash table with AVL tree buckets will be used to store this information.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

PC Part Store Inventory Tracker


2. Output: Describe the output your program will produce.  Include and example format of the output produced.

Inventory Information

- Price

- Current inventory

- Warehouse Location  

- Item Description

- Item Name


Example:

Nvidia GTX 2080TI

$1199.00

Boost Clock: 1582 MHz

Current Inventory: 15 in stock

Warehouse Location: Shelf-G, Bucket-42


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Menu option chosen by the user, and then the item serial number.

Example:


Would you like to do:

A - add an item to the inventory

M - modify a current item's information

D - delete an item from the inventory

--if add has been chosen

########(serial number auto-generated)

(all of these questions will be separate prompts)

Item name?

Item price?

Item description?

Number in stock?

Warehouse location?

--if modify has been chosen

What would you like to modify:

N - change item name

P - change item price

D - change item description

S - change the number currently in stock

L - change the item's warehouse location

--if delete has been chosen

Please enter the serial number of the item to delete.



4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
We are using text menus.

- The first menu would have an add option, a modify option and a delete option.

- If motify option is chosen, the menu would have name, description, price, current inventory and current location.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

- A hash table to store all the data.

- A node to represent each item.

- An AVL tree for bucket.

- We'll focus on a good hash function.

Name each interface or class and briefly describe its function or purpose.

- A hash table to hold key values

- An AVL tree for bucket.

## Edit and Submit this file and any figures referenced by this document.

