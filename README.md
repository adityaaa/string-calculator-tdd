# string-calculator-tdd
A Python implementation of the String Calculator Kata using TDD principles.

1. Project Title and Description
Title: Use the repository name or a descriptive title.

# String Calculator TDD Kata
A Python implementation of the String Calculator Kata using Test-Driven Development (TDD) principles.

2. Features
Highlight key features or requirements met by the project.
markdown

## Features
- Adds numbers from a string input with comma or newline delimiters.
- Supports custom delimiters.
- Handles negative numbers by raising exceptions.
- Follows TDD best practices with comprehensive test coverage.

3. Installation
Provide instructions to set up the project locally.
markdown
 
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/adityaaa/string-calculator-tdd.git
Navigate to the project directory:

 
cd string-calculator-tdd
Install dependencies:

 
pip install -r requirements.txt
(Optional: If you don't use any external dependencies, skip this step.)
 
4. Usage
Provide details on how to run the program or tests.
 
## Usage
Run the program:

python string_calculator.py

Run tests:
 
pytest
 
5. Examples
Show a few examples of how the program works.
 
## Examples
Input: `""`  
Output: `0`

Input: `"1,2,3"`  
Output: `6`

Input: `"//;\n1;2"`  
Output: `3`

Input: `"1,-2,3"`  
Output: `Exception: Negative numbers not allowed: -2`


6. Development Workflow
Explain how TDD was used in the project.
 
## Development Workflow
- Started with the simplest case of an empty string.
- Added tests incrementally for each feature.
- Refactored code after each passing test to ensure clean, maintainable code.
- Frequent commits were made to document the evolution of the code.


7. Contributing
Add a short note on contributing, if applicable.
 
## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.


8. License
Mention the license if you added one while creating the repository.
 
## License
This project is licensed under the MIT License - see the LICENSE file for details.


9. Contact
Provide your contact information if reviewers need to reach out.
markdown
 
## Contact
Created by [Aditya R](https://github.com/adityaaa) - feel free to reach out!
