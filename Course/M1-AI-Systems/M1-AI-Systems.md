# Fundamentals of AI for Business - Module 1: What is AI and Its Types
## Complete Uplimit Storyboard

### Module Version
**v1.1.0** (Updated 2025-12-22 - Corrected session placement)

### Module Purpose
Introduce machine learning through hands-on development using Google Colab, building foundational understanding of how AI systems are created.

### Module Time
~90 minutes (44 min video + 46 min interactive practice)

### Course Context
**Course:** Fundamentals of AI for Business (Ivey Business School)
**Session:** Module 1 - What is AI and Its Types (~2 hours total)
**Format:** Self-paced, asynchronous
**Prerequisites:** None (this is the first session)

---

## Module Learning Outcomes (MLOs)

By completing this module, you will be able to:

- **MLO 1:** Navigate Google Colab environment and execute Python code cells
- **MLO 2:** Load and explore datasets using pandas DataFrames
- **MLO 3:** Identify data quality issues (outliers, missing values, data types)
- **MLO 4:** Preprocess data using one-hot encoding and standardization
- **MLO 5:** Build and evaluate a logistic regression model with 80/20 train-test split
- **MLO 6:** Interpret model accuracy and understand its business implications

---

## Element List

| Order | Element Type | Title/Purpose | Priority | Time |
|-------|--------------|---------------|----------|------|
| **SUBSECTION 1: Introduction & Setup (8 min)** |||||
| 1 | Text | Course Welcome & Introduction | ⬤ Required | 2 min |
| 2 | Learning Outcomes Widget | Module 1 MLOs | ⬤ Required | 2 min |
| 3 | Text | Module Introduction: ML Development Cycle | ⬤ Required | 2 min |
| 4 | Infobox (Note) | What You'll Build Today | ⬤ Required | 2 min |
| **SUBSECTION 2: Google Colab Basics (10 min)** |||||
| 5 | Video | Segment 1: Intro to Google Colab (00:00-02:01) | ⬤ Required | 2 min |
| 6 | Infobox (Action) | 🎯 Now Try It: Open Google Colab | ⬤ Required | 4 min |
| 7 | Details Accordion | Colab Quick Reference Card | ◐ Recommended | -- |
| **SUBSECTION 3: Loading & Exploring Data (18 min)** |||||
| 8 | Video | Segment 2: Loading Data from Google Drive (02:01-05:02) | ⬤ Required | 3 min |
| 8b | Infobox (Action) | 🎯 Now Try It: Load Your Dataset | ⬤ Required | 3 min |
| 9 | Video | Segment 3: Exploring Data with df.head() (05:02-09:23) | ⬤ Required | 4 min |
| 9b | Infobox (Action) | 🎯 Now Try It: Explore Your Data | ⬤ Required | 2 min |
| 10 | Details Accordion | Pandas Basics Reference | ◐ Recommended | -- |
| 11 | Infobox (Action) | 🎯 Now Try It: Explore the Dataset | ⬤ Required | 5 min |
| **SUBSECTION 4: Understanding Your Data (14 min)** |||||
| 12 | Video | Segment 4: Describing Data with df.info() (09:23-14:05) | ⬤ Required | 5 min |
| 12b | Infobox (Action) | 🎯 Now Try It: Investigate Data Types | ⬤ Required | 2 min |
| 13 | Text | Recognizing Data Quality Issues | ⬤ Required | 2 min |
| 14 | iFrame Widget | Outlier Detection Quiz | ◐ Recommended | 5 min |
| **SUBSECTION 5: Data Visualization (14 min)** |||||
| 15 | Video | Segment 5: Visualization & Outliers (14:05-21:47) | ⬤ Required | 8 min |
| 15b | Infobox (Action) | 🎯 Now Try It: Visualize and Clean Data | ⬤ Required | 3 min |
| 16 | Details Accordion | Visualization Best Practices | ◐ Recommended | -- |
| 17 | AI Chat | Data Visualization Q&A | ◐ Recommended | 3 min |
| **SUBSECTION 6: Data Preprocessing (16 min)** |||||
| 18 | Video | Segment 6: One-Hot Encoding & Standardization (21:47-28:30) | ⬤ Required | 7 min |
| 18b | Infobox (Action) | 🎯 Now Try It: Preprocess Your Data | ⬤ Required | 3 min |
| 19 | Text | Why Preprocess? Business Context | ⬤ Required | 2 min |
| 20 | iFrame Widget | Preprocessing Simulator | ⬤ Required | 5 min |
| **SUBSECTION 7: Building the ML Model (20 min)** |||||
| 21 | Video | Segment 7: Model Building & Evaluation (28:30-40:21) | ⬤ Required | 12 min |
| 21b | Infobox (Action) | 🎯 Now Try It: Build Your ML Model | ⬤ Required | 4 min |
| 22 | Text | Understanding 89% Accuracy | ⬤ Required | 2 min |
| 23 | iFrame Widget | Train-Test Split Visualizer | ◐ Recommended | 4 min |
| **SUBSECTION 8: Wrap-Up & Looking Ahead (10 min)** |||||
| 24 | Text | Preview: Why Bias Matters in ML | ⬤ Required | 3 min |
| 25 | Details Accordion | ML Development Cycle Summary | ⬤ Required | 2 min |
| 26 | AI Chat | ML Development Q&A | ◐ Recommended | 5 min |
| 27 | Text | Module Summary & Next Steps | ⬤ Required | 3 min |

---

## SUBSECTION 1: Introduction & Setup

---

### ELEMENT 1: Text - Course Welcome & Introduction

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```markdown
# Welcome to Fundamentals of AI for Business

Artificial intelligence is transforming every industry—from how banks approve loans to how courts assess risk. But what actually happens inside these AI systems? How are they built, and why do they sometimes produce unfair or unexpected results?

This course demystifies AI by putting you in the developer's seat. You won't just read about machine learning—you'll build a real prediction model using the same tools data scientists use. By the end of this session, you'll have trained an algorithm that predicts loan approvals with 89% accuracy.

More importantly, you'll understand the decisions that shape AI outcomes: which data to include, how to handle messy values, what "accuracy" really means. This hands-on foundation prepares you to critically evaluate AI systems throughout your career—whether you're deploying them, governing them, or being affected by their decisions.

Let's begin by setting up your development environment.
```

**Design Notes:**
- 145 words (under 150-word limit)
- Welcomes students to the course
- Sets expectations for hands-on learning
- Previews the loan approval model they'll build

---

### ELEMENT 2: Learning Outcomes Widget - Module 1 MLOs

**Element Type:** Learning Outcomes Widget (Interactive)
**Priority:** ⬤ Required
**Interaction Time:** 2 minutes

#### WIDGET CONFIGURATION:

**Widget Type:** Learning Outcomes Display (Interactive checklist)

**Display Format:** Expandable accordion with checkboxes

**Learning Outcomes to Display (Module 1 - All 6 MLOs):**

- [ ] **MLO 1:** Navigate Google Colab environment and execute Python code cells
- [ ] **MLO 2:** Load and explore datasets using pandas DataFrames
- [ ] **MLO 3:** Identify data quality issues (outliers, missing values, data types)
- [ ] **MLO 4:** Preprocess data using one-hot encoding and standardization
- [ ] **MLO 5:** Build and evaluate a logistic regression model with 80/20 train-test split
- [ ] **MLO 6:** Interpret model accuracy and understand its business implications

**Functionality:**
- Students can check off outcomes as they progress
- Progress saves automatically
- Visual indicator shows completion (e.g., 3/6 outcomes completed)

**Embed Code:**

```html
<learning-outcomes-widget>
  <outcome id="mlo-1">Navigate Google Colab environment and execute Python code cells</outcome>
  <outcome id="mlo-2">Load and explore datasets using pandas DataFrames</outcome>
  <outcome id="mlo-3">Identify data quality issues (outliers, missing values, data types)</outcome>
  <outcome id="mlo-4">Preprocess data using one-hot encoding and standardization</outcome>
  <outcome id="mlo-5">Build and evaluate a logistic regression model with 80/20 train-test split</outcome>
  <outcome id="mlo-6">Interpret model accuracy and understand its business implications</outcome>
</learning-outcomes-widget>
```

**Note to Builder:** Use Uplimit's native learning outcomes widget. Configure with all 6 Module 1 MLOs.

---

### ELEMENT 3: Text - Module Introduction: ML Development Cycle

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```markdown
# Understanding the ML Development Cycle

Machine learning development follows a systematic process, whether you're building a loan approval system, a medical diagnosis tool, or a customer recommendation engine. Today you'll experience each stage hands-on using Google Colab and a real loan dataset.

**The 7 Stages You'll Experience:**

1. **Setup Environment** - Open Google Colab and mount your data
2. **Load Data** - Import CSV files using pandas
3. **Explore Data** - Understand structure, variables, and initial patterns
4. **Describe Data** - Check data types, missing values, and descriptive statistics
5. **Preprocess Data** - Clean outliers, encode categories, standardize values
6. **Build Model** - Split data 80/20, train logistic regression
7. **Evaluate Model** - Test accuracy and interpret results

Each stage involves critical decisions that affect model performance and fairness. Where bias enters the ML development cycle is not random—it's the result of choices made at each of these stages. By the end of this session, you'll understand these choices from the inside.
```

