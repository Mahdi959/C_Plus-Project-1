CS132 Lab 4
Spring 2022

Instructions: For this lab, you will use the code in the DList.cpp file and the DList.h file to make a list of items for a camera store, and implement functions to insert, find, erase, display items.  You will have to modify the code, since it was written for a list of integers.  The items for the list are in a file called InventoryFile.txt
	Each line of the file InventoryFile has the following format:
	
		Item Number – an integer
		Number in stock – an integer (between 0 and 999)
		Unit Price – a floating-point value
		Minimum inventory level – an integer
		Item name – a character string

	You will probably have to define a struct, to hold the info for each item, and then your list will be an array of the structs

	Your driver file should create the list, read in all the items, and then ask the user what to do (insert, delete, etc…)

	When you are done, the list should be output to a file called NewInventory.
