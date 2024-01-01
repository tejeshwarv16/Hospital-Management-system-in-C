# Hospital Management System

This is a simple hospital management system implemented in C for managing patient records, hospital staff records, and inventory. 

## Features

- Add, edit, delete, and search patient records 
- Add, edit, delete, and search hospital staff records
- Add, edit, delete, and search inventory records
- View listings of all records
- Menu-driven interface

## Data Structures

The following structures are used:

- `struct address` - Contains address details 
- `struct patient` - Contains patient details
- `struct staff` - Contains staff details
- `struct inventory` - Contains inventory item details

## Files

- `hospital.c` - Main source code
- `pat.DAT` - Binary file to store patient records 
- `emp.DAT` - Binary file to store staff records
- `inv.DAT` - Binary file to store inventory records

## Usage

- Compile with `gcc hospital.c -o hospital`
- Run with `./hospital`
- Select options from main menu to add, edit, delete, search, or view records
- Patient, staff, and inventory functions are in separate modules
- Binary files are used to persist data across runs

## Note

This is a basic system meant for learning purposes. Proper validation, exceptions, modularization etc. needs to be added to make it robust.
