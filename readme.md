# GitHub Classroom Autograding Test Lab

This lab is designed to test GitHub Classroom's autograding functionality with various scenarios including full credit, partial credit, failures, and edge cases.

## Exercises

### Exercise 1: Simple Pass Test (10 points)
**Objective**: Create a file named `exercise1.txt` with the word "PASS" inside.

**Requirements**:
- File must exist at the root of the repository
- File must contain exactly the word "PASS" (case-sensitive)

**Scoring**: All or nothing - 10 points if correct, 0 otherwise.

---

### Exercise 2: Partial Credit Test (20 points)
**Objective**: Create a file named `exercise2.txt` with answers to 4 questions.

**Requirements**:
Create `exercise2.txt` with the following format:
```
Q1: [your answer]
Q2: [your answer]
Q3: [your answer]
Q4: [your answer]
```

**Correct Answers**:
- Q1: 42
- Q2: GitHub
- Q3: Python
- Q4: Actions

**Scoring**: 5 points per correct answer (partial credit available).

---

### Exercise 3: Multiple Test Cases (15 points)
**Objective**: Create a Python file `calculator.py` with basic math functions.

**Requirements**:
Create `calculator.py` with the following functions:
```python
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b
```

**Scoring**: 5 points per working function (partial credit available).

---

### Exercise 4: Timeout Test (5 points)
**Objective**: Create a file named `exercise4.txt` with the word "QUICK".

**Requirements**:
- File must exist and contain "QUICK"
- This test has a very short timeout to test timeout handling

**Scoring**: All or nothing - 5 points if correct, 0 otherwise.

---

### Exercise 5: Error Handling Test (10 points)
**Objective**: Create a file named `exercise5.txt` with valid JSON.

**Requirements**:
- File must contain valid JSON
- JSON must have a field named "status" with value "success"

**Example**:
```json
{
  "status": "success",
  "message": "Test completed"
}
```

**Scoring**: All or nothing - 10 points if correct, 0 otherwise. Will return error if JSON is invalid.

---

### Exercise 6: Complex Rubric Test (30 points)
**Objective**: Create a comprehensive solution file `exercise6.txt` that will be evaluated on multiple criteria.

**Requirements**:
Create `exercise6.txt` with the following sections:
```
NAME: [Your name]
CODE: [Your code answer]
EXPLANATION: [Your explanation]
```

**Scoring Rubric**:
- NAME present: 10 points
- CODE section correct: 10 points
- EXPLANATION has at least 50 characters: 10 points

**Total possible**: 30 points (partial credit available based on rubric).

---

## Total Points
- Exercise 1: 10 points
- Exercise 2: 20 points
- Exercise 3: 15 points
- Exercise 4: 5 points
- Exercise 5: 10 points
- Exercise 6: 30 points

**Grand Total**: 90 points

---

## Testing Instructions

1. Create the required files according to each exercise specification
2. Commit and push your changes
3. GitHub Actions will automatically run the autograding tests
4. Check the Actions tab to see your score
5. Review feedback for each exercise

Good luck!
