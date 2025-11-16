# Modular-calculator
HumaCalc is a friendly, modular, command-line calculator written in Python.
It supports arithmetic, trigonometry, statistics, unit conversions, memory storage, and persistent history logging — all from an interactive CLI.

🌟 Features
✅ Arithmetic

Evaluate expressions like 4 + 5, 10 * 3, 12 * M

Memory variable M is supported

Safe evaluation (no alphabetic characters except M)

✅ Trigonometry (Degrees)

Functions: sin, cos, tan

Automatically converts degrees → radians

✅ Statistics

Enter numbers separated by spaces or commas (supports M)

Computes:

Mean

Median

Standard Deviation

Count

Supports up to 500 stored history items

✅ Unit Conversion

Supports length and temperature units:

Length:
m, km, cm, mm, mi, ft, in

Temperature:
C, F, K

Examples:

10 km to m

100 F to C

✅ Memory System

Simple single-value memory storage:

store <value>

recall

clear

✅ Persistent History

Saves history in calc_history.json

Automatically keeps the last 500 entries

Shows last 20 entries on command

📦 File Structure
.
├── calculator.py          # Main program containing the HumanoidCalculator class
├── calc_history.json      # Auto-generated history (created at runtime)
└── README.md              # Project documentation

🚀 How to Run
1. Clone or Download the Script
git clone <your-repo-url>
cd your-project

2. Run the Program
python calculator.py

🧭 Interactive Menu Commands

When the program starts, you’ll see:

Hello! I'm HumaCalc — your friendly modular calculator.
I can do arithmetic, trig (degrees), statistics, unit conversion, and save history.
Type 'help' to see modules, or 'exit' to quit.
