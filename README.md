# Steam Web Store Testing

This project was developed by a team of four students as part of a university Software Testing course. It focuses on functional and GUI testing of the Steam Web Store using manual testing techniques and Selenium IDE automation.

The project includes test case design, test execution, defect documentation, and automated testing.

## Technologies and Tools
- Selenium IDE
- Manual Testing
- Functional Testing
- GUI Testing

## Testing Scope
- Game Search
- Website Navigation
- Game Detail Pages
- Shopping Cart
- Wishlist
- User Login

## Test Design Techniques

### Equivalence Class Partitioning (ECP)
Used to divide search inputs into valid and invalid equivalence classes.

### Boundary Value Analysis (BVA)
Applied to search input boundaries to identify potential issues.

### Decision Table Testing
Used to evaluate different conditions and outcomes related to adding games to the shopping cart.

### Use Case Testing
Used to design test scenarios based on user interactions with the Steam Web Store.

## Test Automation

Selenium IDE was used to automate four test scenarios:

- TC-03: Valid Game Search
- TC-04: Invalid Game Search
- TC-09: Search and Add Game to Cart
- TC-10: Remove Item from Cart

All four automated tests passed during the documented test execution.

Login and wishlist automation were not included because Steam Guard and verification requirements made automated execution unreliable.

## Test Documentation

The repository contains:

- `Tables/` - Test cases, test design techniques, and issue documentation
- `Steam_Test_Project.side` - Selenium IDE automation project
- `SE2226_Test_Completion_Report.docx` - Test execution results and completion evaluation

## Test Results

- 12 test cases designed
- 4 Selenium IDE automated tests executed
- 4 automated tests passed
- Functional and GUI testing performed

## Project Information

This project was developed collaboratively by four Software Engineering students to gain practical experience in software testing methodologies, test case design, defect reporting, and browser-based test automation using Selenium IDE.
