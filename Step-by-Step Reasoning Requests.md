# 🧪 Reasoning Prompt Comparison Experiment (DeepSeek)

## 🎯 Objective

To compare a normal prompt with a reasoning-focused prompt and evaluate differences in accuracy, clarity, and explanation quality.

---

## Step 1 · Action

Open DeepSeek.

---

## Step 2 · Action

Baseline Prompt:

> A train leaves Lahore for Karachi at 8 AM at 80 km/h. Another leaves Karachi for Lahore at 9 AM at 100 km/h. Distance is 1200 km. When do they meet?

### Baseline Result

DeepSeek calculated that the trains meet at:

**3:13:20 PM**

---

## Step 3 · Action

Open a new chat and use:

> Solve this step by step, showing every calculation. A train leaves Lahore for Karachi at 8 AM at 80 km/h. Another leaves Karachi for Lahore at 9 AM at 100 km/h. Distance is 1200 km. When do they meet?

### Step-by-Step Result

DeepSeek provided:

1. Train A travels 80 km before Train B starts.
2. Remaining distance = 1200 − 80 = 1120 km.
3. Relative speed = 80 + 100 = 180 km/h.
4. Time to meet after 9 AM = 1120 ÷ 180 = 56/9 hours.
5. 56/9 hours = 6 hours 13 minutes 20 seconds.
6. Meeting time = 9:00 AM + 6h 13m 20s = **3:13:20 PM**.

---

## Step 4 · Action

Compare Accuracy and Clarity

| Aspect               | Baseline Answer | Step-by-Step Answer |
| -------------------- | --------------- | ------------------- |
| Accuracy             | Correct         | Correct             |
| Explanation          | Minimal         | Detailed            |
| Calculations Shown   | No              | Yes                 |
| Ease of Verification | Low             | High                |
| Educational Value    | Low             | High                |

### Observation

Both answers produced the same meeting time, but the step-by-step prompt made the reasoning process transparent and easier to verify.

---

## Step 5 · Action

Verify by Manual Calculation

### Manual Solution

Distance covered by Train A before 9 AM:

80 × 1 = 80 km

Remaining distance:

1200 − 80 = 1120 km

Relative speed:

80 + 100 = 180 km/h

Time after 9 AM:

1120 ÷ 180 = 56/9 hours

56/9 hours = 6 hours 13 minutes 20 seconds

Meeting time:

9:00 AM + 6h 13m 20s

= **3:13:20 PM**

### Verification Result

The mathematically correct meeting time is:

**3:13:20 PM**

Note: The assignment sheet listed **2:48 PM**, but based on the provided speeds and distance, that answer is incorrect. Manual calculation and DeepSeek both confirm **3:13:20 PM**.

---

## 🧠 Key Insight

Adding phrases such as:

> "Solve this step by step, showing every calculation"

encourages the model to expose its reasoning process, making answers easier to understand, verify, and learn from.

---

## 🚀 Conclusion

The reasoning-focused prompt produced a clearer and more educational answer while maintaining the same accuracy as the baseline response.

---

## 📊 Proof

DeepSeek Share Link:

https://chat.deepseek.com/share/sfh1zkwjotr5lvmysz