**Design Notes:**
- 149 words (under 150-word limit)
- Numbered list for clear structure
- Connects to bias discussion
- Sets expectations for hands-on experience

---

### ELEMENT 4: Infobox (Note) - What You'll Build Today

**Element Type:** Infobox
**Variant:** Note (💡 icon)
**Priority:** ⬤ Required
**Reading Time:** 1 minute

#### COPY-PASTE CONTENT:

```
Title: 💡 Your ML Project: Loan Approval Predictor

Today you'll build a logistic regression model that predicts whether loan applications should be approved or rejected. Your dataset contains 45,000 past loan decisions with 14 variables including applicant age, income, employment history, credit score, and loan intent. The model you build achieves 89% accuracy—meaning it replicates human decision-making patterns 89% of the time. This raises critical questions: If an algorithm replicates biased human decisions, does it perpetuate that bias? Can 89% accuracy mask unfair outcomes for specific groups? You'll explore these questions throughout the course.
```

**Design Notes:**
- 99 words (within 50-100 word infobox limit)
- Simple paragraph format (no bullets/headings)
- Preview of ethical questions
- Sets context for bias discussions in later sessions

---

## SUBSECTION 2: Google Colab Basics

---

### ELEMENT 5: Video - Segment 1: Intro to Google Colab

**Video Upload Instructions:**
- **Video Title:** Introduction to Google Colab Interface
- **File Name:** `session3-segment1-colab-intro.mp4`
- **Duration:** 2 minutes 1 second
- **Timestamps:** 00:00 - 02:01
- **VTT Transcript:** Upload corresponding .vtt file for captions

**Accessibility Attributes:**
- ✅ Captions enabled (VTT file)
- ✅ Transcript available below video

**Video Description Text:**

Learn how to navigate the Google Colab environment. Discover how to create notebooks, use the Gemini AI assistant, run code cells, and configure your workspace layout. This foundational knowledge prepares you to execute machine learning code throughout this session.

**Bridge-In Text (display above video):**

```markdown
### Opening Your ML Development Environment

Google Colab provides a free, cloud-based Python environment—no software installation required. Watch this 2-minute walkthrough to understand the interface, learn how to create notebooks, and discover how Gemini AI can assist with code generation and explanation.

**What You'll Learn:**
- Creating new notebooks
- Understanding the code cell interface
- Using Gemini AI for code assistance
- Configuring workspace layout (side-by-side vs. bottom panel)
```

**Key Timestamps:**
- 00:00 - 00:21: Creating a new notebook
- 00:21 - 00:44: Understanding the interactive Python notebook environment
- 00:44 - 01:18: Using Gemini AI for code generation and explanations
- 01:18 - 02:01: Configuring workspace layout preferences

---

### ELEMENT 6: Infobox (Action) - Now Try It: Open Google Colab

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 1 minute

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Open Your Colab Environment

Now that you've seen how Colab works, it's time to try it yourself:

