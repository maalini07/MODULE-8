# 🏆 Hackerrank:Runner-Up Score Finder in Python

## 🎯 AIM:
To write a Python program that takes a list of scores from participants and finds the **runner-up score** (i.e., the second-highest score), eliminating any duplicates.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a variable `n` and get its value from the user (number of participants)
3. Read the list of `n` scores from the user using `input().split()` and convert them to integers
4. Store the scores in a list
5. Use `set()` to remove any duplicate scores
6. Convert the set back to a list and sort it in ascending order
7. Print the second-last element of the sorted list (i.e., the runner-up score)
8. **Stop**

---

## 💻 PROGRAM:
```
def find_runner_up(scores):
    unique_scores = list(set(scores))  
    unique_scores.sort(reverse=True)  
    return unique_scores[1] 
n = int(input("Enter the number of participants: "))
scores = []
for _ in range(n):
    score = int(input(f"Enter score for participant {_+1}: "))
    scores.append(score)
runner_up = find_runner_up(scores)
print(f"\nThe runner-up score is: {runner_up}")
```

## OUTPUT
<img width="583" height="297" alt="444351934-6c2e2277-64ed-41ad-bbb5-c647490a894b" src="https://github.com/user-attachments/assets/50635f39-68e9-4f5e-aaec-454a157da38e" />

## RESULT
Thus, the program has executed successfully
