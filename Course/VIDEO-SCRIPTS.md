# Video Scripts - Fundamentals of AI for Business

**Course:** Fundamentals of AI for Business
**Instructor:** Professor Yasser Rahrovani, Ivey Business School
**Created:** 2025-12-26

---

## VIDEO 1: Course Welcome
**File Name:** `module-0-welcome-rahrovani.mp4`
**Duration:** 3 minutes 30 seconds
**Location:** Module 0 (Bridge-In), Element 1

**Video Upload Instructions:**
- **Video Title:** Welcome to Fundamentals of AI for Business
- **VTT Transcript:** Upload corresponding .vtt file for captions

**Accessibility Attributes:**
- Captions enabled (VTT file)
- Transcript available below video
- Keyboard controls (space to play/pause, arrow keys for seek)

**Video Description Text (display below video):**
Professor Yasser Rahrovani welcomes you to the course and explains why business leaders need deep AI literacy. Preview the hands-on learning journey ahead, from building your first ML model to analyzing algorithmic bias in real-world systems.

---

### VIDEO SCRIPT

**[0:00 - 0:15] OPENING**

*[Visual: Professor Rahrovani on screen, professional office/classroom setting]*

Hi, I'm Yasser Rahrovani, Associate Professor at Ivey Business School. Welcome to Fundamentals of AI for Business.

My research focuses on how AI systems become embedded in organizations—and what happens when they go wrong.

**[0:15 - 0:35] THE ACCOUNTABILITY QUESTION**

*[Visual: Rahrovani on screen, engaged and direct]*

Here's a question I want you to sit with: When an algorithm denies someone a loan, flags a resume for rejection, or recommends a prison sentence—who's responsible?

The data scientist who built it? The manager who deployed it? The executive who approved it?

The honest answer? All of them. And increasingly, that includes you.

**[0:35 - 0:55] WHY THIS MATTERS NOW**

*[Visual: On-screen text - "AI is already reshaping decisions in every industry"]*

AI isn't coming to business—it's already here. Right now, algorithms are making decisions about hiring, lending, pricing, and operations in virtually every industry.

As a business leader, you'll either shape how these systems are deployed, or you'll be shaped by decisions you don't understand.

This course exists to change that.

**[0:55 - 1:25] WHAT MAKES THIS COURSE DIFFERENT**

*[Visual: Google Colab interface screenshot, loan dataset preview]*

Over the next ten hours, you're going to do something most MBA programs never offer: you're going to build an actual machine learning model.

Not watch someone else do it—build it yourself, in Google Colab, with real code and real data.

You'll load a dataset of 45,000 loan applications. You'll clean the data, handle outliers, preprocess features, split into training and test sets, and train a model that predicts loan approval with 89% accuracy.

**[1:25 - 1:45] THE CRITICAL QUESTION**

*[Visual: Rahrovani on screen, leaning in]*

And then—this is the important part—you'll ask: what did that model actually learn? Whose patterns did it replicate? What biases might be hiding in that 89% accuracy?

**[1:45 - 2:10] THE COMPAS CASE**

*[Visual: On-screen text - "COMPAS Algorithm | ProPublica Investigation"]*

That's why we'll spend significant time on the COMPAS case study—a real algorithm used in American courtrooms to predict whether defendants would commit future crimes.

ProPublica's investigation found it was twice as likely to falsely label Black defendants as high-risk. Northpointe, the company that built it, disagreed. Both sides had data to support their claims.

How is that possible? You'll find out.

**[2:10 - 2:55] COURSE ROADMAP**

*[Visual: Course roadmap graphic showing 6 modules]*

Here's what you'll accomplish:

**Module 1:** Build your first ML model from scratch in Google Colab.

**Module 2:** Master supervised, unsupervised, and reinforcement learning—and know when each applies.

**Module 3:** Analyze the COMPAS case and identify nine types of bias in ML systems.

**Module 4:** Explore how AI transforms work and the automation-versus-augmentation decision.

**Module 5:** Study implementation challenges—why AI projects fail, and what governance helps them succeed.

**Module 6:** Learn to recognize AI snake oil—overpromised applications that waste resources and create risk.

**[2:55 - 3:20] WHY HANDS-ON MATTERS**

*[Visual: Rahrovani on screen]*

By the end, you won't just understand AI conceptually. You'll have felt the weight of decisions data scientists make every day—which features to include, how to handle missing data, what "good enough" accuracy means.

That hands-on experience will make you a better questioner, a better decision-maker, and a more responsible leader in an AI-powered world.

**[3:20 - 3:30] CLOSING**

*[Visual: Rahrovani on screen, warm and engaged]*

I'm genuinely excited to guide this journey.

Let's begin.

**[END]**

---

### GRAPHICS REQUIRED

| Timestamp | Visual Element | Description |
|-----------|---------------|-------------|
| 0:00-0:15 | Lower third | "Professor Yasser Rahrovani | Associate Professor, Ivey Business School" |
| 0:35-0:55 | On-screen text | "AI is already reshaping decisions in every industry" |
| 0:55-1:25 | B-roll/screenshot | Google Colab interface, loan dataset preview |
| 1:45-2:10 | On-screen text | "COMPAS Algorithm | ProPublica Investigation" |
| 2:10-2:55 | Graphic | Course roadmap showing 6 modules with icons |