1. Open Google Colab: [colab.research.google.com](https://colab.research.google.com)
2. Click "New Notebook" to create a fresh notebook
3. Try clicking the "+ Code" button to add a new cell
4. Type `print("Hello, ML!")` and press the play button (▶) to run it
5. Experiment with the Gemini AI button to ask questions about code

Don't worry about making mistakes—you can always create a new notebook. When you're comfortable navigating the interface, continue to the next section where you'll load real data.
```

**Design Notes:**
- Clear numbered steps for first-time Colab users
- Direct link to Colab
- Low-stakes experimentation encouraged
- Signals when to continue

---

### ELEMENT 7: Details Accordion - Colab Quick Reference Card

**Element Type:** Details Accordion
**Priority:** ◐ Recommended
**Reading Time:** Reference as needed

**Introduction Text (above accordion):**

```markdown
## 📋 Colab Quick Reference

Keep this reference handy as you work through the module. Expand each section for keyboard shortcuts, common actions, and troubleshooting tips.
```

**Accordion Sections:**

<details>
<summary><strong>Essential Keyboard Shortcuts</strong></summary>

| Action | Windows/Linux | Mac |
|--------|---------------|-----|
| Run current cell | Ctrl + Enter | Cmd + Enter |
| Run cell & move to next | Shift + Enter | Shift + Enter |
| Add code cell above | Ctrl + M, A | Cmd + M, A |
| Add code cell below | Ctrl + M, B | Cmd + M, B |
| Delete cell | Ctrl + M, D | Cmd + M, D |
| Undo | Ctrl + Z | Cmd + Z |
| Save notebook | Ctrl + S | Cmd + S |

</details>

<details>
<summary><strong>Common Actions</strong></summary>

- **Run all cells:** Runtime menu → Run all
- **Restart runtime:** Runtime menu → Restart runtime (clears all variables)
- **Connect to GPU:** Runtime menu → Change runtime type → GPU
- **Download notebook:** File menu → Download → Download .ipynb
- **Share notebook:** Share button (top right) → copy link

</details>

<details>
<summary><strong>Troubleshooting</strong></summary>

| Problem | Solution |
|---------|----------|
| "Session crashed" | Click "Reconnect" or Runtime → Restart runtime |
| Code won't run | Check if connected (green checkmark top right) |
| Variables undefined | Run cells in order from top to bottom |
| File not found | Re-mount Google Drive: `from google.colab import drive; drive.mount('/content/drive')` |

**Tip:** If something isn't working, try Runtime → Restart runtime, then run cells from the beginning.

</details>

---

## SUBSECTION 3: Loading & Exploring Data

---

### ELEMENT 8: Video - Segment 2: Loading Data from Google Drive

**Video Upload Instructions:**
- **Video Title:** Loading CSV Data into Google Colab
- **File Name:** `session3-segment2-load-data.mp4`
- **Duration:** 3 minutes 1 second
- **Timestamps:** 02:01 - 05:02
- **VTT Transcript:** Upload corresponding .vtt file

**Accessibility Attributes:**
- ✅ Captions enabled
- ✅ Transcript available below video

**Video Description Text:**

Learn how to mount Google Drive, upload CSV files, and load data into pandas DataFrames. Understand the import pandas as pd convention, read_csv() function, and how to display the first five rows with df.head().

**Bridge-In Text (display above video):**

```markdown
### Connecting Your Data to Colab

Before building ML models, you need data. This 3-minute segment shows you how to upload your loan dataset CSV file to Google Drive, mount that drive to Colab, and load the data into a pandas DataFrame—Python's standard data structure for spreadsheet-like data.

**What You'll Learn:**
- Uploading CSV files to Google Drive's Colab Notebooks folder
- Mounting Google Drive to access files
- Using pandas `read_csv()` to load data
- Displaying data with `df.head()` to see the first 5 rows
```

**Key Timestamps:**
- 02:01 - 02:48: Uploading CSV to Google Drive and navigating the Colab Notebooks folder
- 02:48 - 03:34: Mounting Google Drive and copying file paths
- 03:34 - 04:26: Writing `pd.read_csv()` code using Gemini AI
- 04:26 - 05:02: Running the code and displaying the first 5 rows with `df.head()`

---

### ELEMENT 8b: Infobox (Action) - Now Try It: Load Your Dataset

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 1 minute

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Load the Loan Dataset

Pause here and load the dataset yourself in Google Colab:

1. Download the loan dataset CSV file: [link to course files]
2. Upload it to your Google Drive → Colab Notebooks folder
3. In your Colab notebook, run: `from google.colab import drive` then `drive.mount('/content/drive')`
4. Load the data: `import pandas as pd` then `df = pd.read_csv('/content/drive/MyDrive/Colab Notebooks/loan_data.csv')`
5. View your data: `df.head()`

You should see a table with 14 columns including person_age, person_income, and loan_status. If you see an error, check that your file path matches where you uploaded the CSV.

Once your data loads successfully, continue to the next video.
```

**Design Notes:**
- Numbered steps match video sequence
- Includes actual code students will type
- Success criteria: see the table output
- Clear signal to continue

---

### ELEMENT 9: Video - Segment 3: Exploring Data with df.head()

**Video Upload Instructions:**
- **Video Title:** Exploring Your Dataset Structure
- **File Name:** `session3-segment3-explore-data.mp4`
- **Duration:** 4 minutes 21 seconds
- **Timestamps:** 05:02 - 09:23
- **VTT Transcript:** Upload corresponding .vtt file

**Accessibility Attributes:**
- ✅ Captions enabled
- ✅ Transcript available below video

**Video Description Text:**

Understand the loan dataset structure by examining the first five rows. Learn to identify categorical variables (gender, education, loan intent) versus numerical variables (age, income, credit score) and interpret what each column represents in the context of loan approval decisions.

**Bridge-In Text (display above video):**

```markdown
### Understanding What Your Data Contains

Once data loads successfully, your first task is exploration—understanding what variables you have, their data types, and what they represent. This 4-minute segment walks through the loan dataset's 14 columns, distinguishing categorical variables (text labels like "Female" or "Master's degree") from numerical variables (age, income, credit score).

**What You'll Learn:**
- Interpreting `df.head()` output (column names and first 5 rows)
- Categorical variables: gender, education, home ownership, loan intent
- Numerical variables: age, income, employment experience, loan amount, interest rate
- Target variable: loan_status (1 = approved, 0 = rejected)
- Using Gemini AI to explain unfamiliar column names
```

**Key Timestamps:**
- 05:02 - 06:24: Examining the first 5 rows and identifying column names
- 06:24 - 07:44: Understanding categorical vs. numerical variables
- 07:44 - 08:36: Identifying the target variable (loan_status: 1 = approved, 0 = rejected)
- 08:36 - 09:23: Using Gemini AI to explain what pandas DataFrames are

---

### ELEMENT 9b: Infobox (Action) - Now Try It: Explore Your Data

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 1 minute

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Explore the Dataset Structure

Now explore your loaded dataset in Colab:

1. Run `df.head()` to see the first 5 rows
2. Run `df.shape` to confirm you have 45,000 rows and 14 columns
3. Look at the column names—can you identify which are categorical (text) vs. numerical?
4. Find the target variable: `loan_status` (1 = approved, 0 = rejected)

**Quick Check:** Try asking Gemini AI: "Explain what each column in this loan dataset represents"

Once you can see your data and understand what each column means, continue to the next video to learn about data types and descriptive statistics.
```

**Design Notes:**
- Hands-on exploration tasks
- Encourages Gemini AI use
- Sets up next video topic

---

### ELEMENT 10: Details Accordion - Pandas Basics Reference

**Element Type:** Details Accordion
**Priority:** ◐ Recommended
**Reading Time:** Reference while practicing

**Introduction Text (above accordion):**

```markdown
## 🐼 Pandas Quick Reference

Expand each section below for pandas syntax, common functions, and examples. Reference this guide while practicing data exploration in the widget below.
```

**Accordion Sections:**

<details>
<summary><strong>What is a DataFrame?</strong></summary>

**Definition:** A DataFrame is pandas' core data structure—think of it as an Excel spreadsheet or database table with rows and columns.

**Key Characteristics:**
- **Rows:** Each row represents one observation (one loan application in our dataset)
- **Columns:** Each column represents one variable (age, income, loan_status, etc.)
- **Index:** Row numbers starting from 0 (Python uses zero-indexing)
- **Data Types:** Columns can contain numbers (int, float) or text (object/string)

**Why DataFrames?**
DataFrames make it easy to filter, analyze, and transform large datasets. Instead of manually scrolling through 45,000 rows in Excel, you write code that processes all data instantly.

**Common Variable:** `df` stands for "DataFrame" (shorthand convention)

</details>

<details>
<summary><strong>Essential pandas Functions</strong></summary>

| Function | Purpose | Example | Output |
|----------|---------|---------|--------|
| `pd.read_csv("file.csv")` | Load CSV file into DataFrame | `df = pd.read_csv("loans.csv")` | DataFrame with all data |
| `df.head(5)` | Show first 5 rows | `df.head()` | Top 5 rows displayed |
| `df.tail(5)` | Show last 5 rows | `df.tail()` | Bottom 5 rows displayed |
| `df.shape` | Get row and column count | `df.shape` | `(45000, 14)` - 45K rows, 14 cols |
| `df.info()` | Show data types and missing values | `df.info()` | Column names, types, null counts |
| `df.describe()` | Get descriptive statistics | `df.describe()` | Mean, min, max, standard deviation |
| `df["column"]` | Select one column | `df["person_age"]` | All ages as a Series |
| `df[["col1", "col2"]]` | Select multiple columns | `df[["age", "income"]]` | DataFrame with 2 columns |

</details>

<details>
<summary><strong>Understanding Data Types</strong></summary>

**pandas Data Types (dtypes):**

| pandas dtype | Meaning | Examples in Loan Dataset |
|--------------|---------|---------------------------|
| **int64** | Whole numbers | person_age (22, 35, 48), loan_status (0, 1) |
| **float64** | Decimal numbers | person_income (45000.5), loan_int_rate (7.25) |
| **object** | Text/strings | person_gender ("Male", "Female"), person_education ("Bachelor", "Master") |

**Why Data Types Matter:**
- You can't do math on text ("Male" + "Female" = error)
- Machine learning algorithms require numbers, not text
- That's why we need **one-hot encoding** to convert categories to numbers (covered in Segment 6)

**Checking Data Types:**
```python
df.info()  # Shows each column's data type
df.dtypes  # Returns just the data types
```

</details>

<details>
<summary><strong>Common Errors & Fixes</strong></summary>

| Error | Cause | Fix |
|-------|-------|-----|
| FileNotFoundError | CSV file path incorrect | Check path with `!ls` command; ensure file uploaded to Google Drive |
| KeyError: 'column_name' | Column doesn't exist or typo | Run `df.columns` to see exact column names (case-sensitive) |
| AttributeError: 'DataFrame' object has no attribute 'head' | Variable isn't a DataFrame | Check `type(df)` to confirm it's a DataFrame |
| NameError: name 'pd' is not defined | Forgot to import pandas | Run `import pandas as pd` first |

**Debugging Tip:** Use `print()` statements to inspect variables:
```python
print(type(df))  # Check if df is a DataFrame
print(df.columns)  # See all column names
print(df.shape)  # Verify row and column count
```

</details>

---

### ELEMENT 11: Infobox (Action) - Now Try It: Explore the Dataset

**Element Type:** Infobox (Action)
**Priority:** ⬤ Required
**Interaction Time:** 5 minutes

#### INFOBOX CONTENT:

```markdown
### 🎯 Now Try It: Explore the Loan Dataset

**Practice: MLO 2 (Load and explore datasets using pandas DataFrames) + MLO 3 (Identify data quality issues)**

Return to your Google Colab notebook and try these exploration tasks:

**Task 1: Check Dataset Dimensions**
```python
print(df.shape)
```
→ How many rows and columns does the dataset have?

**Task 2: Preview Column Names**
```python
print(df.columns.tolist())
```
→ Can you identify which column is the target variable (what we're trying to predict)?

**Task 3: Examine Data Types**
```python
df.info()
```
→ How many categorical (object) vs. numerical columns exist?

**Task 4: Look for Outliers**
```python
df.describe()
```
→ Check `person_age` max value. Does 140 years old seem realistic?
→ Check `person_emp_length` max value. Does 125,000+ years of experience make sense?

**Task 5: Check for Missing Values**
```python
df.isnull().sum()
```
→ Are there any missing values that need to be handled?

**✓ Success Checkpoint:** You've completed data exploration when you can answer:
- The dataset has 45,000 rows and 14 columns
- `loan_status` is the target variable (0 = approved, 1 = denied)
- There are obvious outliers in age and employment length
- Missing values will need to be addressed before model training
```

**Learning Outcomes Addressed:** MLO 2 (Explore datasets), MLO 3 (Identify data quality issues)

---

## SUBSECTION 4: Understanding Your Data

---

### ELEMENT 12: Video - Segment 4: Describing Data with df.info()

**Video Upload Instructions:**
- **Video Title:** Understanding Data Types and Descriptive Statistics
- **File Name:** `session3-segment4-describe-data.mp4`
- **Duration:** 4 minutes 42 seconds
- **Timestamps:** 09:23 - 14:05
- **VTT Transcript:** Upload corresponding .vtt file

**Accessibility Attributes:**
- ✅ Captions enabled
- ✅ Transcript available below video

**Video Description Text:**

Learn to use `df.shape`, `df.info()`, and `df.describe()` to understand dataset structure, check for missing values, identify data types, and examine descriptive statistics. Discover how outliers (140-year-old applicants, 125,000 years of employment experience) reveal data quality issues that must be addressed before model training.

**Bridge-In Text (display above video):**

```markdown
### Deep Dive: Data Types, Missing Values, and Outliers

After viewing the first few rows, you need systematic analysis of the entire dataset. This 5-minute segment demonstrates three essential pandas functions that reveal data structure, data types, missing values, and statistical summaries. You'll also discover obvious data quality problems—like a 140-year-old loan applicant—that highlight the importance of data cleaning.

**What You'll Learn:**
- `df.shape`: Get total row and column count (45,000 rows × 14 columns)
- `df.info()`: Check data types (int64, float64, object) and missing values
- `df.describe()`: Calculate mean, min, max, standard deviation for numerical columns
- Identifying outliers: Ages >100 years, employment experience >100 years
- Why clean data matters: Outliers distort model training
```

**Key Timestamps:**
- 09:23 - 10:18: Using `df.shape` to confirm 45,000 rows and 14 columns
- 10:18 - 11:42: Running `df.info()` to check data types and null values
- 11:42 - 13:00: Using `df.describe()` for descriptive statistics (mean, min, max)
- 13:00 - 14:05: Identifying suspicious outliers (140-year-old applicant, 125K years employment)

---

### ELEMENT 12b: Infobox (Action) - Now Try It: Investigate Your Data

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 1 minute

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Investigate Data Types and Outliers

Time to dig deeper into your dataset in Colab:

1. Run `df.shape` — confirm you see (45000, 14)
2. Run `df.info()` — check data types for each column (int64, float64, object)
3. Run `df.describe()` — look at min/max values for each numerical column
4. **Spot the outliers:** Look at max values for person_age and person_emp_exp. Do they seem realistic?

**What to look for:**
- Does person_age max make sense? (Hint: check if anyone is >120 years old)
- Does person_emp_exp max make sense? (Hint: can someone work 125,000 years?)

These suspicious values reveal data quality issues you'll need to address. Continue reading to understand why this matters.
```

**Design Notes:**
- Specific commands to run
- Guides attention to outliers
- Sets up the following text explanation

---

### ELEMENT 13: Text - Recognizing Data Quality Issues

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```markdown
# Why Data Quality Determines Model Quality

Machine learning models learn patterns from data. If your data contains errors, your model learns those errors as patterns. The loan dataset reveals common data quality issues that, if ignored, would corrupt model predictions.

**Red Flags Identified:**

- **Impossible ages:** Maximum person_age = 140 years (likely data entry error)
- **Absurd employment history:** Maximum employment_exp = 125,000 years
- **Suspicious loan status values:** Should be binary 0/1, but some rows may have other values

**Why This Matters for Bias:**

Real-world ML systems face similar data quality questions: Were all records complete? Did missing data disproportionately affect certain demographic groups? If one neighborhood has incomplete records while another has comprehensive tracking, the model learns different patterns for each group—creating bias. You'll examine this concept in depth in Module 3.

Data cleaning isn't just technical hygiene—it's an ethical imperative. Deciding which outliers to remove and which to keep involves judgment calls that affect model fairness. Should you remove all applicants over age 100? What about applicants over 80? These decisions shape who gets approved and who gets rejected.
```

**Design Notes:**
- 147 words (under 150-word limit)
- Bullet list for red flags
- Previews bias discussion from Module 3
- Raises ethical questions about data cleaning choices

---

### ELEMENT 14: iFrame Widget - Outlier Detection Quiz

**Element Type:** iFrame Widget
**Priority:** ◐ Recommended
**Interaction Time:** 5 minutes

#### WIDGET INTRODUCTION (display above widget):

```markdown
### ⚙ Interactive Activity: Spotting Data Quality Issues

**Practice: MLO 3 (Identify data quality issues - outliers, missing values, data types)**

Understanding outliers requires judgment—not every unusual value is an error. This quiz presents 6 scenarios from the loan dataset and asks you to decide: Is this value a legitimate outlier or a data quality error? Your choices reveal how data cleaning decisions affect who gets included in model training.

This exercise builds the critical thinking skills needed to evaluate dataset quality in business contexts. You'll practice distinguishing between extreme-but-valid values (a 22-year-old with $200K income—rare but possible) versus impossible values (140-year-old applicant—data entry error). These decisions directly impact model fairness: removing too many outliers may exclude underrepresented groups; keeping too many errors distorts predictions.
```

**Widget Features:**
- 6 scenarios with descriptive statistics and individual cases
- Each scenario presents a value and context
- Students choose: "Legitimate outlier" vs. "Data quality error"
- Feedback explains reasoning and business implications
- Scenarios include:
  1. Age = 140 years (ERROR - impossible)
  2. Age = 22 years (VALID - young applicant)
  3. Income = $250,000 (VALID - high earner)
  4. Employment_exp = 125,000 years (ERROR - absurd)
  5. Credit_score = 300 (VALID - poor credit but possible)
  6. Loan_status = 2 (ERROR - should be 0 or 1)

**Learning Outcomes Addressed:** MLO 3 (Identify data quality issues)

**Accessibility:**
- Keyboard navigation
- Screen reader support
- High contrast mode
- WCAG 2.2 AA compliant

#### COPY-PASTE EMBED CODE:

```html
<iframe
  src="https://[YOUR-WIDGET-HOST]/outlier-detection-quiz.html"
  width="100%"
  height="650"
  frameborder="0"
  title="Outlier Detection Quiz"
  aria-label="Interactive quiz for identifying data quality issues and outliers in loan dataset"
  allowfullscreen
  loading="lazy"
></iframe>
```

**Instructions Text (display above widget):**

```
For each scenario, examine the value in context and decide whether it's a legitimate outlier or a data quality error. Click your choice and read the feedback explanation.
```

---

## SUBSECTION 5: Data Visualization

---

### ELEMENT 15: Video - Segment 5: Visualization & Outliers

**Video Upload Instructions:**
- **Video Title:** Visualizing Data and Identifying Outliers with Plots
- **File Name:** `session3-segment5-visualization.mp4`
- **Duration:** 7 minutes 42 seconds
- **Timestamps:** 14:05 - 21:47
- **VTT Transcript:** Upload corresponding .vtt file

**Accessibility Attributes:**
- ✅ Captions enabled
- ✅ Transcript available below video

**Video Description Text:**

Learn to create visualizations that reveal data patterns and outliers. Explore count plots for loan approval distribution, boxplots for detecting outliers in age, and bar charts comparing interest rates by loan status. Understand how filtering outliers (removing applicants aged >100) improves data quality before model training.

**Bridge-In Text (display above video):**

```markdown
### Seeing Patterns: Data Visualization and Outlier Detection

Numbers alone obscure patterns—visualization reveals them instantly. This 8-minute segment demonstrates how charts expose relationships invisible in raw data: How many loans were approved vs. rejected? Do approved loans have higher interest rates? Where are the outliers hiding?

**What You'll Learn:**
- Creating count plots to visualize loan approval distribution (~35K rejected, ~10K approved)
- Using boxplots to identify outliers in person_age
- Comparing interest rates by loan status (approved loans = 13%, rejected = 11%)
- Filtering outliers: Removing applicants with age >100 using pandas
- Why subject matter expertise matters: Interpreting whether patterns make business sense
```

**Key Timestamps:**
- 14:05 - 15:50: Asking Gemini AI for visualization suggestions
- 15:50 - 17:04: Creating count plot showing loan approval distribution
- 17:04 - 18:20: Comparing interest rates by loan status (approved = 13%, rejected = 11%)
- 18:20 - 19:47: Using boxplots to visualize outliers in person_age
- 19:47 - 21:47: Filtering dataset to remove outliers (age between 15-100 years)

---

### ELEMENT 15b: Infobox (Action) - Now Try It: Visualize and Clean Your Data

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Create Visualizations and Filter Outliers

Practice creating visualizations and cleaning outliers in Colab:

**Step 1: Visualize loan approval distribution**
Ask Gemini AI: "Create a count plot showing loan_status distribution"
Run the code it provides and observe: How many loans were approved (1) vs. rejected (0)?

**Step 2: Check for outliers with a boxplot**
Ask Gemini: "Create a boxplot for person_age to identify outliers"
Look for dots outside the whiskers—these are potential outliers

**Step 3: Filter out impossible ages**
Run: `df_clean = df[(df['person_age'] >= 18) & (df['person_age'] <= 100)]`
Then run: `df_clean.shape` to see how many rows remain

**Reflection:** Why did we keep ages 18-100 but remove 140? This is a judgment call that affects who gets included in model training.

Once you've cleaned your data, continue to the next section on preprocessing.
```

**Design Notes:**
- Three concrete steps matching video
- Uses Gemini AI for code generation
- Includes reflection on data cleaning choices
- Clear continuation signal

---

### ELEMENT 16: Details Accordion - Visualization Best Practices

**Element Type:** Details Accordion
**Priority:** ◐ Recommended
**Reading Time:** Reference while practicing

**Introduction Text (above accordion):**

```markdown
## 📊 ML Data Visualization Guide

Expand each section below for guidelines on choosing visualizations for exploratory data analysis. Reference this guide when creating your own visualizations.
```

**Accordion Sections:**

<details>
<summary><strong>When to Use Each Chart Type (ML Context)</strong></summary>

**Count Plots (Categorical Distribution):**
- **Use for:** Showing how many observations fall into each category
- **Example:** Loan approval distribution (35K rejected, 10K approved)
- **Insight:** Reveals class imbalance—more rejected than approved loans
- **Why it matters:** Imbalanced datasets require special handling (model may predict "reject" for everyone and achieve 78% accuracy just by ignoring minority class)

**Boxplots (Outlier Detection):**
- **Use for:** Identifying outliers in numerical variables
- **Example:** Person age distribution with whiskers showing typical range and dots showing outliers (140 years)
- **Insight:** Visually flags impossible values for removal
- **Why it matters:** Outliers distort model training—removing them improves accuracy

**Bar Charts (Group Comparisons):**
- **Use for:** Comparing numerical values across categories
- **Example:** Average interest rate for approved (13%) vs. rejected (11%) loans
- **Insight:** Approved loans have higher interest rates—suggests banks charge more when risk is higher
- **Why it matters:** Patterns like this may reflect policy decisions or bias (do banks approve high-risk applicants only when they can charge premium rates?)

**Scatter Plots (Relationships Between Variables):**
- **Use for:** Exploring correlations between two numerical variables
- **Example:** Income vs. loan amount (do higher earners request larger loans?)
- **Insight:** Positive correlation suggests income influences loan size
- **Why it matters:** Helps identify features that predict target variable

</details>

<details>
<summary><strong>Subject Matter Expertise in Data Interpretation</strong></summary>

**Why SMEs Matter:**

The video instructor emphasizes a critical point: "You can't rely on generative AI to tell you what type of correlation or visualization you need. I'm the subject matter expert—the anchor."

**What This Means:**

- **AI suggests visualizations** but doesn't know your business context
- **You decide** which patterns are meaningful vs. coincidental
- **Domain knowledge** interprets whether findings make sense

**Example from Video:**

When the chart shows approved loans have 13% interest rates vs. 11% for rejected loans, the instructor hypothesizes: "Banks feel comfortable approving more loans when interest rates are higher—they're compensated for risk."

This interpretation requires understanding:
- **Bank risk management:** Higher rates compensate for default risk
- **Regulatory policy:** Some regulations may limit rates for high-risk applicants
- **Market dynamics:** Competition may force rate reductions

**AI cannot make these connections**—only a subject matter expert can determine whether the pattern reflects sound policy, business strategy, or potential bias.

**Your Role:**

When visualizations reveal patterns, ask:
1. Does this pattern make business sense?
2. Could this pattern reflect bias (e.g., systematically higher rates for certain demographics)?
3. What external factors might explain this relationship?
4. Should we investigate further or accept this as expected?

</details>

<details>
<summary><strong>Interpreting Class Imbalance</strong></summary>

**What is Class Imbalance?**

When your target variable has unequal distribution:
- **Example:** 35,000 rejected loans (78%) vs. 10,000 approved loans (22%)

**Why It Matters:**

A "lazy" model could predict "REJECT" for every applicant and achieve 78% accuracy without learning anything useful. This is why accuracy alone doesn't tell the full story—you need precision, recall, and F1 scores (covered in Module 3).

**Detecting Imbalance:**

Create a count plot of your target variable:
```python
df['loan_status'].value_counts().plot(kind='bar')
```

If one class dominates (>70%), you have imbalance.

**Solutions (Beyond This Session's Scope):**

- Oversampling minority class (duplicate approved loans)
- Undersampling majority class (reduce rejected loans)
- Weighted loss functions (penalize mistakes on minority class more heavily)
- Synthetic data generation (SMOTE technique)

**Why This Matters:**

Class imbalance is common in high-stakes ML applications. In criminal justice risk assessment, most defendants don't reoffend. If a model always predicts "low risk," it's accurate for the majority but useless for identifying high-risk individuals. This is where fairness metrics become essential—accuracy doesn't capture disproportionate impacts on specific groups. You'll explore this concept further in Module 3.

</details>

---

### ELEMENT 17: AI Chat - Data Visualization Q&A

**Element Type:** AI Chat Widget
**Priority:** ◐ Recommended
**Available:** Throughout subsection

#### AI CHAT CONFIGURATION:

**Widget Name:** Data Visualization Q&A

**System Prompt:**

```
You are a patient tutor helping MBA students understand data visualization in the context of machine learning exploratory data analysis.

Your role:
- Answer questions about choosing appropriate chart types for ML data exploration
- Explain how visualizations reveal outliers, class imbalance, and feature relationships
- Use business examples from loan approval, credit scoring, and risk assessment contexts
- If students are confused about specific chart interpretations, break down what patterns mean
- Encourage students to think critically about whether patterns reflect business logic or bias
- If asked about Python/pandas visualization code, provide clear syntax examples

Example topics you might discuss:
- "Why does the loan approval chart show more rejections than approvals?"
- "How do I interpret a boxplot showing outliers?"
- "What does it mean that approved loans have higher interest rates?"
- "How can I tell if my dataset has class imbalance?"
- "Can you explain this matplotlib code?"

Keep responses concise (2-3 paragraphs maximum). Ask clarifying questions if needed. Always connect technical concepts to business implications.
```

**Welcome Message:**

```
Hi! I can help clarify data visualization concepts, chart interpretation, and how visualizations reveal patterns relevant to machine learning. What questions do you have?
```

**Show System Prompt to User:** No

**Suggested Prompts (display as quick-start buttons):**
- "Why use boxplots for outlier detection?"
- "What does class imbalance mean?"
- "How do I interpret the interest rate comparison chart?"
- "Can you explain this visualization code?"

---

## SUBSECTION 6: Data Preprocessing

---

### ELEMENT 18: Video - Segment 6: One-Hot Encoding & Standardization

**Video Upload Instructions:**
- **Video Title:** Preprocessing Data: Encoding and Standardization
- **File Name:** `session3-segment6-preprocessing.mp4`
- **Duration:** 6 minutes 43 seconds
- **Timestamps:** 21:47 - 28:30
- **VTT Transcript:** Upload corresponding .vtt file

**Accessibility Attributes:**
- ✅ Captions enabled
- ✅ Transcript available below video

**Video Description Text:**

Learn why machine learning algorithms require numerical inputs and how to preprocess data accordingly. Understand one-hot encoding (converting categorical variables like "Bachelor," "Master's," "PhD" into binary columns) and standardization (scaling numerical variables like income and age to comparable ranges). See how preprocessing transforms your dataset from 14 columns to 23 columns, all numeric and ready for model training.

**Bridge-In Text (display above video):**

```markdown
### Preparing Data for Machine Learning Algorithms

Machine learning algorithms perform mathematical calculations—they can't process text like "Male" or "Bachelor's degree." Preprocessing converts all data to numbers while preserving meaning. This 7-minute segment demonstrates two essential techniques: one-hot encoding for categorical variables and standardization for numerical variables.

**What You'll Learn:**
- Why ML requires numerical inputs (algorithms perform matrix multiplication)
- **One-hot encoding:** Converting "Bachelor," "Master's," "PhD" into binary columns (1 = yes, 0 = no)
- How encoding expands dataset from 14 → 23 columns
- **Standardization:** Scaling numerical variables (income, age) to comparable ranges
- Using StandardScaler from scikit-learn to normalize values
- Why standardization matters: Prevents large values (income = $100K) from dominating small values (age = 35)
```

**Key Timestamps:**
- 21:47 - 23:04: Identifying categorical variables needing encoding (gender, education, loan_intent, home_ownership)
- 23:04 - 24:10: Explaining one-hot encoding with education example (Bachelor → 3 binary columns)
- 24:10 - 25:42: Running `pd.get_dummies()` to create one-hot encoded DataFrame (14 → 23 columns)
- 25:42 - 27:24: Standardizing numerical variables using StandardScaler
- 27:24 - 28:30: Displaying standardized dataset and confirming shape (45,000 rows, 23 columns)

---

### ELEMENT 18b: Infobox (Action) - Now Try It: Preprocess Your Data

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Apply One-Hot Encoding and Standardization

Transform your cleaned dataset into ML-ready format in Colab:

**Step 1: One-Hot Encode Categorical Variables**
Ask Gemini: "Apply one-hot encoding to the categorical columns in my DataFrame"
Run `df_encoded = pd.get_dummies(df_clean, drop_first=True)`
Run `df_encoded.shape` — you should see more columns now (categorical variables expanded)

**Step 2: Standardize Numerical Variables**
Ask Gemini: "Standardize the numerical columns using StandardScaler"
The code will use `from sklearn.preprocessing import StandardScaler`
After running, your numerical values should be centered around 0

**Verify your preprocessing:**
- Run `df_encoded.head()` — all values should be numbers (no text)
- Check `df_encoded.shape` — more columns than original (due to encoding)

Once your data is preprocessed, you're ready to build your ML model! Continue to the next video.
```

**Design Notes:**
- Two clear preprocessing steps
- Uses Gemini AI for code assistance
- Verification checks included
- Links to model building

---

### ELEMENT 19: Text - Why Preprocess? Business Context

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```markdown
# The Business Logic Behind Preprocessing

Preprocessing isn't arbitrary technical complexity—it directly impacts model performance and fairness. Each preprocessing decision shapes which patterns the algorithm can learn and which it misses.

**Why One-Hot Encoding?**

Imagine encoding education levels as numbers: High School = 1, Bachelor = 2, Master = 3, PhD = 4. The algorithm would interpret this as PhD being "4× better" than High School—a mathematical relationship that doesn't reflect reality. One-hot encoding prevents false ordinal assumptions by treating each category independently.

**Why Standardization?**

Income ranges from $20K to $250K while age ranges from 18 to 80. Without standardization, income dominates the model simply because its numbers are larger—not because it's more predictive. Standardization gives each variable equal opportunity to influence predictions, letting the algorithm discover which features truly matter.

**Bias Implications:**

Preprocessing choices affect fairness. If you encode "Female" as 0 and "Male" as 1, does the model interpret "Male" as superior? One-hot encoding avoids this by creating separate binary columns. Similarly, if you remove outliers (ages >100), you're making a judgment call: What threshold excludes errors without excluding legitimate edge cases? These decisions accumulate into algorithmic bias.
```

**Design Notes:**
- 149 words (under 150-word limit)
- Bold key questions for engagement
- Connects preprocessing to bias
- Business logic for technical choices

---

### ELEMENT 20: iFrame Widget - Preprocessing Simulator

**Element Type:** iFrame Widget
**Priority:** ⬤ Required
**Interaction Time:** 5 minutes

#### WIDGET INTRODUCTION (display above widget):

```markdown
### ⚙ Interactive Activity: Preprocessing Data Step-by-Step

**Practice: MLO 4 (Preprocess data using one-hot encoding and standardization)**

You're now ready to preprocess data hands-on. This simulator presents a mini loan dataset (10 applicants with 5 variables) and challenges you to apply one-hot encoding to categorical variables and standardization to numerical variables. Your task: transform messy mixed-type data into clean numerical inputs ready for machine learning.

This widget reveals exactly how preprocessing works behind the scenes. You'll click "Encode" to watch categorical columns (education: "Bachelor," "Master's," "PhD") split into binary columns (education_Bachelor: 1/0, education_Masters: 1/0, education_PhD: 1/0). Then you'll click "Standardize" to see numerical values (income: $45K, $89K, $120K) transform into standardized scores (income: -0.8, 0.3, 1.2). By completing both steps, you'll understand why preprocessing is essential and how each technique preserves information while converting everything to numbers.
```

**Widget Features:**
- Mini dataset with 10 applicants, 5 columns (3 numerical, 2 categorical)
- Two-stage process:
  1. **Stage 1 - One-Hot Encoding:**
     - Shows original DataFrame with categorical columns (gender, education)
     - "Encode Categorical Variables" button
     - Result: 5 columns → 8 columns (gender_Male, gender_Female, education_Bachelor, education_Masters, education_PhD)
     - Side-by-side before/after comparison
  2. **Stage 2 - Standardization:**
     - Shows DataFrame with numerical columns (age, income, credit_score)
     - "Standardize Numerical Variables" button
     - Result: Raw values → standardized values (mean=0, std=1)
     - Tooltip explaining formula: (value - mean) / std_dev
- Progress tracking (Stage 1/2 → 2/2)
- "Check Understanding" quiz at end (3 questions about preprocessing effects)

**Learning Outcomes Addressed:** MLO 4 (Preprocess data)

**Accessibility:**
- Keyboard navigation
- Screen reader support for tables
- High contrast mode
- WCAG 2.2 AA compliant

#### COPY-PASTE EMBED CODE:

```html
<iframe
  src="https://[YOUR-WIDGET-HOST]/preprocessing-simulator.html"
  width="100%"
  height="700"
  frameborder="0"
  title="Preprocessing Simulator - One-Hot Encoding and Standardization"
  aria-label="Interactive tool for practicing data preprocessing with one-hot encoding and standardization"
  allowfullscreen
  loading="lazy"
></iframe>
```

**Instructions Text (display above widget):**

```
Complete Stage 1 by clicking "Encode Categorical Variables" and observing how categories become binary columns. Then complete Stage 2 by clicking "Standardize Numerical Variables" and seeing raw values transform into standardized scores. Answer the quiz questions to check your understanding.
```

---

## SUBSECTION 7: Building the ML Model

---

### ELEMENT 21: Video - Segment 7: Model Building & Evaluation

**Video Upload Instructions:**
- **Video Title:** Building and Evaluating a Logistic Regression Model
- **File Name:** `session3-segment7-model-building.mp4`
- **Duration:** 11 minutes 51 seconds
- **Timestamps:** 28:30 - 40:21
- **VTT Transcript:** Upload corresponding .vtt file

**Accessibility Attributes:**
- ✅ Captions enabled
- ✅ Transcript available below video

**Video Description Text:**

Learn the complete machine learning workflow: splitting data into training (80%) and testing (20%) sets, training a logistic regression model using scikit-learn, making predictions on unseen data, and evaluating accuracy. Understand why you can't train and test on the same data, what 89% accuracy means in business terms, and how model evaluation reveals whether predictions are reliable.

**Bridge-In Text (display above video):**

```markdown
### From Data to Predictions: The ML Model Workflow

This 12-minute segment is the culmination of all previous steps. You've loaded, explored, cleaned, and preprocessed data—now you'll build the actual machine learning model. Watch as the instructor explains the train-test split (why you need separate data for training and evaluation), trains a logistic regression model, generates predictions, and calculates 89% accuracy.

**What You'll Learn:**
- **Splitting data 80/20:** 36,000 rows for training, 9,000 rows for testing
- Why separate X (features) from y (target variable)
- **Training the model:** Using `LogisticRegression()` from scikit-learn
- The `.fit()` method: How the algorithm learns patterns from training data
- **Making predictions:** Using `.predict()` on test data (data the model has never seen)
- **Calculating accuracy:** Comparing predictions to actual outcomes (89% match)
- What 89% accuracy means: The model replicates human decisions 89% of the time
```

**Key Timestamps:**
- 28:30 - 30:42: Explaining the train-test split concept (why you can't test on training data)
- 30:42 - 32:40: Separating features (X) from target variable (y = loan_status)
- 32:40 - 34:30: Using `train_test_split()` from scikit-learn (80% train, 20% test, random_state=42)
- 34:30 - 35:50: Training the logistic regression model with `.fit(X_train, y_train)`
- 35:50 - 37:30: Making predictions with `.predict(X_test)` and displaying first 10 predictions
- 37:30 - 40:21: Calculating accuracy score (89%) and interpreting what this means

---

### ELEMENT 21b: Infobox (Action) - Now Try It: Build Your ML Model

**Element Type:** Infobox
**Variant:** Action (🎯 icon)
**Priority:** ⬤ Required
**Reading Time:** 3 minutes

#### COPY-PASTE CONTENT:

```
Title: 🎯 Now Try It: Train and Evaluate Your Loan Approval Model

This is the big moment—build your own machine learning model in Colab:

**Step 1: Prepare Features (X) and Target (y)**
Ask Gemini: "Separate my DataFrame into features X and target variable y (loan_status)"
You should have X with all columns except loan_status, and y with just loan_status

**Step 2: Split into Training and Testing Sets**
Ask Gemini: "Split X and y into 80% training and 20% testing sets"
The code will use `from sklearn.model_selection import train_test_split`
Confirm: `X_train.shape` should show ~36,000 rows

**Step 3: Train the Model**
Ask Gemini: "Train a logistic regression model on my training data"
Run the `.fit()` code—this is where the algorithm learns patterns!

**Step 4: Make Predictions and Check Accuracy**
Ask Gemini: "Make predictions on the test set and calculate accuracy"
You should see accuracy around 89%

Congratulations! You've built a complete machine learning model from scratch. Continue reading to understand what 89% accuracy really means.
```

**Design Notes:**
- Four clear steps matching video
- Uses Gemini AI throughout
- Celebrates completion
- Sets up accuracy discussion

---

### ELEMENT 22: Text - Understanding 89% Accuracy

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 2 minutes

#### COPY-PASTE CONTENT:

```markdown
# What Does 89% Accuracy Really Mean?

Your model achieved 89% accuracy—it correctly predicted loan approval/rejection for 8,010 out of 9,000 test cases. This sounds impressive, but accuracy alone doesn't tell the complete story about model performance or fairness.

**What 89% Accuracy Tells You:**

The model replicates past human decisions 89% of the time. If historical loan officers approved certain profiles and rejected others, your model learned those patterns and applies them to new applicants with 89% consistency.

**What 89% Accuracy Doesn't Tell You:**

- **Which 11% did it get wrong?** Are errors random or concentrated in specific groups (young applicants, low-income applicants, certain neighborhoods)?
- **Does high accuracy mean fairness?** If historical decisions were biased, the model perpetuates that bias at 89% accuracy
- **Class imbalance:** With 78% rejections in the dataset, a lazy model predicting "reject" for everyone achieves 78% accuracy without learning anything

**Preview: When Accuracy Masks Bias**

In Module 3, you'll study a real case where a recidivism prediction algorithm achieved ~65-70% accuracy, leading courts to trust its predictions. An investigation revealed that while overall accuracy seemed acceptable, **error rates differed by race.** Accuracy masked unfairness.

This is why later sessions explore precision, recall, and fairness metrics that reveal what accuracy conceals.
```

**Design Notes:**
- 149 words (under 150-word limit)
- Bold section headers for clarity
- Previews Module 3 case study on algorithmic bias
- Sets up Module 3 discussion on fairness metrics

---

### ELEMENT 23: iFrame Widget - Train-Test Split Visualizer

**Element Type:** iFrame Widget
**Priority:** ◐ Recommended
**Interaction Time:** 4 minutes

#### WIDGET INTRODUCTION (display above widget):

```markdown
### ⚙ Interactive Activity: Understanding Train-Test Split

**Practice: MLO 5 (Build and evaluate a logistic regression model with 80/20 train-test split)**

Why can't you test a model on the same data you trained it on? This visualizer demonstrates the train-test split concept through an interactive animation. Your task: drag the split slider from 50/50 to 80/20 and observe how training data size affects model performance and generalization.

This widget reveals the core principle of machine learning evaluation: Models must prove they can predict unseen data, not just memorize training examples. You'll see how splitting data into training (80%) and testing (20%) sets allows you to measure whether the model generalizes or overfits. The animation shows data rows being randomly assigned to training vs. testing sets, preserving the 78% rejection rate in both to avoid bias. By experimenting with different split ratios, you'll understand why 80/20 is standard practice in machine learning.
```

**Widget Features:**
- Visual representation of 45,000 loan applications as blocks
- Interactive slider to adjust train-test split ratio (50/50 → 90/10)
- Animation showing random assignment to training vs. testing sets
- Real-time stats display:
  - Training set size
  - Testing set size
  - Approval rate in training set (should match overall ~22%)
  - Approval rate in testing set (should match overall ~22%)
- Explanation of why proportions must match (avoid sampling bias)
- "Test Your Understanding" quiz (3 questions):
  1. Why do we need a test set?
  2. What happens if you test on training data?
  3. Why is 80/20 a common split?

**Learning Outcomes Addressed:** MLO 5 (Build and evaluate with train-test split)

**Accessibility:**
- Keyboard navigation (arrow keys for slider)
- Screen reader descriptions of visual states
- High contrast mode
- WCAG 2.2 AA compliant

#### COPY-PASTE EMBED CODE:

```html
<iframe
  src="https://[YOUR-WIDGET-HOST]/train-test-split-visualizer.html"
  width="100%"
  height="650"
  frameborder="0"
  title="Train-Test Split Visualizer"
  aria-label="Interactive visualization of train-test split concept in machine learning"
  allowfullscreen
  loading="lazy"
></iframe>
```

**Instructions Text (display above widget):**

```
Adjust the split ratio slider and observe how data is divided between training and testing sets. Notice how proportions are preserved in both sets. Answer the quiz questions to confirm understanding.
```

---

## SUBSECTION 8: Wrap-Up & Looking Ahead

---

### ELEMENT 24: Text - Preview: Why Bias Matters in ML

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 3 minutes

#### COPY-PASTE CONTENT:

```markdown
# Why This Matters: From Loan Approvals to Life-Changing Decisions

You've now experienced the complete machine learning development cycle. But here's a critical question: **What happens when algorithms like the one you just built are used for decisions that change lives?**

**Consider the decisions you made:**

- You chose which variables to include (age, income, credit score)
- You decided how to handle outliers (remove ages over 100?)
- You encoded categories into numbers (education levels, loan intent)
- You accepted 89% accuracy as "good enough"

Each of these choices shaped your model's predictions. Now imagine similar choices being made for algorithms that determine:

- **Who gets a job interview** (resume screening algorithms)
- **Who qualifies for a mortgage** (credit scoring systems)
- **Who gets released on bail** (criminal justice risk assessments)
- **Who receives medical treatment** (healthcare triage algorithms)

**The Stakes Get Higher:**

Your loan model achieved 89% accuracy—but which 11% did it get wrong? Are errors randomly distributed, or do they disproportionately affect certain groups? If historical loan officers were biased against young applicants or certain neighborhoods, your model may have learned those patterns.

**What's Coming in This Course:**

In Module 2, you'll explore different types of machine learning (supervised, unsupervised, reinforcement) and understand when each applies. In Module 3, you'll analyze a real case—the COMPAS algorithm used in courtrooms—where a major investigation revealed that "accurate" predictions masked racial bias in error rates. You'll learn to identify nine types of bias that can enter at each stage of the ML development cycle you just experienced.

The goal isn't to fear AI—it's to understand it deeply enough to build and deploy it responsibly.
```

**Design Notes:**
- 280 words (summary/wrap-up elements can exceed 150 words)
- Connects hands-on experience to high-stakes applications
- Previews Sessions 2 and 3 content
- Raises ethical questions without assuming prior knowledge

---

### ELEMENT 25: Details Accordion - ML Development Cycle Summary

**Element Type:** Details Accordion
**Priority:** ⬤ Required
**Reading Time:** Reference material

**Introduction Text (above accordion):**

```markdown
## 🔄 ML Development Cycle: Complete Reference

Expand each stage below to review what you learned and how bias can enter at each stage of ML development.
```

**Accordion Sections:**

<details>
<summary><strong>Stage 1: Setup Environment</strong></summary>

**What You Did:**
- Opened Google Colab
- Created a new notebook
- Mounted Google Drive
- Uploaded loan dataset CSV

**Key Concepts:**
- Cloud-based Python environments eliminate setup barriers
- Gemini AI provides code assistance

**Bias Connection:**
Some commercial ML systems use proprietary software and closed datasets. Lack of transparency makes it impossible for affected individuals to challenge predictions or understand how scores were calculated. Open environments like Colab enable reproducibility and scrutiny—values you'll explore in Module 3.

</details>

<details>
<summary><strong>Stage 2: Load Data</strong></summary>

**What You Did:**
- Used `import pandas as pd` to load pandas library
- Used `pd.read_csv()` to load loan dataset
- Displayed first 5 rows with `df.head()`

**Key Concepts:**
- DataFrames organize data in rows (observations) and columns (variables)
- Loading reveals dataset structure immediately

**Bias Connection:**
Data collection decisions determine what models can learn. If records are incomplete for certain neighborhoods or demographics, the model learns different patterns for different groups—creating measurement bias. You'll examine real examples of this in Module 3.

</details>

<details>
<summary><strong>Stage 3: Explore Data</strong></summary>

**What You Did:**
- Examined column names and first 5 rows
- Identified categorical vs. numerical variables
- Identified target variable (loan_status)

**Key Concepts:**
- Understanding data structure precedes analysis
- Target variable is what you're predicting (loan_status, recidivism, etc.)

**Bias Connection:**
Choosing which variables to include involves value judgments. Is "family structure" predictive of an outcome or a proxy for socioeconomic status that correlates with race? Is "neighborhood" a legitimate factor or an encoded proxy for demographics? Feature selection can introduce representation bias—a concept you'll explore deeply in Module 3.

</details>

<details>
<summary><strong>Stage 4: Describe Data</strong></summary>

**What You Did:**
- Used `df.shape` to check row and column count
- Used `df.info()` to check data types and missing values
- Used `df.describe()` for descriptive statistics (mean, min, max)
- Identified outliers (140-year-old applicants)

**Key Concepts:**
- Descriptive statistics reveal data quality issues
- Outliers can be legitimate extreme values or errors

**Bias Connection:**
Were all records complete? Did missing data disproportionately affect certain groups? If one demographic has more comprehensive tracking than another, the model learns different patterns—creating aggregation bias. Deciding which outliers to remove involves judgment calls that affect who gets included in model training.

</details>

<details>
<summary><strong>Stage 5: Visualize Data</strong></summary>

**What You Did:**
- Created count plots showing loan approval distribution (35K rejected, 10K approved)
- Created bar charts comparing interest rates by loan status
- Used boxplots to identify outliers in person_age
- Filtered dataset to remove outliers (age between 15-100)

**Key Concepts:**
- Visualizations reveal patterns invisible in raw numbers
- Class imbalance (78% rejections) affects model training
- Filtering outliers is a judgment call requiring subject matter expertise

**Bias Connection:**
Many high-stakes ML applications face class imbalance. While overall accuracy may look acceptable, error types can differ by demographic group. Visualizing disaggregated outcomes—not just overall accuracy—exposes bias hidden in aggregate metrics. Module 3 explores a famous case where this analysis revealed hidden unfairness.

</details>

<details>
<summary><strong>Stage 6: Preprocess Data</strong></summary>

**What You Did:**
- Applied one-hot encoding to categorical variables (gender, education, loan_intent, home_ownership)
- Expanded dataset from 14 → 23 columns
- Standardized numerical variables (age, income, employment_exp, credit_score) using StandardScaler
- Transformed raw values to mean=0, std=1

**Key Concepts:**
- ML algorithms require numerical inputs
- One-hot encoding prevents false ordinal assumptions
- Standardization gives each variable equal opportunity to influence predictions

**Bias Connection:**
Encoding choices matter: Should "low-income neighborhood" be binary (yes/no) or categorical (5 levels)? These decisions affect how the model weighs factors. If preprocessing amplifies race-correlated signals while downweighting individual circumstances, the model can perpetuate learning bias—a concept central to Module 3's case study.

</details>

<details>
<summary><strong>Stage 7: Build and Evaluate Model</strong></summary>

**What You Did:**
- Split data 80/20 into training (36,000 rows) and testing (9,000 rows) sets
- Separated features (X) from target variable (y = loan_status)
- Trained logistic regression model using `LogisticRegression().fit(X_train, y_train)`
- Generated predictions using `.predict(X_test)`
- Calculated accuracy: 89%

**Key Concepts:**
- Train-test split prevents overfitting (model must generalize to unseen data)
- Accuracy measures overall correctness but doesn't reveal error distribution
- 89% accuracy means the model replicates human decisions 89% of the time

**Bias Connection:**
Some ML systems achieve 65-70% accuracy on high-stakes predictions, leading decision-makers to trust their outputs. But accuracy alone can mask evaluation bias—fair models require analyzing error types across demographic groups, not just overall correctness. In Module 3, you'll study a case where acceptable overall accuracy hid significant disparities in error rates.

**The Fundamental Question:**
If an algorithm replicates biased human decisions with high accuracy, is it objective or is it automating discrimination? This question drives our exploration of AI ethics throughout the course.

</details>

---

### ELEMENT 26: AI Chat - ML Development Q&A

**Element Type:** AI Chat Widget
**Priority:** ◐ Recommended
**Available:** Throughout session

#### AI CHAT CONFIGURATION:

**Widget Name:** ML Development Q&A

**System Prompt:**

```
You are a patient tutor helping MBA students understand machine learning development concepts in the context of business applications and algorithmic bias.

Your role:
- Answer questions about the ML development cycle (data loading, exploration, preprocessing, model training, evaluation)
- Explain pandas, scikit-learn, and Google Colab concepts in business-friendly language
- Connect technical concepts to real-world applications and preview the algorithmic bias discussion from Module 3
- If students are confused about specific steps, break down the process into smaller parts
- Encourage critical thinking about where bias can enter the ML development cycle
- If asked about Python code, provide clear syntax examples with explanations

Example topics you might discuss:
- "Why do we need to split data into training and testing sets?"
- "What's the difference between one-hot encoding and label encoding?"
- "Is 89% accuracy good enough for real-world decisions?"
- "Can you explain what pandas DataFrames are?"
- "Where can bias enter during data preprocessing?"

Keep responses concise (2-3 paragraphs maximum). Ask clarifying questions if needed. Always connect technical concepts to business and ethical implications.
```

**Welcome Message:**

```
Hi! I can help clarify machine learning development concepts, Python code, and connections to algorithmic bias. What questions do you have about today's session?
```

**Show System Prompt to User:** No

**Suggested Prompts (display as quick-start buttons):**
- "Why split data 80/20 for training and testing?"
- "What is one-hot encoding and why use it?"
- "How does preprocessing affect model fairness?"
- "Can you explain this pandas code?"

---

### ELEMENT 27: Text - Module Summary & Next Steps

**Element Type:** Text Block
**Priority:** ⬤ Required
**Reading Time:** 3 minutes

#### COPY-PASTE CONTENT:

```markdown
# Module 1 Complete: You've Built a Machine Learning Model

Congratulations! You've completed the hands-on machine learning development session. You navigated Google Colab, loaded and explored a real dataset with 45,000 loan applications, identified data quality issues, preprocessed data using encoding and standardization, and built a logistic regression model that achieved 89% accuracy.

**Key Skills You've Developed:**

- **MLO 1:** Navigate Google Colab, execute code cells, and use Gemini AI for assistance ✅
- **MLO 2:** Load CSV files into pandas DataFrames and explore data structure ✅
- **MLO 3:** Identify outliers, missing values, and data type issues ✅
- **MLO 4:** Apply one-hot encoding and standardization for ML preprocessing ✅
- **MLO 5:** Build and evaluate logistic regression models with train-test splits ✅
- **MLO 6:** Interpret accuracy and understand its limitations ✅

**What You Learned About Bias:**

Every stage of ML development involves choices that affect model fairness:
- **Data loading:** Which variables to include (representation bias)
- **Data cleaning:** Which outliers to remove (measurement bias)
- **Preprocessing:** How to encode categorical variables (aggregation bias)
- **Model training:** Which algorithms and parameters to use (learning bias)
- **Evaluation:** Which metrics to prioritize (evaluation bias)

These aren't just technical decisions—they're value judgments that shape algorithmic outcomes and fairness.

**Looking Ahead: Module 2 - ML Techniques**

In Module 2, you'll explore different types of machine learning: supervised learning (like the logistic regression you just built), unsupervised learning (finding patterns without labeled outcomes), and reinforcement learning (learning through trial and error). You'll use comic-based cases and interactive simulations to understand when each approach applies.

**What's Coming in Module 3:**

Now that you've experienced ML development firsthand, you'll be ready to critically analyze a famous case study about algorithmic bias in courtroom risk assessment. You'll examine how an investigation revealed racial disparities in error rates, explore competing definitions of fairness, and apply the technical foundation you've built here to understand where bias enters and how stakeholders debate algorithmic accountability.

**Action Items:**

1. **Optional Practice:** Access the Google Colab notebook used in this session and experiment with different preprocessing choices (try different outlier thresholds, encoding strategies)
2. **Reflect:** How would you explain to a non-technical stakeholder whether 89% accuracy is "good enough" for high-stakes decisions?
3. **Preview Module 2:** Think about examples of AI learning from labeled data vs. finding patterns on its own

Click "Mark as Complete" when you're ready to move forward!
```

**Design Notes:**
- 379 words (final summary can exceed 150 words)
- Checklist of MLOs achieved
- Explicit bridge to Module 2 and preview of Module 3 case study
- Action items for next steps

---

## COURSE CONNECTION: How This Session Supports Your Learning

**This session provides the foundational hands-on experience for the "Fundamentals of AI for Business" course, building technical literacy that supports all subsequent sessions.**

**How Module 1 Connects to Course Learning Objectives:**

**CLO 2: Apply hands-on understanding of ML development**

You didn't just read about machine learning—you built a real model using Google Colab, pandas, and scikit-learn. This hands-on experience demystifies ML development and prepares you to:
- Evaluate vendor claims about AI capabilities with technical literacy
- Participate in AI implementation decisions with informed skepticism
- Recognize when technical jargon obscures meaningful evaluation

**CLO 3: Explain the ML development process and evaluate how bias emerges at each stage**

By experiencing all seven stages (setup, load, explore, describe, visualize, preprocess, build/evaluate), you now understand where bias can enter:
- **Data-to-Algorithm Bias:** Measurement (incomplete arrest records), Representation (which variables included), Aggregation (how variables encoded)
- **Algorithm-to-Users Bias:** Learning (which patterns the model finds), Evaluation (which metrics prioritized)
- **Users-to-Data Bias:** Historical (biased past decisions), Deployment (how predictions are used)

This framework prepares you for the bias case analysis in Module 3.

**How Module 1 Prepares You for Module 2 (ML Techniques):**

Module 2 explores **different types of machine learning**—supervised, unsupervised, and reinforcement learning. Your hands-on experience building a supervised model helps you:
- Understand what makes supervised learning different (labeled outcomes, prediction focus)
- Compare to unsupervised approaches (pattern discovery without labels)
- Recognize when each approach applies in business contexts

**How Module 1 Sets Up Module 3 (ML Development and Bias):**

Module 3 examines **algorithmic bias through a famous case study**. Your hands-on experience reveals why:
- Technical choices involve value judgments (which outliers to remove, which accuracy is acceptable)
- ML development requires cross-functional coordination (data scientists, domain experts, ethicists)
- Bias can enter at any stage of the development cycle you just experienced

**Real-World Application:**

MBA leaders who understand ML development can:
- **Evaluate AI vendors** with technical literacy ("How did you validate your training data? What's your false positive rate by demographic group?")
- **Participate in AI governance** with informed perspectives on where bias enters and how to mitigate it
- **Make implementation decisions** understanding trade-offs between automation (cost savings) and augmentation (quality, fairness, worker satisfaction)

This session transformed you from AI consumer to AI-literate manager ready to shape how organizations design, deploy, and govern machine learning systems responsibly.

---

## ACCESSIBILITY CHECKLIST

✅ All videos have VTT captions
✅ All videos have full transcripts available below player
✅ All widgets are keyboard navigable
✅ All widgets have ARIA labels and roles
✅ All infoboxes use simple paragraph format (no bullets/headings)
✅ Color contrast meets WCAG 2.2 AA (4.5:1)
✅ No text blocks exceed 150 words (except summaries/wrap-ups)
✅ All interactive elements have focus indicators
✅ Screen reader compatibility verified
✅ Alt text provided for all visual elements

---

## WIDGET TECHNICAL SPECIFICATIONS

### Widget 1: Colab Interface Explorer (colab-interface-explorer.html)
**Framework:** Vanilla JS + HTML/CSS
**Size:** Responsive (min-width: 320px)
**Accessibility:** WCAG 2.2 AA compliant, keyboard navigable, ARIA labels
**Features:**
- Simulated Colab UI with clickable cells
- 5 guided tasks with visual feedback
- Progress tracking (1/5 → 5/5)
- No external dependencies

### Widget 2: Outlier Detection Quiz (outlier-detection-quiz.html)
**Framework:** Vanilla JS + HTML/CSS
**Size:** Responsive (min-width: 320px)
**Accessibility:** WCAG 2.2 AA compliant, keyboard navigable, ARIA labels
**Features:**
- 6 scenarios with contextual data
- Binary choice: "Legitimate outlier" vs. "Data quality error"
- Feedback explaining reasoning and business implications
- Score tracking

### Widget 3: Preprocessing Simulator (preprocessing-simulator.html)
**Framework:** Vanilla JS + HTML/CSS
**Size:** Responsive (min-width: 320px)
**Accessibility:** WCAG 2.2 AA compliant, keyboard navigable, ARIA labels
**Features:**
- Mini dataset (10 applicants, 5 variables)
- Two-stage process: Encoding → Standardization
- Side-by-side before/after comparison
- "Check Understanding" quiz (3 questions)

### Widget 4: Train-Test Split Visualizer (train-test-split-visualizer.html)
**Framework:** Vanilla JS + HTML/CSS
**Size:** Responsive (min-width: 320px)
**Accessibility:** WCAG 2.2 AA compliant, keyboard navigable, ARIA labels
**Features:**
- Visual representation of 45,000 data points as blocks
- Interactive slider for split ratio (50/50 → 90/10)
- Animation showing random assignment
- Real-time stats display (training size, testing size, approval rates)
- "Test Your Understanding" quiz (3 questions)

---

**END OF SESSION 3 STORYBOARD**
