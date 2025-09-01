# 🔺 Looping(Patterns)-Floyd's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Floyd’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Floyd's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Initialize a counter variable o = 1.
4. Loop from 1 to the number of rows.
5. For each row:
   - Loop through the columns of that row.
   - Print the current value of o.
   - Increment o by 1.
6. Print all rows of Floyd’s Triangle.
7. End the program.
---

## 🧪 Program
a=int(input())

o=1

for i in range (1,a+1):

    for j in range (1,i+1):
    
        print(o,end=(" "))
        
        o+=1
    
    print()

## Sample Output
<img width="742" height="647" alt="image" src="https://github.com/user-attachments/assets/79612d31-8665-4a47-9a55-0b15a23d3c08" />

## Result
Thus, This project demonstrates a simple Python program to generate **Floyd’s Triangle**, where the number of rows is provided by the user us verified
