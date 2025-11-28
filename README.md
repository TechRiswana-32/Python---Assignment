# Python---Assignment

### 🌡️ NumPy Temperature Analysis — Week-wise Weather Data

This project demonstrates the use of NumPy arrays, including creation, slicing, indexing, mathematical operations, and working with 1D and 2D arrays using real-world temperature data.

🧩 Part 1: Week 1 — 1D NumPy Array
import numpy as np

#  Create 1D NumPy array for Week 1
temperatures_w1 = np.array([22.5, 25.3, 20.8, 23.4, 26.1, 24.8, 21.9])

🔍 Array Inspection
print("Shape:", temperatures_w1.shape)
print("Data Type:", temperatures_w1.dtype)
print("Total Elements:", temperatures_w1.size)

🌡️ Celsius → Fahrenheit Conversion
temperatures_fahrenheit = (temperatures_w1 * 9/5) + 32
print("Fahrenheit:", temperatures_fahrenheit)

📊 Statistical Analysis
print("Max Temperature:", np.max(temperatures_w1))
print("Min Temperature:", np.min(temperatures_w1))
print("Mean Temperature:", np.mean(temperatures_w1))

✂️ Slicing / Indexing
print("First 3 Days:", temperatures_w1[:3])
print("Weekend (last 2 days):", temperatures_w1[-2:])
print("Middle 3 Days:", temperatures_w1[2:5])

🧮 Part 2: Week 1 + Week 2 — 2D Array
temperatures_w2 = np.array([19.2, 22.5, 21.3, 24.0, 23.5, 22.8, 20.1])
temperatures = np.array([temperatures_w1, temperatures_w2])

🧾 2D Array Inspection
print("2D Shape:", temperatures.shape)
print("2D Data Type:", temperatures.dtype)
print("2D Total Elements:", temperatures.size)

🔥 Row & Column Indexing
print("Week 1 Temperatures:", temperatures[0])
print("Week 2 Temperatures:", temperatures[1])
print("Weekend Temps (Both Weeks):", temperatures[:, -2:])

🎯 Learning Outcomes

✔ NumPy array creation (1D and 2D)
✔ Array attribute inspection (shape, size, dtype)
✔ Statistical functions (max, min, mean)
✔ Unit conversion with vectorized operations
✔ Slicing and indexing on arrays
✔ Handling multi-dimensional matrices

👤 Author

Riswana Haris

If you want, I can also create:
✔ sample output section
✔ screenshots of output
✔ project description badges
✔ a better title and tagline

Just ask — I’ll help you refine it further for GitHub.
