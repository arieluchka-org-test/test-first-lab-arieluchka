# Test Solutions for GitHub Classroom Autograding

This directory contains sample test files to verify the autograding functionality.

## Test Files

### Full Score Scenario
- `exercise1.txt` - Contains "PASS" (10/10 points)
- `exercise2.txt` - All correct answers (20/20 points)
- `calculator.py` - All functions working (15/15 points)
- `exercise4.txt` - Contains "QUICK" (5/5 points)
- `exercise5.txt` - Valid JSON with correct status (10/10 points)
- `exercise6.txt` - All rubric criteria met (30/30 points)

**Total: 90/90 points**

### Partial Credit Scenario
To test partial credit, modify the files to have some correct and some incorrect answers.

### Failure Scenarios
To test failures:
- Delete a file to test "file not found"
- Change content to incorrect values
- Make JSON invalid for exercise 5
- Remove required sections from exercise 6

## Testing Different Scenarios

### Scenario 1: Perfect Score
All files present with correct content - should get 90/90 points.

### Scenario 2: Partial Credit (Exercise 2)
Modify `exercise2.txt` to have only 2 correct answers - should get 10/20 points for that exercise.

### Scenario 3: Partial Credit (Exercise 3)
Modify `calculator.py` to have only `add()` function working - should get 5/15 points.

### Scenario 4: Partial Credit (Exercise 6)
Modify `exercise6.txt` to have only NAME and CODE sections - should get ~20/30 points.

### Scenario 5: JSON Error
Make `exercise5.txt` contain invalid JSON - should get error status with 0 points.

### Scenario 6: Missing Files
Delete one or more files - each missing file should report 0 points with appropriate message.

## How to Test

1. Create a new repository from the assignment template
2. Add/modify the test files according to the scenario you want to test
3. Commit and push
4. Check the Actions tab to see the autograding results
5. Verify the score shown matches the expected result

## Expected Workflow Behavior

The workflow should:
1. Run all 6 exercises independently
2. Each exercise should output a JSON result
3. The reporter should aggregate all results
4. Final score should be displayed in the format "Points X/90"
5. Individual test feedback should be visible in the Actions log
