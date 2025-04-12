# Python IP Address Access Control Algorithm

## Project Overview
This project demonstrates my ability to develop a Python algorithm that automates the management of IP address access controls in a healthcare security context. I created a solution that reads an allow list file, filters out unauthorized IP addresses, and updates the file to enforce access restrictions to sensitive patient information.

## Security Context
A healthcare company implements access control via an allow list containing IP addresses authorized to access restricted patient information. Each employee is assigned a designated IP address. The allow list file, named "allow_list.txt", stores these authorized IP addresses. A separate list variable remove_list identifies IP addresses that should no longer have access privileges. 

This automation improves the company's security posture by ensuring prompt removal of access privileges while reducing the risk of human error when updating the access controls.

## Project Components
This project folder contains:

- **Python_Access_Control_Algorithm**: Detailed documentation of the algorithm development process
- **code-samples/**: Folder containing relevant code and sample allow list file:
  - **allow_list_update.py**: The complete Python script implementing the access control algorithm
  - **allow_list.txt**: Sample allow list file containing the original IP addresses used by the algorithm. Simply running the Python script will update this file by removing the unauthorized IP addresses from the list.

## Algorithm Components
My Python algorithm completes the following operations:

1. **Open the allow list file** - Uses the `with` statement and Python's built-in `open()` function with the "r" operation mode to securely read the file contents

2. **Read and convert file contents** - Applies the `.read()` method to convert the file contents to a string stored in the `ip_addresses` variable

3. **Convert string to list** - Implements the `.split()` method to transform the string of IP addresses into a list for easier manipulation

4. **Filter unauthorized IP addresses** - Employs a list comprehension to efficiently filter out any IP addresses that appear in the `remove_list`

5. **Convert list back to string** - Uses the `.join()` method with the newline separator to prepare the filtered IP addresses for file writing

6. **Update the allow list file** - Implements a second `with` statement with the "w" operation mode to securely overwrite the file with the updated list

## Key Technical Skills Demonstrated
- File operations (reading, writing, and manipulation)
- String and list manipulations in Python
- List comprehensions for efficient data filtering
- Secure file handling using `with` statements
- Algorithm development for security automation

## Security Benefits
This algorithm provides several security benefits:
- Ensures consistent and error-free updates to access control lists
- Reduces potential for human error in security administration
- Automates the prompt removal of access for unauthorized IP addresses
- Maintains the integrity of access controls
- Follows best practices for file handling to prevent resource leaks

## Implementation Details
The algorithm uses Python best practices including:
- Efficient data structure conversions
- Proper file handling with automatic cleanup
- Pythonic code syntax (list comprehensions)
- Clear variable naming and organization
- Comprehensive and detailed comments explaining functionality

This project illustrates my ability to create practical security solutions using Python, automating critical access control tasks while maintaining secure coding practices.