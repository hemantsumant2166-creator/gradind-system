# gradind-system

# Grade Calculator 🎓📊

This is a simple Python program that takes a student's marks as input and assigns a grade based on predefined ranges. The grade is printed as output.

## How it Works ⚙️

- The program takes an integer input representing the student's marks.
- Based on the input, the program assigns a grade using the following criteria:
  - **A+** if marks are between 81 and 90.
  - **A** if marks are between 71 and 80.
  - **B** if marks are between 61 and 70.
  - **Fail** if marks are below 33.

## Code Snippet 💻

```python
a = int(input("Enter the marks: "))
if 90 > a > 80:
    print("Grade = A+")
elif 80 > a > 70:
    print("Grade = A")
elif 70 > a > 60:
    print("Grade = B")
elif 33 < a:
    print("Fail")
Sample Output 🖥️
1. If the user enters marks 85:
Grade = A+
2. If the user enters marks 75:
Grade = A
3. If the user enters marks 65:
Grade = B
4. If the user enters marks 25:
Fail
Requirements 📋
Python 3.x installed on your computer.

How to Run 🏃‍♂️
Copy the Python code into a file, e.g., grade_calculator.py.

Run the file using Python:

python grade_calculator.py
Input the marks when prompted.

The program will display the corresponding grade.

License 📜
This project is licensed under the MIT License - see the LICENSE file for details.

Made with ❤️ by [HEMANT SUMANT] 👨‍💻

This README provides a clear explanation of how the program works, sample inputs/outputs, and instructions for running it. Let me know if you'd like any changes or additions! 😊





