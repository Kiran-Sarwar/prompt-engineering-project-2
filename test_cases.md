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