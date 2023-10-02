# Part A

## Exploring ArrayLists in Java with Unit Testing

**Getting Started:**
Recall our discussion about arrays? Java offers an advanced tool called `ArrayList` that can adjust its size as needed. Today, we're diving into that, and to make sure your toolbox works perfectly, you'll learn to test it using unit tests!

**What You're Building:**
Imagine a toolbox that can keep your numbers, expand with more numbers, reduce when you eliminate some, and even provide a neat display of its contents. That's your mission for today!

**Steps:**

**1. Construct the `ArrayListBasics` Toolbox:**

- Design a tool named `ArrayListBasics`.
- Equip this toolbox to:
    - Initiate a new collection of numbers.
    - Add a range of numbers to this collection.
    - Remove a number from your collection using its position.
    - Neatly present what's currently inside the collection.

**2. Test the `ArrayListBasics` Toolbox:**

- Initialize with an empty collection.
- Populate it with a series of numbers (like 1, 2, 3, and so forth).
- Extract a number and reveal the modified collection.
- Neatly display the collection's contents.

**3. Confirm Your Toolbox Works:**

- For this, we'll use the `ArrayListBasicsTest` unit test. It's a way of checking that each part of your toolbox works as intended.
- After crafting your toolbox, run the `ArrayListBasicsTest`. If all tests pass, you've built a solid toolbox! If not, see where the issues lie and refine your code.

**Things to Consider:**

- Remember, `ArrayList` in Java is dynamic, unlike arrays with a fixed size.
- Ponder on the order of numbers when added. What transpires when you discard one?

**Extra Challenge:**

**Mix It Up!:** Fancy inserting a number somewhere in the middle? Or perhaps substituting one? Maybe even reversing the entire collection? Endeavor to infuse these features into your toolbox.

**How We'll Know You Nailed It:**

- You've grasped and utilized the potential of `ArrayList` in Java.
- Your `ArrayListBasics` toolbox proficiently administers a dynamic collection of numbers.
- Your code is sleek, efficient, and contemplates diverse scenarios.
- The `ArrayListBasicsTest` confirms the prowess of your toolbox.
- Tackling and conquering the extra challenge is a testament to your growing expertise.

**In Conclusion:**
Delving into Java's data structures is a thrilling voyage. The excursion with `ArrayList` is merely an introduction. Always scrutinize your tools with tests to guarantee their seamless operation. Happy coding and experimenting!

# Part B

## Venturing into Java Maps

**Getting Started:**  
Do you remember when we explored lists and arrays that maintain elements in a sequence? Now, let's move to something even cooler: `Maps`! Maps in Java allow you to store data in key-value pairs. Imagine having a dictionary where you look up a word (the key) to get its definition (the value). That's the essence of a Map!

**What You're Building:**  
You're about to construct a toolbox for managing such key-value pairs. Whether it's names and their phone numbers, countries and their capitals, or authors and their books, this toolbox will handle it all!

**Steps:**

**1. Design the `MapBasics` Toolbox:**

- Create a tool named `MapBasics`.
- This toolbox should be equipped to:
  - Start with an empty map.
  - Insert a key-value pair.
  - Remove a key-value pair using the key.
  - Retrieve a value using its key.
  - Show all key-value pairs in the map.

**2. Test the `MapBasics` Toolbox:**

- Initialize an empty map.
- Populate it with some key-value pairs. For instance, countries as keys and capitals as values.
- Remove a key and demonstrate the updated map.
- Fetch a specific value using its key.
- Display all pairs in your map.

**3. Validate Your Toolbox:**

- To be sure of your toolbox's capabilities, use the provided unit test, say `MapBasicsTest`.
- After setting up your toolbox, execute the `MapBasicsTest`. If all tests succeed, your toolbox is rock-solid! If not, identify the glitches and refine your creation.

**Things to Ponder:**

- `Maps` in Java offer methods like `put()`, `get()`, and `remove()` that can be invaluable for this lab.
- A key in a map is unique. What happens if you try to insert a duplicate key?

**Extra Challenge:**

**Deep Dive!:** Can you implement a method to fetch all the keys? Or maybe all the values? How about a method that checks if a particular key or value exists in the map? Go on, enhance your toolbox with these!

**How We'll Know You Did It Right:**

- You've delved deep into the world of Java Maps and harnessed their potential.
- Your `MapBasics` toolbox effectively manages key-value pairs.
- Your code is crisp, efficient, and prepared for various situations.
- Your success in the `MapBasicsTest` underlines the robustness of your toolbox.
- Engaging with the extra challenge showcases your depth of understanding.

**Concluding Notes:**  
Maps are a pivotal data structure in many real-world applications. From databases to caching systems, they're everywhere. By mastering maps, you're adding a significant tool to your programming arsenal. Make sure to always test your tools to ensure their perfection. Dive in and enjoy the world of Maps!

# Part C 

## Count Duplicates Challenge 🧩

### Introduction:
Sometimes, we come across situations where we have to count things that repeat. Think of it like going through a box of colored marbles and counting how many times each color repeats more than once.

In this challenge, you have to do something similar, but with characters in a string!

### The Challenge:
Given a string called `data`, your task is to count the number of characters that appear more than once. These characters are considered 'duplicates'.

For example:

If `data` is `"abcdefga"`, you should return the value of `1`. Why? Because the character `a` is the only one that repeats.

If `data` is `"xyzxyzxyz"`, you should return the value of `3`. That's because the characters `x`, `y`, and `z` all repeat multiple times.

### Hints 🚀:
If you're not sure where to start, think about how a map (or dictionary in some languages) works. It can store items with a unique key and a value. For this challenge, a `Map` can be extremely helpful. You can use characters as the unique keys and their count (number of times they appear) as values.

### How to get started 🏁:
1. Look at the `Problem` class provided in the `com.codedifferently` package. There's a method named `countDuplicates` which takes the string `data` as its parameter.
2. Fill in the logic in this method to solve the problem. Make sure it returns the correct count for the test cases.
3. Test your solution against the given tests in the `ProblemTest` class. Once all tests pass, pat yourself on the back!

Best of luck, and happy coding! 🌟
