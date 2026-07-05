# User-Configuration-Manager

A simple Python project that simulates a user settings management system. The application allows users to manage configuration settings through basic CRUD (Create, Read, Update, Delete) operations using Python dictionaries.

This project was built as part of the **Python Certification** curriculum on freeCodeCamp to strengthen foundational Python programming skills, including working with dictionaries, functions, conditional statements, and string manipulation.

## Features

* Add new user settings
* View all current settings
* Update existing settings
* Delete settings
* Prevent duplicate settings from being added
* User-friendly feedback messages for each operation

## Technologies Used

* Python 3

## Example

Initial settings:

```python
test_settings = {
    "theme": "dark",
    "language": "isiXhosa",
    "notifications": "enabled"
}
```

Example operations:

```python
add_setting(dictionary, ("font_size", "large"))
update_setting(dictionary, ("theme", "light"))
delete_setting(dictionary, "language")
view_settings(dictionary)
```

## Learning Objectives

This project demonstrates how to:

* Work with Python dictionaries
* Create reusable functions
* Validate user input
* Perform CRUD operations
* Apply conditional logic
* Write clean, readable Python code


## Acknowledgements

This project was completed as part of the **Python Certification** offered by freeCodeCamp.

* freeCodeCamp Python Certification:
  https://www.freecodecamp.org/learn/python-v9/lab-user-configuration-manager/build-a-user-configuration-manager

## License

This project is open source and available under the MIT License.
