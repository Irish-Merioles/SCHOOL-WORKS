#  Programming Assignments𓂃˖˳·˖ ִֶָ ⋆☄️⋆ ִֶָ˖·˳˖𓂃 ִֶָ 
This repository contains my programming assignments for **ECE 2112: Advanced Computer Programming and Algorithms**.

## ✧˖°. Contents

### ✨ [Experiment 1 – Introduction to Python Programming](EXPERIMENT1.ipynb) 
── .✦ This experiment introduces the basics of Python through three simple problems:
 
#### Alphabet Soup
1. Define a function `alphabet_soup` that takes a string and returns its letters in alphabetical order.  
2. Use `sorted()` to get characters in order, then `''.join(...)` to make a string again.

```python
def alphabet_soup(text):  
    return ''.join(sorted(text))  
 ```
 
Output
```python
print(alphabet_soup("hello"))      # ehllo
 ```
#### Emoticon Problem

1. Create a mapping (dictionary) of words → emoticons.
2. Split the sentence into words, replace any word found in the mapping, then join back.

```python
def emotify(sentence):
    emoticons = {
        "smile": ":)",
        "grin": ":D",
        "sad": ":(",
        "mad": ">:("
    }
    words = sentence.split()
    result = [emoticons.get(word, word) for word in words]
    return " ".join(result)
 ```
#### Unpacking List

1. Given a list, extract the first, everything in the middle, and the last element.
2. Use indexing and slicing so it works even if you don't want starred-unpacking.
```python
lst = [1, 2, 3, 4, 5, 6]

first = lst[0]
last  = lst[-1]
middle = lst[1:-1]

print("first:", first)   # first: 1
print("middle:", middle) # middle: [2, 3, 4, 5]
print("last:", last)     # last: 6
 ```
### *How to run (locally / in Jupyter)*

Put your notebook file Experiment1.ipynb in the experiments/ folder (or repo root).

Start Jupyter:

Open  [Experiment 1](EXPERIMENT1.ipynb) and run the cells.

## ⏔⏔⏔ ꒰ ᧔ෆ᧓ ꒱ ⏔⏔⏔


