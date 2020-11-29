# techtalent-academy-python-projects
Showcasing the code produced from this course
#Converting student mark from percentage to grade.

def mark_grade(mark):
    if mark >= 90:
        print("A*")
    elif mark >= 80:
        print("A")
    elif mark >= 70:
        print("B")
    elif mark >= 60:
        print("C")
    elif mark >= 50:
        print("D")
    else:
        print("You have failed.")

mark = int(input("Hello, please enter your mark: "))

mark_grade(mark)
