#  Programming Assignments𓂃˖˳·˖ ִֶָ ⋆☄️⋆ ִֶָ˖·˳˖𓂃 ִֶָ 
This repository contains my programming assignments for **ECE 2112: Advanced Computer Programming and Algorithms**.

## ✧˖°. Contents

### ✨ [Experiment 1 – Introduction to Python Programming](EXPERIMENT1.ipynb) 
── .✦ This experiment introduces the basics of Python through three simple problems:
 
   Alphabet Soup
  - I created a function that takes a string and returns the string with its letters in alphabetical order.
  FUNCTION:
   def alphabet_soup(word):
    return ''.join(sorted(word))
  OUTPUT:
   print(alphabet_soup("hello"))      # Output: ehllo
   print(alphabet_soup("hacker"))     # Output: acehkr
   print(alphabet_soup("programming"))# Output: aggimmnoprr

  Emoticon Problem – replacing specific words in a sentence with their corresponding emoticons.
  - i created a function that replaces the words smile, grin, sad, and mad with corresponding emoticons in a given sentence.

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

  Unpacking List – separating a list into its first, middle, and last elements.

  Given a list, unpack its elements into three variables: first, middle, and last, where:
  first is the first element
  middle contains all elements in between
  last is the last element
  lst = [1, 2, 3, 4, 5, 6]

  first = lst[0]
  middle = lst[1:-1]
  last = lst[-1]

  print("first:", first)    # Output: 1
  print("middle:", middle)  # Output: [2, 3, 4, 5]
  print("last:", last)      # Output: 6

### 🗂️ File Structure

Experiment1.ipynb       # Jupyter notebook containing the code
README.md               # This file

## ⏔⏔⏔ ꒰ ᧔ෆ᧓ ꒱ ⏔⏔⏔


