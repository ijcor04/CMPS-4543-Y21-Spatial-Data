# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:` append()

2. How can you remove an item from a list by value?  
   `Answer:` remove()

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` [2,4,6,8]

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.
```
my_list = [pizza, chicken, popcorn]
my_list.append("burger")
my_list.remove("pizza")
print(my_list)

---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` Lists are changeable (mutable), tuples are not.

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` No, because tuples are not meant to be changed once created.
---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
```
my_tuple = (23, 24, 8)
x,y,z = my_tuple
print(x,y,z)

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` get just looks for a key, without throwing errors if no key exixts. 

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` use a for loop and .items, (for key, value in dictionaryname.items(): )

---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
```
my_dictionary = {'name' : 'Isaiah', 'age' : 21, 'major' : 'computer science'}
for key, value in my_dictionary.items():
   print(key, ':', value)

---

## 🧾 Submit Checklist

- [ X ] I practiced creating and modifying lists.
- [ X ] I understand how tuples are different from lists.
- [ X ] I accessed and looped through dictionary items.
