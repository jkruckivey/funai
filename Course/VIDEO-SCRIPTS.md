# Video Scripts - Fundamentals of AI for Business

**Course:** Fundamentals of AI for Business
**Instructor:** Professor Yasser Rahrovani, Ivey Business School
**Created:** 2025-12-26

---

## VIDEO 1: Course Welcome
**File Name:** `module-0-welcome-rahrovani.mp4`
**Duration:** 3 minutes
**Location:** Module 0 (Bridge-In), Element 1

### SCRIPT:

```
[OPEN: Professor Rahrovani at desk or standing, casual professional setting]

Welcome to Fundamentals of AI for Business. I'm Yasser Rahrovani, Associate Professor at Ivey Business School, where my research focuses on how AI systems become embedded in organizations—and what happens when they go wrong.

[BEAT]

Here's a question I want you to sit with: When an algorithm denies someone a loan, or flags a resume for rejection, or recommends a prison sentence—who's responsible? The data scientist who built it? The manager who deployed it? The executive who approved it?

The honest answer? All of them. And increasingly, that includes you.

[TRANSITION]

AI isn't coming to business—it's already here. Right now, algorithms are making decisions about hiring, lending, pricing, and operations in virtually every industry. As a business leader, you'll either shape how these systems are deployed, or you'll be shaped by decisions you don't understand.

This course exists to change that.

[BEAT]

Over the next ten hours, you're going to do something most MBA programs never offer: you're going to build an actual machine learning model. Not watch someone else do it—build it yourself, in Google Colab, with real code and real data.

You'll load a dataset of 45,000 loan applications. You'll clean the data, handle outliers, preprocess features, split your data into training and test sets, and train a logistic regression model that predicts loan approval with 89% accuracy.

And then—and this is the important part—you'll ask: what did that model actually learn? Whose patterns did it replicate? What biases might be hiding in that 89% accuracy?

[TRANSITION]

That's why we'll spend significant time on the COMPAS case study—a real algorithm used in American courtrooms to predict whether defendants would commit future crimes. ProPublica's investigation found it was twice as likely to falsely label Black defendants as high-risk. Northpointe, the company that built it, disagreed. Both sides had data to support their claims.

How is that possible? You'll find out. And more importantly, you'll learn why "fairness" in AI isn't a technical problem with a technical solution—it's a values problem that requires business judgment.

[BEAT]

Here's what you'll accomplish in this course:

Module 1: You'll build your first ML model from scratch in Google Colab.

Module 2: You'll master the three types of machine learning—supervised, unsupervised, and reinforcement—and know when each applies.

Module 3: You'll analyze the COMPAS case and identify nine different types of bias that can emerge in ML systems.

Module 4: You'll explore how AI transforms work, creativity, and the automation-versus-augmentation decision every organization faces.

Module 5: You'll study implementation challenges through real cases—why AI projects fail, and what governance structures help them succeed.

Module 6: You'll learn to recognize AI snake oil—the overpromised, underdelivered AI applications that waste resources and create risk.

[CLOSING]

By the end, you won't just understand AI conceptually. You'll have felt the weight of decisions data scientists make every day—which features to include, how to handle missing data, what "good enough" accuracy means.

That hands-on experience will make you a better questioner, a better decision-maker, and a more responsible leader in an AI-powered world.

I'm genuinely excited to guide this journey.

Let's begin.

[END]
```

**On-Screen Text Suggestions:**
- 0:15 - "Professor Yasser Rahrovani | Associate Professor, Ivey Business School"
- 1:45 - "45,000 loan applications | Real data, real code"
- 2:20 - "COMPAS Algorithm | ProPublica Investigation"

**B-Roll Suggestions:**
- Brief clips of Google Colab interface
- COMPAS news headlines (with permission)
- Data visualization graphics

---

## VIDEO 2: Course Conclusion
**File Name:** `module-6-conclusion-rahrovani.mp4`
**Duration:** 2-3 minutes
**Location:** Module 6 (AI Harms & Snake Oil), Final Element

### SCRIPT:

