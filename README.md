# Tool Used
Postman

# How to Run the Tests
- Install Postman (https://www.postman.com/downloads/)

# steps
- clone this repo (git clone <your-repo-url>)
- open postman
- import all of three json file
    - Positive Test Case.postman_collection.json
    - Negative Test Case.postman_collection.json
    - Edge Test Case.postman_collection.json
- after import, click Run in each collection


# Approach

- Test Scenarios
Before make a test, i analyzed the end point to make a test scenario that include positive (vallid input), negative (invalid input), and edge (boundary data) testcase.

- API testing
i use postman to make scenario with automated script using pm.test() (response status, data type, and data structure)

- Bug Documentation
when testing i find that in POST posts theres some bug in there (no input validation).





