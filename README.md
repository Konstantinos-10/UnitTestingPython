# Gotham Needs You
**Background Story:**

Gotham City is under threat! The notorious Joker has planted bugs in the Bat-Tech systems that keep Batman’s operations running smoothly. As a trusted member of Batman’s elite tech team, your mission is to write robust tests for critical components of the Bat-Tech software. Your testing skills will ensure that every gadget works flawlessly, from the Batmobile’s power calculations to the Bat-Signal’s reliability, and even monitor Joker’s mischief—all with the power of pytest.

**Objective:**
In this assignment, you will write tests for a provided Python module (bat_functions.py) using pytest. You’ll cover:
- Basic pytest syntax: Writing simple test functions and using assertions.
- Parametrization: Running tests with multiple input values.
- Fixtures: Creating reusable test setups.
- Mocking: Simulating external dependencies.
- Continuous Integration: Setting up a GitHub Actions workflow to run your tests on every push.

**Expectations:**
- Your tests should be clear, well-organized, and cover various edge cases.
- Use pytest best practices and include meaningful commit messages in your GitHub repository.
- The assignment is designed for beginners but requires careful attention to details discussed in the presentation.

## Exercise 1: Basic Tests and Parametrization
Write tests for calculate_bat_power and signal_strength functions:
- Task 1: Write a test function that verifies calculate_bat_power returns the correct power for different levels.
- Task 2: Use pytest parametrization to test signal_strength with various distances (e.g., 0 km, 5 km, 10 km, and 12 km).

## Exercise 2: Using Fixtures
Create a fixture that sets up a reusable dictionary of bat vehicles. Then:
- Write tests for get_bat_vehicle using this fixture.
- Verify that the function returns correct specifications for known vehicles and raises an error for unknown ones.

## Exercise 3: Mocking External Dependencies
Test the fetch_joker_info function:
- Write a test that uses mocking (with pytest’s monkeypatch or the pytest-mock plugin) to simulate a fast response from fetch_joker_info without waiting for the real 1-second delay.
- Ensure that your mock returns a custom dictionary (e.g., {'mischief_level': 0, 'location': 'captured'}) and verify that your test uses this mocked response.

## Exercise 4: Continuous Integration
Set up GitHub Actions to automatically run your tests:
- Create a GitHub Actions workflow file (e.g., .github/workflows/pytest.yml) that installs your dependencies and runs your tests on every push.
- Ensure the workflow runs on Ubuntu and uses a recent version of Python (e.g., Python 3.9 or 3.10).

# Submission Instructions
### Create a GitHub Repository:
Name your repository (e.g., bat-test-assignment) and commit all your files:
- bat_functions.py
- test_bat_functions.py
- .github/workflows/pytest.yml
Any additional documentation (e.g., a README.md describing your approach).

### Commit Guidelines:
Write clear, descriptive commit messages (e.g., "Add basic tests for calculate_bat_power", "Implement fixture for bat vehicles", "Set up GitHub Actions workflow").
Ensure your repository is organized and your code is commented where necessary.

### Push Your Repository:
Once you’re done, push your changes to GitHub. Make sure the repository is public (or provide access if private) so that it can be reviewed.

### Final Submission:
Tag me as a collaborator @Konstantinos-10 to grade it. 

### Thank You So Much
I hope you don't find it too difficult nor too easy. Appreciate you guys. 


Θα τελειώσω στα 6 χρόνια!!!!!