```
[OPEN: Professor Rahrovani, same setting as welcome video]

You made it.

Ten hours ago, you started this course as someone who used AI. Now, you've built AI. You've trained a model, evaluated its predictions, and—most importantly—questioned what those predictions really mean.

[BEAT]

Let's reflect on what you've accomplished.

You loaded 45,000 loan applications into Google Colab and explored the data like a data scientist would. You found outliers—a 140-year-old loan applicant, someone with 125,000 years of work experience—and made decisions about how to handle them.

You learned that preprocessing isn't just technical housekeeping. It's where assumptions get baked in. One-hot encoding. Standardization. Train-test splits. Each choice shapes what the model can learn.

You built a logistic regression model and achieved 89% accuracy. And then you asked the harder question: accurate according to whom? Accurate at what cost?

[TRANSITION]

The COMPAS case showed you that fairness isn't a checkbox. It's a contested value. ProPublica and Northpointe looked at the same algorithm and reached opposite conclusions—because they measured fairness differently.

That's not a failure of analysis. That's the nature of the problem.

In Module 4, you explored how AI changes work—not just replacing tasks, but restructuring roles, relationships, and expertise. You learned the difference between automation and augmentation, and why the choice between them is a strategic decision, not a technical inevitability.

Module 5 showed you why AI projects fail. Not because the algorithms don't work, but because organizations aren't ready—governance gaps, misaligned incentives, insufficient change management.

And in Module 6, you learned to recognize AI snake oil. The overpromised emotion detection. The predictive policing that reinforces existing biases. The hiring algorithms that discriminate while claiming objectivity.

[BEAT]

Here's what I hope you take forward:

First: AI systems are organizational systems. They don't operate in isolation. They inherit the biases of their data, the assumptions of their designers, and the incentives of their deployers.

Second: There is no neutral. Every dataset reflects choices. Every feature selection privileges some patterns over others. Every accuracy metric hides trade-offs. Your job as a business leader is to surface those trade-offs and make them visible.

Third: The questions matter more than the answers. When someone presents you with an AI solution, you now know what to ask: What data trained this? Who labeled it? How was fairness defined? What happens when it's wrong? Who bears the consequences?

[CLOSING]

You started this course to understand AI. You're leaving with something more valuable: the judgment to deploy it responsibly.

AI will continue reshaping business, society, and human decision-making. How it reshapes them depends on leaders like you—leaders who understand not just what AI can do, but what it should do.

Thank you for taking this journey. I hope you'll carry these questions into every AI decision you face.

[END]
```

**On-Screen Text Suggestions:**
- 0:30 - "45,000 loan applications | 89% accuracy"
- 1:15 - "COMPAS: Same algorithm, different conclusions"
- 2:15 - "Three Takeaways" (as listed)

---

## VIDEO 3: Google Colab Setup Guide (Optional)
**File Name:** `module-1-colab-setup.mp4`
**Duration:** 2 minutes
**Location:** Module 1 (AI Systems), Before Element 5

### SCRIPT:

```
[SCREEN RECORDING: Browser open to Google]

Before we start building our machine learning model, let's make sure you can access Google Colab.

[NAVIGATE TO: colab.research.google.com]

Go to colab.research.google.com. If you have a Google account, you can sign in here. If you're using an institutional account that doesn't have Colab access, you may need to use a personal Gmail account.

[CLICK: New Notebook]

Click "New Notebook" to create a fresh workspace. This is where we'll write and run our Python code.

[POINT TO INTERFACE ELEMENTS]

Let me orient you to the interface:

This is a code cell. You write Python code here and run it by clicking the play button—or pressing Shift+Enter.

[TYPE: print("Hello, AI!")]
[RUN CELL]

See? The output appears right below the cell.

[POINT TO: + Code button]

You can add new code cells with this button—or by pressing Ctrl+M then B.

[POINT TO: Runtime menu]

If things ever get stuck, go to Runtime and click "Restart runtime." This clears everything and lets you start fresh.

[POINT TO: File menu]

Your notebooks save automatically to your Google Drive. You can also download them as .ipynb files or .py scripts.

[TRANSITION]

One more important thing: Colab runs on Google's servers, not your computer. That means you get access to powerful hardware—including GPUs for machine learning—without installing anything.

The trade-off? If you're inactive for a while, your session will disconnect and you'll need to re-run your code cells. So save your work periodically, and don't worry if you see a "reconnecting" message.

[CLOSING]

That's all you need to know to get started. In the next video, we'll load our loan dataset and begin exploring the data.

[END]
```

---

## PRODUCTION NOTES

### Recording Setup
- **Background:** Clean, professional (office, neutral backdrop)
- **Lighting:** Soft, even lighting on face
- **Audio:** Lapel mic or quality USB mic, minimal room echo
- **Framing:** Medium shot (chest up), slight off-center
- **Eye line:** Direct to camera for welcome/conclusion; can look at notes occasionally

### Screen Recording (Colab Setup)
- **Resolution:** 1920x1080 minimum
- **Font size:** Increase Colab font size for readability
- **Mouse:** Highlight clicks, smooth movements
- **Zoom:** Use browser zoom (125-150%) for better visibility

### Accessibility Requirements
- VTT caption files for all videos
- Full transcript available below each video
- Captions synchronized within 1 second of speech
- Color contrast 4.5:1 for any text overlays

### File Naming Convention
- `module-{N}-{descriptive-name}.mp4`
- `module-{N}-{descriptive-name}.vtt` (captions)
- Example: `module-0-welcome-rahrovani.mp4`

---

## SUMMARY

| Video | Duration | Location | Status |
|-------|----------|----------|--------|
| 1. Course Welcome | 3 min | M0, Element 1 | Script complete |
| 2. Course Conclusion | 2-3 min | M6, Final | Script complete |
| 3. Colab Setup Guide | 2 min | M1, Before Element 5 | Script complete (optional) |
| 4-10. Content Segments | 40 min total | M1, Elements 5-26 | Existing video (needs cuts) |

**Total new recording time needed:** ~7-8 minutes
**Total content video time:** ~40 minutes (from existing recording)
