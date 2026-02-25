# 🌐 CMPS 302 — Web Application 6: JavaScript Timer & Array Manipulation

> **Course:** CMPS 302 – Web Development  
> **Institution:** American University of Beirut (AUB)  
> **Week:** 7  
> **Topic:** JavaScript — Timers & Array Manipulation

---

## 📋 Assignment Overview

This assignment focuses on practicing **JavaScript timer control** and **array manipulation** through two hands-on exercises that modify provided starter code.

---

## 📁 Project Structure

```
webactivity6/
├── timer.html    ← Exercise 1: Countdown Timer
└── array.html    ← Exercise 2: Array Multiplication
```

---

## 🔧 Exercise 1 — Countdown Timer (`timer.html`)

### Objective
Convert an **incrementing** timer into a **decrementing countdown** from **100 to 0**, stopping automatically when it reaches zero.

### Changes Made
| # | Modification | Detail |
|---|-------------|--------|
| 1 | Initial display value | Changed `<strong>` content from `0` → `100` |
| 2 | Variable initialization | Set `var seconds = 100;` |
| 3 | Decrement logic | Changed `seconds + 1` → `seconds - 1` |
| 4 | Interval variable | Defined `var interval;` to store the timer reference |
| 5 | Stop condition | Added `if (seconds == 0) { clearInterval(interval); }` |

### Key Concepts
- **`window.setInterval()`** — Executes a function repeatedly at a specified interval (1000ms = 1 second)
- **`clearInterval()`** — Stops a running interval using its stored reference
- **DOM Manipulation** — Updating `innerHTML` to reflect the countdown in real-time

---

## 🔧 Exercise 2 — Array Multiplication (`array.html`)

### Objective
Modify the array manipulation function to **subtract 1** from each element, then **multiply** all results together instead of summing them.

### Changes Made
| # | Modification | Detail |
|---|-------------|--------|
| 1 | Initial accumulator | Changed `var s = 0;` → `var s = 1;` (multiplicative identity) |
| 2 | Subtract before multiply | Added `a[i] = a[i] - 1;` before the multiplication |
| 3 | Multiplication operator | Changed `s += a[i]` → `s *= a[i]` |
| 4 | Display operator | Changed `" +\n"` → `" *\n"` |

### Example Output
```
Array: [2, 6, 8, 10]
After subtracting 1: [1, 5, 7, 9]
Result: 1 * 5 * 7 * 9 = 315
```

### Key Concepts
- **Array traversal** — Iterating through array elements with a `for` loop
- **In-place modification** — Modifying array elements directly (`a[i] = a[i] - 1`)
- **Accumulator pattern** — Using a running product instead of a running sum

---

## 🚀 Live Demo

🔗 **GitHub Pages:** [View Live Demo](https://DatariusAI.github.io/cmps302_week_7_web_application_6_JavaScript/webactivity6/timer.html)

| Page | Link |
|------|------|
| Timer | [timer.html](https://DatariusAI.github.io/cmps302_week_7_web_application_6_JavaScript/webactivity6/timer.html) |
| Array | [array.html](https://DatariusAI.github.io/cmps302_week_7_web_application_6_JavaScript/webactivity6/array.html) |

---

## 🛠️ Technologies Used

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📝 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/DatariusAI/cmps302_week_7_web_application_6_JavaScript.git
   ```
2. Open `webactivity6/timer.html` or `webactivity6/array.html` in any web browser.

---

> **Author:** DatariusAI — AUB CMPS 302, Spring 2026
