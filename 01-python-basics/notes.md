# 🐍 Python Basics — Angela Yu 100 Days of Code
> My Python learning journey as I transition to AI Testing Engineer

## 📋 Course Details
| Field          | Value                        |
|----------------|------------------------------|
| Instructor     | Angela Yu                    |
| Platform       | Udemy                        |
| Total Hours    | 60 hours                     |
| Hours Watched  | In Progress                  |
| Speed          | 1.75x                        |
| Started        | April 2026                   |
| Completed      | In Progress                  |
| Rating         | ⭐ Updating...               |

## 🎯 Why I Took This Course
I already have experience in testing but AI Testing needs Python.
This course helps me learn Python fast to become an AI Test Engineer.

---

## 📖 What I Learned

### Topic 1: Variables & Naming
**What it is:** A variable stores data so you can use it later.
Python doesn't need you to declare the type — it figures it out.

**Why it matters for AI Testing:**
Test data like usernames, passwords, expected results
are all stored in variables.

**Code example:**
```python
# Variable naming rules
name = "Chinnappa"        # string
age = 25                  # integer
is_tester = True          # boolean
pass_rate = 94.5          # float

# Good naming — clear and readable
user_name = "cn_crazy"
test_status = "pass"

# Bad naming — avoid this
x = "cn_crazy"
a = "pass"
**Key takeaway:** Always use clear names.

---
### Topic 2: Input from User
**What it is:** `input()` lets your program ask a question
and store the answer.

**Why it matters for AI Testing:**
Build tools that ask testers for data
instead of hardcoding everything.

**Code example:**
```python
# Input in a test tool
test_case = input("Enter test case name: ")
result = input("Did it pass? (yes/no): ")
print(f"Test: {test_case} — Result: {result}")
```
---

### Topic 3: String Manipulation
**What it is:** Changing, combining, or extracting
parts of text (strings).

**Why it matters for AI Testing:**
API responses come back as strings.
You'll slice, search, and format them constantly.

**Code example:**
```python
name = "chinnappa"

# Common string methods
print(name.upper())          # CHINNAPPA
print(name.capitalize())     # Chinnappa
print(len(name))             # 9
print(name.replace("a","@")) # chinn@pp@

# f-strings — best way to combine strings
test = "login_test"
status = "PASS"
print(f"Test: {test} | Status: {status}")
# Output: Test: login_test | Status: PASS

# Slicing
result = "PASS_login_test"
print(result[0:4])           # PASS
```
---

## 💡 Aha Moments
1. **No type declaration:** In Java you write `String name = "CN"`.
   In Python just `name = "CN"` — so clean!
2. **f-strings are magic:** `f"Result: {status}"` is so much
   easier than joining strings with `+`
3. **input() is always a string:** Spent time confused why
   maths wasn't working — because `"5" + "3" = "53"` not `8`!

## 🔨 How I Applied This
- Still in learning phase — project coming this weekend!

## ⭐ My Rating So Far: 9/10
**Pros:**
- Angela explains very clearly
- Good examples for beginners

**Would I recommend?** Yes — perfect for someone
coming from another language like Java


print("Hello CNP")


