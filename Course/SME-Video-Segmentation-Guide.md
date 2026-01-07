# SME Video Segmentation Guide
## Fundamentals of AI for Business (FUNAI)

**Source Video:** Professor Rahrovani's Google Colab Walkthrough
**Source Transcript:** Video Project 14_Captions_English (United States).txt
**Total Source Duration:** ~40 minutes
**Output:** 7 video segments for Module 1 (AI Systems)

---

## Overview

This document provides editing instructions for segmenting Professor Rahrovani's recorded Google Colab walkthrough into 7 individual videos. Each segment covers a distinct phase of the ML development process and aligns with specific Module Learning Outcomes (MLOs).

**Editing Tool Recommendation:** Adobe Premiere Pro
**Export Settings:** H.264 MP4, 1080p, 8-12 Mbps bitrate, AAC 256kbps audio

---

## Video Segments

### VIDEO #4 IO - Self-Paced - FUNAI - M1, V2 (Getting Started with Google Colab)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-01-colab-intro.mp4 |
| **Duration** | 2:01 |
| **Storyboard Location** | AI Systems module, Element 5 |
| **MLO Addressed** | MLO 1: Navigate Google Colab environment and execute Python code cells |

**Video Title (for Panopto/LMS):**
Getting Started with Google Colab

**Video Description:**
Professor Rahrovani introduces Google Colab, a free cloud-based Python environment. Learn how to create a new notebook, understand the interface layout, and prepare your workspace for machine learning development. No software installation required - everything runs in your browser.

**Transcript Cut Points:**
- **START at:** "So what? I'm gonna start, um. So you see my screen?"
- **END before:** "So when we create a new interactive Python notebook, as I just did"

---

### VIDEO #5 IO - Self-Paced - FUNAI - M1, V3 (Loading the Loan Dataset)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-02-load-data.mp4 |
| **Duration** | 3:01 |
| **Storyboard Location** | AI Systems module, Element 7 |
| **MLO Addressed** | MLO 2: Load and explore datasets using pandas DataFrames |

**Video Title (for Panopto/LMS):**
Loading the Loan Dataset

**Video Description:**
Learn how to load real-world data into Google Colab. Professor Rahrovani demonstrates uploading a CSV file containing 45,000 loan applications and importing it into a pandas DataFrame - the foundation for all our machine learning work.

**Transcript Cut Points:**
- **START at:** "So when we create a new interactive Python notebook, as I just did, you have a kind of a blank"
- **END before:** "Uh, and it gives you the option of accepting but not running"

---

### VIDEO #6 IO - Self-Paced - FUNAI - M1, V4 (Exploring the Data Structure)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-03-explore-data.mp4 |
| **Duration** | 4:21 |
| **Storyboard Location** | AI Systems module, Element 9 |
| **MLO Addressed** | MLO 2: Load and explore datasets using pandas DataFrames |

**Video Title (for Panopto/LMS):**
Exploring the Data Structure

**Video Description:**
Your first look at the loan dataset. Professor Rahrovani uses df.head() to examine the first rows, identifying the 14 columns including person_age, person_income, loan_amount, and the target variable loan_status. This exploratory phase is where you begin to understand what patterns might exist in the data.

**Transcript Cut Points:**
- **START at:** "Uh, and it gives you the option of accepting but not running or accepting and running"
- **END before:** "What if if I want to know more. So describe."

---

### VIDEO #7 IO - Self-Paced - FUNAI - M1, V5 (Understanding Data Types and Statistics)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-04-describe-data.mp4 |
| **Duration** | 4:42 |
| **Storyboard Location** | AI Systems module, Element 13 |
| **MLO Addressed** | MLO 3: Identify data quality issues (outliers, missing values, data types) |

**Video Title (for Panopto/LMS):**
Understanding Data Types and Statistics

**Video Description:**
Dive deeper into the dataset using df.shape, df.info(), and df.describe(). Professor Rahrovani shows how to identify which columns are numerical vs. categorical, check for missing values, and spot potential data quality issues like suspiciously high ages (140 years!) that will need addressing.

**Transcript Cut Points:**
- **START at:** "What if if I want to know more. So describe."
- **END before:** "So what about if I want to get some visualization"

---

### VIDEO #8 IO - Self-Paced - FUNAI - M1, V6 (Visualizing Data Distributions)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-05-visualization.mp4 |
| **Duration** | 7:42 |
| **Storyboard Location** | AI Systems module, Element 15 |
| **MLO Addressed** | MLO 3: Identify data quality issues (outliers, missing values, data types) |