---

### VTT TRANSCRIPT

```vtt
WEBVTT

00:00:00.000 --> 00:00:04.500
Hi, I'm Yasser Rahrovani, Associate Professor at Ivey Business School.

00:00:04.500 --> 00:00:07.000
Welcome to Fundamentals of AI for Business.

00:00:07.500 --> 00:00:12.500
My research focuses on how AI systems become embedded in organizations—

00:00:12.500 --> 00:00:15.000
and what happens when they go wrong.

00:00:15.500 --> 00:00:18.500
Here's a question I want you to sit with:

00:00:18.500 --> 00:00:22.000
When an algorithm denies someone a loan,

00:00:22.000 --> 00:00:24.500
flags a resume for rejection,

00:00:24.500 --> 00:00:27.500
or recommends a prison sentence—who's responsible?

00:00:28.000 --> 00:00:30.000
The data scientist who built it?

00:00:30.000 --> 00:00:32.000
The manager who deployed it?

00:00:32.000 --> 00:00:34.000
The executive who approved it?

00:00:34.500 --> 00:00:36.500
The honest answer? All of them.

00:00:36.500 --> 00:00:39.000
And increasingly, that includes you.

00:00:40.000 --> 00:00:43.000
AI isn't coming to business—it's already here.

00:00:43.500 --> 00:00:48.000
Right now, algorithms are making decisions about hiring, lending,

00:00:48.000 --> 00:00:51.000
pricing, and operations in virtually every industry.

00:00:51.500 --> 00:00:54.500
As a business leader, you'll either shape how these systems are deployed,

00:00:54.500 --> 00:00:57.500
or you'll be shaped by decisions you don't understand.

00:00:58.000 --> 00:01:00.000
This course exists to change that.

00:01:01.000 --> 00:01:05.000
Over the next ten hours, you're going to do something most MBA programs never offer:

00:01:05.500 --> 00:01:08.500
you're going to build an actual machine learning model.

00:01:09.000 --> 00:01:13.000
Not watch someone else do it—build it yourself, in Google Colab,

00:01:13.000 --> 00:01:15.000
with real code and real data.

00:01:15.500 --> 00:01:19.000
You'll load a dataset of 45,000 loan applications.

00:01:19.500 --> 00:01:23.000
You'll clean the data, handle outliers, preprocess features,

00:01:23.000 --> 00:01:25.500
split into training and test sets,

00:01:25.500 --> 00:01:29.500
and train a model that predicts loan approval with 89% accuracy.

00:01:30.500 --> 00:01:33.500
And then—this is the important part—

00:01:33.500 --> 00:01:36.500
you'll ask: what did that model actually learn?

00:01:37.000 --> 00:01:39.000
Whose patterns did it replicate?

00:01:39.500 --> 00:01:43.000
What biases might be hiding in that 89% accuracy?

00:01:44.000 --> 00:01:47.500
That's why we'll spend significant time on the COMPAS case study—

00:01:48.000 --> 00:01:53.000
a real algorithm used in American courtrooms to predict whether defendants would commit future crimes.

00:01:53.500 --> 00:01:58.500
ProPublica's investigation found it was twice as likely to falsely label Black defendants as high-risk.

00:01:59.000 --> 00:02:02.000
Northpointe, the company that built it, disagreed.

00:02:02.500 --> 00:02:05.000
Both sides had data to support their claims.

00:02:05.500 --> 00:02:08.000
How is that possible? You'll find out.

00:02:09.000 --> 00:02:11.000
Here's what you'll accomplish:

00:02:11.500 --> 00:02:16.000
Module 1: Build your first ML model from scratch in Google Colab.

00:02:16.500 --> 00:02:22.000
Module 2: Master supervised, unsupervised, and reinforcement learning—and know when each applies.

00:02:22.500 --> 00:02:27.500
Module 3: Analyze the COMPAS case and identify nine types of bias in ML systems.

00:02:28.000 --> 00:02:33.000
Module 4: Explore how AI transforms work and the automation-versus-augmentation decision.

00:02:33.500 --> 00:02:39.000
Module 5: Study implementation challenges—why AI projects fail, and what governance helps them succeed.

00:02:39.500 --> 00:02:44.500
Module 6: Learn to recognize AI snake oil—overpromised applications that waste resources and create risk.

00:02:45.500 --> 00:02:49.000
By the end, you won't just understand AI conceptually.

00:02:49.500 --> 00:02:53.000
You'll have felt the weight of decisions data scientists make every day—

00:02:53.500 --> 00:02:56.500
which features to include, how to handle missing data,

00:02:56.500 --> 00:02:59.000
what "good enough" accuracy means.

00:02:59.500 --> 00:03:04.000
That hands-on experience will make you a better questioner, a better decision-maker,

00:03:04.000 --> 00:03:07.500
and a more responsible leader in an AI-powered world.

00:03:08.500 --> 00:03:11.500
I'm genuinely excited to guide this journey.

00:03:12.000 --> 00:03:14.000
Let's begin.
```

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
