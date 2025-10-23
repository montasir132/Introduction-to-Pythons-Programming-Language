````markdown
# 🐍 Python C2 Assignment

এই অ্যাসাইনমেন্টটি **Python** ভাষার বেসিক প্রোগ্রাম অনুশীলনের জন্য তৈরি করা হয়েছে।  
প্রতিটি প্রশ্নের জন্য আলাদা প্রোগ্রাম লেখা হয়েছে যেখানে **input নেওয়া, output দেওয়া এবং গাণিতিক অপারেশন করা** শেখানো হয়েছে।

> 📖 এই অ্যাসাইনমেন্টটা মূলত খাতায় লিখে জমা দিতে হবে।  
> কোড লেখার সময় নিচে দেওয়া `#` চিহ্ন দিয়ে লেখা **comment** গুলো খাতায় লিখবে না — এগুলো শুধু বোঝার সুবিধার জন্য রাখা হয়েছে।

---

## 🧠 Comment (`#`) কী এবং এর কাজ কী?

Python-এ `#` দিয়ে শুরু হওয়া লাইনগুলোকে **comment** বলা হয়।  ( যিনি কোড করছে সে যাতে বুঝতে পারে কি করতাছে সে তাই একটা মেসেজ আকারে স্টেপ বাই স্টেপ রাখা)
কমেন্ট আসলে **কোড ব্যাখ্যা করার জন্য ব্যবহৃত হয়**, প্রোগ্রাম চালানোর সময় Python এগুলো **ignore করে**।  
মানে এগুলো শুধু মানুষের জন্য—কম্পিউটারের জন্য নয়।

**উদাহরণ:**
```python
# এটি একটি কমেন্ট
print("Hello World")  # এটিও একটি কমেন্ট
````

> 💡 অ্যাসাইনমেন্ট করার সময় কমেন্ট বাদ দিয়ে শুধু প্রোগ্রামের নাম মূল কোড ইনপুট আউটপুট লিখবে।

---

## 📚 Assignment Questions & Code Summary

---

### 🧩 1. [নাম এবং রোল প্রিন্ট কর](assignment_1.py)

**Description:**
এই প্রোগ্রামে ব্যবহারকারীর নাম এবং রোল ইনপুট নিয়ে সেগুলো স্ক্রিনে প্রিন্ট করা হয়েছে।

```python
# Program - 1
n = str(input("Enter Your Name : "))
r = int(input("Enter Your Board Roll : "))
print("Name :-", n, "\nBoard Roll :-", r)
```

**Input:**

```
Montasir
245456
```

**Output:**

```
Name :- Montasir
Board Roll :- 245456
```

---

### ➕➖✖️➗ 2. [দুইটি সংখ্যার যোগ, বিয়োগ, গুণ, ভাগ](assignment_2.py)

**Description:**
দুইটি সংখ্যা ইনপুট নিয়ে তাদের উপর চারটি মৌলিক গাণিতিক অপারেশন (যোগ, বিয়োগ, গুণ, ভাগ) করা হয়েছে।

```python
# Program - 2
a = int(input("Enter your first number : "))
b = int(input("Enter your second number : "))
sum = a + b
sub = a - b
mul = a * b
div = a / b
print("The sum of", a, "and", b, "=", sum)
print("The subtraction of", a, "and", b, "=", sub)
print("The multiplication of", a, "and", b, "=", mul)
print("The division of", a, "and", b, "=", div)
```

**Input:**

```
10
5
```

**Output:**

```
The sum of 10 and 5 = 15
The subtraction of 10 and 5 = 5
The multiplication of 10 and 5 = 50
The division of 10 and 5 = 2.0
```

---

### 🔲 3. [চতুর্ভুজের ক্ষেত্রফল](assignment_3.py)

**Description:**
দৈর্ঘ্য ও প্রস্থ ইনপুট নিয়ে চতুর্ভুজের ক্ষেত্রফল নির্ণয় করা হয়েছে।

```python
# Program - 3
length = int(input("Enter length: "))
width = int(input("Enter width: "))

area = length * width
print("Area of Rectangle:", area)
```

**Input:**

```
5
2
```

**Output:**

```
Area of Rectangle: 10
```

---

### 🔺 4.  [ত্রিভুজের ক্ষেত্রফল](assignment_4.py)

**Description:**
ভিত্তি (base) ও উচ্চতা (height) ইনপুট নিয়ে ত্রিভুজের ক্ষেত্রফল নির্ণয় করা হয়েছে।

```python
# Program - 4
base = float(input("Enter base: "))
height = float(input("Enter height: "))

area = 0.5 * base * height
print("Area of Triangle:", area)
```

**Input:**

```
2
10
```

**Output:**

```
Area of Triangle: 10.0
```

---

### ⬜ 5. [বর্গক্ষেত্রের ক্ষেত্রফল](assignment_5.py)

**Description:**
একটি বাহুর দৈর্ঘ্য ইনপুট নিয়ে বর্গক্ষেত্রের ক্ষেত্রফল নির্ণয় করা হয়েছে।

```python
# Program - 5
side = int(input("Enter side length: "))

area = side * side
print("Area of Square:", area)
```

**Input:**

```
10
```

**Output:**

```
Area of Square: 100
```

---

### 🌡️ 6. [সেলসিয়াস থেকে ফারেনহাইট রূপান্তর](assignment_6.py)

**Description:**
সেলসিয়াস তাপমাত্রা ইনপুট নিয়ে সেটি ফারেনহাইটে রূপান্তর করা হয়েছে।

```python
# Program - 6
celsius = float(input("Enter temperature in Celsius: "))

fahrenheit = (celsius * 1.8) + 32
print("Temperature in Fahrenheit:", fahrenheit)
```

**Input:**

```
88
```

**Output:**

```
Temperature in Fahrenheit: 190.4
```

---

## 📌 Summary

এই ছয়টি প্রোগ্রাম Python-এর সবচেয়ে বেসিক ধারণাগুলো শেখায়:

* **input()** দিয়ে ব্যবহারকারীর কাছ থেকে ডেটা নেওয়া
* **print()** দিয়ে আউটপুট দেখানো
* **গাণিতিক অপারেশন** (+, -, *, /) করা
* **float ও int** টাইপ ব্যবহার করা
* এবং **কমেন্ট** দিয়ে কোড বোঝানো।

---

> ✍️ **Tips:** অ্যাসাইনমেন্ট লেখার সময় কোডের মধ্যে থাকা `#` দিয়ে শুরু হওয়া লাইনগুলো বাদ দিয়ে কেবল মূল প্রোগ্রামটাই লিখবে।

```

---

তুমি চাইলে আমি এর সাথে একটা `assignment_c2.py` ফাইলও বানিয়ে দিতে পারি যেখানে এই ৬টা প্রোগ্রাম একসাথে থাকবে—GitHub repo তে রাখতে সুবিধা হবে।  
তুমি কি চাও আমি সেটাও বানিয়ে দিই?
```
