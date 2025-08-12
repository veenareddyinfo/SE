
Weather Modeling Using Quadratic Solution
📌 Overview:
This project models temperature changes over time using the quadratic equation:

T(t)=aX^2 + bX + c

It is implemented in three stages:
Hard-coded variables (keyboard input)

Read from a file (single set of inputs)

Read from a file (multiple sets of inputs)

Each stage plots a temperature-time curve using Matplotlib.

📂 Files:
stage1_hardcoded.py — Uses fixed coefficients, user enters number of days.
stage1_userinput.py — User enters coefficients and number of days.
stage2_file_single.py — Reads one dataset from wea2.csv.
stage3_file_multiple.py — Reads multiple datasets from wea.csv.
wea2.csv — Sample file for single set of inputs.
wea.csv — Sample file for multiple sets of inputs.

⚙️ How to Run:
1️⃣ Hard-coded Variables (Keyboard Input):
python stage1_hardcoded.py
Prompts for number of days and plots the curve.

2️⃣ Hard-coded Variables (User Input)
python stage1_userinput.py
Prompts for a, b, c, and number of days.

3️⃣ Single Set of Inputs from CSV
python stage2_file_single.py
Requires wea2.csv:

css:
a,b,c
0.5,2,20

4️⃣ Multiple Sets of Inputs from CSV
python stage3_file_multiple.py
Requires wea.csv:

css
a,b,c
0.5,2,20
1,-3,15
-0.2,4,10

📊 Output:
Line plots of temperature over time.
For multiple datasets, all curves appear on the same plot.

🛠 Requirements:
Python 3.x
matplotlib
pandas
