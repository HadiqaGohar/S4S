# 🧪 Constraint-Based Prompt Testing Experiment (DeepSeek)

## 🎯 Objective
To test how well an AI follows strict constraints such as word count, reading level, banned words, and sentence structure.

---

## 🪜 Steps

### Step 1 · Action
Open DeepSeek.

---

### Step 2 · Action
Write a prompt that stacks at least 4 rules:

"Write a product description for a solar-powered desk fan for the Pakistani market. Constraints:  
1) exactly 60 words  
2) written at a grade-5 reading level  
3) must NOT use the words 'powerful' or 'innovative'  
4) end with a question."

---

### Step 3 · Action
Check each constraint manually:
- Word count  
- Banned words  
- Reading level  
- Ending punctuation  

---

### Step 4 · Action
If any rule fails, reply:
> "You broke rule N. Try again."

---

### Step 5 · Action
Save the compliant final version.

---

## 🧪 Attempts & Results

### ❌ Attempt 1
Beat the heat without the high bills. This solar desk fan runs on sun energy, so you save money. It works during load-shedding too. Quiet blades give a soft breeze for study or sleep. Easy to set up anywhere. Sturdy build lasts long. Perfect for homes, offices, or shops. Stay cool and help the planet. Isn’t that a smart choice for your family?

👉 Result: Rule 1 failed (word count incorrect)

---

### ❌ Attempt 2
This solar fan runs on sunlight. No electricity needed. It keeps you cool during load-shedding. Quiet blades help you study or sleep. Easy to move and set up. Saves your money on bills. Strong frame lasts for years. Great for homes, shops, or outdoor work. Stay comfortable without worry. Does this fan fit your daily needs?

👉 Result: Rule 1 failed (word count incorrect)

---

### ❌ Attempt 3
This solar fan runs on sunlight. No grid power needed. It keeps you cool when lights go out. Quiet blades help you focus or rest. Easy to place anywhere. Saves rupees on monthly bills. Strong build handles daily use. Great for home, shop, or stall. Stay comfortable without extra cost. Will this fan work for your hot days?

👉 Result: 58 words → Rule 1 failed

---

### ❌ Attempt 4 (Final Fixed Version)
This solar fan runs on sunlight. No grid power needed. It keeps you cool when lights go out. Quiet blades help you focus or rest. Easy to place anywhere. Saves rupees on monthly bills. Strong build handles daily use. Great for home, shop, or stall. Stay comfortable without extra cost every day. Will this fan work for your hot afternoons?

👉 Result: ✔ All rules passed

---

## 📊 Evidence Link
https://chat.deepseek.com/share/yhh2o7prbz5iprmybw

---

## 🧠 Key Insights

- AI struggles with exact constraints like word count
- Iteration improves accuracy but does not guarantee precision
- Manual verification is essential for rule-based tasks

---

## 🚀 Conclusion

Constraint-heavy prompting requires:
- strict instructions
- self-check mechanisms
- manual validation

Even advanced AI models can make small counting errors, so verification is necessary for accurate results.
