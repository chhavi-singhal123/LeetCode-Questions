# 🚀 LeetCode Solutions in Java

Welcome to my LeetCode solutions repository!  
This repository contains my Java solutions for LeetCode problems with clean and optimized code.

---

## 📌 About

- 💻 Language: Java
- 📚 Platform: LeetCode
- 🎯 Goal: Improve DSA & problem-solving skills
- 🔥 Regular problem uploads

---

## 📂 Folder Structure

```bash
LeetCode-Solutions/
│
├── Arrays/
├── Strings/
├── LinkedList/
├── Trees/
├── Graphs/
├── DynamicProgramming/
├── BinarySearch/
└── README.md
```

---

## 🧠 Topics Covered

- Arrays
- Strings
- Linked Lists
- Trees
- Graphs
- Dynamic Programming
- Binary Search
- Sliding Window
- Recursion
- Greedy Algorithms

---

## ✅ Example Solution

```java
class Solution {
    public int mySqrt(int x) {
        if (x == 0 || x == 1) {
            return x;
        }

        int left = 1;
        int right = x;
        int ans = 0;

        while (left <= right) {
            int mid = left + (right - left) / 2;
            long square = (long) mid * mid;

            if (square == x) {
                return mid;
            } 
            else if (square < x) {
                ans = mid;
                left = mid + 1;
            } 
            else {
                right = mid - 1;
            }
        }

        return ans;
    }
}
```

---

## 📈 Progress

| Difficulty | Problems Solved |
|------------|----------------|
| 🟢 Easy    | XX |
| 🟡 Medium  | XX |
| 🔴 Hard    | XX |

---

## 🎯 Goals

- Solve problems consistently
- Strengthen DSA concepts
- Prepare for coding interviews
- Improve coding efficiency

---

## ⭐ Support

If you like this repository, give it a ⭐ on GitHub!

---

## 👩‍💻 Author

**Chhavi Singhal**

Passionate about:
- Full Stack Development
- Data Structures & Algorithms
- Problem Solving
- Software Development

---

# 🚀 Happy Coding!