**Video Title (for Panopto/LMS):**
Visualizing Data Distributions

**Video Description:**
See the data come alive through visualizations. Professor Rahrovani creates histograms and plots to understand how variables are distributed across the 45,000 loan applications. Visual analysis reveals patterns that statistics alone might miss - including the outliers that could bias our model.

**Transcript Cut Points:**
- **START at:** "So what about if I want to get some visualization and data"
- **END before:** "We have a lot of categorical variable. Let us a little bit clean the data"

---

### VIDEO #9 IO - Self-Paced - FUNAI - M1, V7 (Preprocessing for Machine Learning)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-06-preprocessing.mp4 |
| **Duration** | 6:43 |
| **Storyboard Location** | AI Systems module, Element 19 |
| **MLO Addressed** | MLO 4: Preprocess data using one-hot encoding and standardization |

**Video Title (for Panopto/LMS):**
Preprocessing for Machine Learning

**Video Description:**
Raw data can't go directly into a machine learning model. Professor Rahrovani demonstrates two essential preprocessing techniques: one-hot encoding (converting categorical variables like "yes/no" into 0s and 1s) and standardization (scaling numerical features so no single variable dominates). These choices shape what the model can learn.

**Transcript Cut Points:**
- **START at:** "We have a lot of categorical variable. Let us a little bit clean the data"
- **END before:** "Before we dive into developing the model, which is the beef"

---

### VIDEO #10 IO - Self-Paced - FUNAI - M1, V8 (Building and Evaluating the Model)

| Field | Value |
|-------|-------|
| **File Name** | m1-video-07-model-building.mp4 |
| **Duration** | 11:51 |
| **Storyboard Location** | AI Systems module, Element 23 |
| **MLO Addressed** | MLO 5: Build and evaluate a logistic regression model with 80/20 train-test split |

**Video Title (for Panopto/LMS):**
Building and Evaluating the Model

**Video Description:**
The culmination of the module: Professor Rahrovani builds a logistic regression model to predict loan approval. Learn how to split data into training (80%) and testing (20%) sets, train the model on historical patterns, and evaluate its accuracy on unseen data. The model achieves 89% accuracy - but what does that really mean, and whose predictions might be wrong?

**Transcript Cut Points:**
- **START at:** "Before we dive into developing the model, which is the beef"
- **END at:** "Okay, I'll stop here."

---

## Quick Reference Table

| Video | File Name | Duration | Element | MLO |
|-------|-----------|----------|---------|-----|
| #4 M1, V2 | m1-video-01-colab-intro.mp4 | 2:01 | 5 | MLO 1 |
| #5 M1, V3 | m1-video-02-load-data.mp4 | 3:01 | 7 | MLO 2 |
| #6 M1, V4 | m1-video-03-explore-data.mp4 | 4:21 | 9 | MLO 2 |
| #7 M1, V5 | m1-video-04-describe-data.mp4 | 4:42 | 13 | MLO 3 |
| #8 M1, V6 | m1-video-05-visualization.mp4 | 7:42 | 15 | MLO 3 |
| #9 M1, V7 | m1-video-06-preprocessing.mp4 | 6:43 | 19 | MLO 4 |
| #10 M1, V8 | m1-video-07-model-building.mp4 | 11:51 | 23 | MLO 5 |

**Total Duration:** ~40 minutes

---

## Storyboard Integration

Each video segment corresponds to a specific element in the M1-AI-Systems storyboard:

| Video | Watch Element | Followed By |
|-------|---------------|-------------|
| #4 | Element 5 | Element 6: Colab Practice (Do) |
| #5 | Element 7 | Element 8: Load Data Practice (Do) |
| #6 | Element 9 | Element 10: Explore Data Practice (Do) |
| #7 | Element 13 | Element 14: Data Types Practice (Do) |
| #8 | Element 15 | Element 16: Visualization Practice (Do) |
| #9 | Element 19 | Element 20: Preprocessing Practice (Do) |
| #10 | Element 23 | Element 24: Model Building Practice (Do) |

---

## Export Checklist

For each video segment:

- [ ] Set in-point at START transcript marker
- [ ] Set out-point at END transcript marker
- [ ] Export with naming convention: `m1-video-0X-[topic].mp4`
- [ ] Verify audio levels are consistent
- [ ] Check that no content is cut mid-sentence
- [ ] Upload to Panopto with Video Title
- [ ] Add Video Description to LMS element
- [ ] Generate/upload VTT captions

---

**Document Version:** 1.0
**Last Updated:** December 2024
**Course:** Fundamentals of AI for Business (FUNAI)
**Module:** M1 - AI Systems
