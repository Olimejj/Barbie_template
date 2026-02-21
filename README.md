# The Barbie Movie Project (Python)

## Introduction
Welcome to the Barbie Movie Adventure! Step into the captivating world of Barbieland, where Barbie and Ken are about to embark on an extraordinary journey that blends beauty, bravery, and a touch of magic.

In this Python project, you'll code and solve **three challenges** that mirror key moments in Barbie and Ken’s journey. Your job is to complete the code inside the provided Python file and make sure your output matches the example formatting.

---

## What You Will Do
You will complete **three challenges** in `barbie.py`:

### 1) Beach Adventure Challenge
Help Barbie and Ken manage their expenses for a day at the beach.  
You will calculate:
- total cost before discounts  
- total cost after discounts  
- each person's share  

### 2) Escape Plan Challenge
Assist Barbie, Ken, and Gloria in devising an escape plan.  
You will calculate:
- time required for each route  
- which route is fastest  
- time saved by choosing the fastest route  

### 3) Societal Reformation Challenge
Help Barbie reform society in Barbieland.  
You will calculate:
- success rate of proposed changes  
- how many additional changes are needed to reach a 75% success rate  
- remaining changes to be implemented  

---

## Files in This Repository
- **`barbie.py`** → This is the file you edit and submit.
- **`tests_public/`** → Public tests you can run locally to check your output.
- **`.vscode/tasks.json`** → VS Code tasks (one-click setup + run + tests).
- **`requirements.txt`** → Python packages needed for testing (currently just `pytest`).

---

## Required Output Formatting
Your output must include the same formatted result lines as the example.  
**Extra output is allowed**, but the required lines must appear exactly.

---

## Example Input and Output Values

### Beach Adventure Challenge
**Example Inputs**
- Number of people: `4`
- Beach Chairs Cost: `$30.00`
- Sunscreen Cost: `$10.00`
- Ice Cream Cost: `$5.00`
- Beach Toys Cost: `$15.00`

**Expected Result Lines**
Challenge 1 Results:
Total cost before discounts: $60.00
Total cost after discounts: $53.50
Each person's share: $13.38


### Escape Plan Challenge
**Example Inputs**
- Route 1 Distance: `100` miles
- Route 1 Speed: `50` mph
- Route 2 Distance: `120` miles
- Route 2 Speed: `70` mph
- Route 3 Distance: `140` miles
- Route 3 Speed: `60` mph

**Expected Result Lines**
Challenge 2 Results:
Time required for Route 1: 2.00 hours
Time required for Route 2: 1.71 hours
Time required for Route 3: 2.33 hours
The fastest route takes 1.71 hours.
Time saved by choosing the fastest route: 0.62 hours

### Societal Reformation Challenge
**Example Inputs**
- Total Proposed Changes: `20`
- Successful Changes: `13`

**Expected Result Lines**
Challenge 3 Results:
Percentage of successful changes: 65.00%
Number of additional changes needed to achieve a 75% success rate: 2
Remaining changes to be implemented: 7

---

## Using VS Code Tasks (Required)

This assignment is also an introduction to using **VS Code Tasks**. Tasks give you one-click commands for setting up your environment and running tests.

### Step 1: Install the Tasks extension (if needed)
Most versions of VS Code already support Tasks by default.  
If you do not see Tasks working, install:

**Extension name:** `Task Explorer` (publisher: *spmeesseman*)  
This makes Tasks easier to find and run.

### Step 2: How to run Tasks
In VS Code, use one of these:

**Option A (recommended):**
- Press **Ctrl+Shift+P** (Windows) or **Cmd+Shift+P** (Mac)
- Type: **Tasks: Run Task**
- Choose the task you want

**Option B (Task Explorer extension):**
- Open the Task Explorer sidebar
- Click the task name to run it

### What the Tasks Do
Your repo includes these tasks:

1. **Run - Program**
   - Runs your `barbie.py` program so you can test it normally.

2. **Setup - Create venv (.venv)**
   - Creates a Python virtual environment in a folder named `.venv`

3. **Setup - Install requirements**
   - Installs the packages listed in `requirements.txt` into your virtual environment

4. **Run - Public Tests**
   - Runs the included public tests to check for required output lines

**Recommended workflow:**
1) Run **Run - Program** first (manual testing)  
2) Then run **Run - Public Tests** (automatic check)  

---

## Report Outline (Required)
Write a short report (about **half a page**) that includes:

- A short description, in your own words, of what you were required to do (1–2 sentences)
- The challenges you faced when completing the project
- The concepts you learned from the project
- Any resources/people that helped you

**Format:**  
- You may either **upload** your report as a file **OR** submit it as a **text entry** (no PDF required).

---

## Submission
You will submit:

1) **A link to your GitHub assignment repository** (this repo)  
2) Your **report** (upload or text entry)

Make sure your final code is pushed to GitHub.

