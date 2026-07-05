# Test Cases

## Purpose

The following test cases evaluate the effectiveness of the Chain-of-Thought (CoT) prompt. Each test is designed to examine the model's reasoning, self-correction, and ability to avoid common logic traps.

---

## Test Case 1

### Question

A farmer has 17 sheep. All but 9 die. How many sheep are left?

### Expected Answer

9 sheep are left.

### Why this test?

This is a classic logic trap. It checks whether the AI understands the wording instead of performing unnecessary calculations.

---
### AI Output

**Final Answer:** 9 sheep are left.

**Brief Explanation:** The phrase "All but 9 die" means everyone except 9 dies. Therefore, 9 sheep remain alive.

**Confidence Level:** High

### Result

✅ Passed

The prompt successfully guided the AI to interpret the wording correctly instead of treating it as a mathematical calculation.

---

## Test Case 2

### Question

If five machines make five toys in five minutes, how long will 100 machines take to make 100 toys?

### Expected Answer

5 minutes

### AI Output

**Final Answer:** 5 minutes

**Brief Explanation:** Each machine makes one toy in five minutes. Therefore, 100 machines working simultaneously will produce 100 toys in the same five minutes.

**Confidence Level:** High

### Result

✅ Passed

The AI correctly applied proportional reasoning and avoided the common mistake of assuming that more machines require more time.

### Why this test?

This test evaluates the model's understanding of proportional reasoning and parallel processing rather than simple arithmetic.

---

## Test Case 3

### Question

Emily's father has three daughters: Anna, Bella, and...?

### Expected Answer

Emily

### AI Output

**Final Answer:** Emily

**Brief Explanation:** The question states "Emily's father has three daughters," meaning Emily is one of the daughters. The other two are Anna and Bella, so the third daughter is Emily.

**Confidence Level:** High

### Result

✅ Passed

The AI correctly identified the hidden clue in the question instead of guessing another name.

### Why this test?

This test evaluates whether the model carefully reads the question and identifies implicit information rather than making assumptions.

---

## Test Case 4

### Question

Some months have 31 days. How many months have 28 days?

### Expected Answer

12 months

### AI Output

**Final Answer:** 12 months

**Brief Explanation:** Every month has at least 28 days. Although some months have 30 or 31 days, all 12 months include a 28th day.

**Confidence Level:** High

### Result

✅ Passed

The AI correctly interpreted the wording of the question and avoided the common trick of answering "1 month."

### Why this test?

This test evaluates whether the model carefully analyzes the wording instead of relying on assumptions.

---

## Test Case 5

### Question

A train travels at 60 km/h for 2 hours and then at 80 km/h for 3 hours. What is the average speed for the entire journey?

### Expected Answer

72 km/h

### AI Output

**Final Answer:** 72 km/h

**Brief Explanation:** The total distance is (60 × 2) + (80 × 3) = 360 km. The total travel time is 5 hours. Therefore, the average speed is 360 ÷ 5 = 72 km/h.

**Confidence Level:** High

### Result

✅ Passed

The AI correctly calculated the total distance, total time, and average speed using a step-by-step approach.

### Why this test?

This test evaluates the model's ability to perform multi-step mathematical reasoning accurately.