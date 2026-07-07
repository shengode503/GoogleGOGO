# Coding Interview SOP

> Goal: Follow the same structured process for every problem instead of jumping straight into coding.

---

# Step 1. Understand the Problem (1–2 min)

Do **not** start coding immediately.

Make sure you understand:

* What is the input?
* What is the expected output?
* What are the constraints?
* Can the input be modified?
* How large can the input be?

Ask clarifying questions if necessary:

* Can the input be empty?
* Can there be duplicate values?
* Is the input already sorted?
* Can I modify the input in-place?
* What are the input constraints?

---

# Step 2. Discuss the Brute Force Solution (1–2 min)

Start with the simplest approach.

Explain:

* How it works
* Time complexity
* Space complexity

Example:

> A straightforward solution is to compare every pair of elements. This takes **O(n²)** time and **O(1)** extra space.

---

# Step 3. Optimize the Solution (2–3 min)

Think about possible optimizations.

Consider whether you can use:

* Hash Map
* Hash Set
* Sorting
* Two Pointers
* Sliding Window
* Stack
* Queue
* DFS / BFS
* Binary Search
* Dynamic Programming
* Greedy

Explain the trade-offs.

Example:

> We can trade extra memory for faster lookups by using a hash map, reducing the time complexity to O(n).

---

# Step 4. Describe the Algorithm (1 min)

Before writing code, explain the algorithm in plain English.

Example:

1. Create a hash map.
2. Iterate through the array.
3. Check whether the complement exists.
4. Return the answer.

---

# Step 5. Implement the Solution

Write clean, readable code.

While coding, explain what you're doing.

For example:

* Here I'm creating the hash map.
* This loop builds the frequency table.
* Now I'm checking each element.
* Finally, I return the result.

Avoid long periods of silence.

---

# Step 6. Review Your Code (1 min)

Before saying you're done, quickly review your code.

Check for:

* Variable names
* Boundary conditions
* Off-by-one errors
* Missing return statements
* Incorrect dictionary lookups
* Syntax mistakes

---

# Step 7. Dry Run the Algorithm (2–3 min)

Walk through a sample input.

Example:

Input:

[2, 7, 11, 15]

Target:

9

Verify:

* Variable values
* Hash map contents
* Pointer movement
* Final output

---

# Step 8. Consider Edge Cases (1 min)

Think about cases such as:

* Empty input
* Single element
* Duplicate values
* All identical values
* All unique values
* Negative numbers
* Very large input

---

# Step 9. Analyze Complexity

Clearly state:

Time Complexity:

O(?)

Space Complexity:

O(?)

Briefly explain why.

---

# Step 10. Discuss Follow-up Questions

If time permits, think about possible improvements.

Examples:

* Can we reduce the space complexity?
* Can we make it faster?
* How would this work with streaming data?
* What if the dataset contains billions of records?
* What if the data cannot fit into memory?
* Can this solution be parallelized?

---

# Coding Checklist

Before coding:

☐ I fully understand the problem.

☐ I know the input and output.

☐ I understand the constraints.

☐ I have a brute-force solution.

☐ I have an optimized solution.

☐ I know the expected time complexity.

☐ I know the expected space complexity.

---

After coding:

☐ Review the code.

☐ Dry run the algorithm.

☐ Check edge cases.

☐ Analyze complexity.

☐ Discuss possible follow-ups.

---

# Golden Rules

1. Understand the problem before coding.
2. Think before you implement.
3. Communicate your thought process.
4. Write clean and readable code.
5. Test your solution mentally.
6. Analyze the complexity.
7. Stay calm if you get stuck.

> Interviewers evaluate more than just whether your solution passes. They also assess your problem-solving process, communication, code quality, and ability to reason about trade-offs.
