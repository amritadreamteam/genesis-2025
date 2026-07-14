# Genesis 2026 Tasks (Freshers Only)

*Theme: Spider-Man*

## Table of Contents
- [Genesis 2026 Tasks (Freshers Only)](#genesis-2026-tasks-freshers-only)
  - [Table of Contents](#table-of-contents)
  - [What is Genesis?](#what-is-genesis)
  - [Submission Guidelines](#submission-guidelines)
  - [Task List](#task-list)
  - [TASK 00: Web-Slinger Origin Story](#task-00-web-slinger-origin-story)
  - [TASK 01: Spider-Sense Training – Linux Basics](#task-01-spider-sense-training--linux-basics)
  - [TASK 02: The Web (Wide Web) – Git \& GitHub](#task-02-the-web-wide-web--git--github)
  - [TASK 03: Great Power, Great Responsibility – Terminal Web-Slinger](#task-03-great-power-great-responsibility--terminal-web-slinger)
  - [TASK 04: Spider-Sense – Debug the Villains](#task-04-spider-sense--debug-the-villains)
  - [TASK 05: Build Your Web-Shooter – Vanilla JS Gadget](#task-05-build-your-web-shooter--vanilla-js-gadget)
  - [TASK 06: Swing Through the City – CSS \& Animation](#task-06-swing-through-the-city--css--animation)
  - [A Note on AI Usage](#a-note-on-ai-usage)
  - [References \& Acknowledgments](#references--acknowledgments)

## What is Genesis?

Genesis is the entry point into the Dream Team — a student-led community dedicated to transforming interested and ambitious students into problem solvers and leading professionals of tomorrow. These tasks are designed to be an introductory phase: approachable, low-stakes, and paced so you can build real momentum instead of getting overwhelmed on day one.

No prior experience is assumed. Take it slow, ask for help when you're stuck, and focus on understanding over just finishing.

## Submission Guidelines

1. **Set up a private GitHub repository named `genesis-2026-tasks`.**

2. **Create directories named `task-##`** (where `##` corresponds to the task number). All work, files, screenshots, code, and deliverables for each task **must be placed inside the correct corresponding directory**.

3. **Add a `README.md` file inside each task folder** with a brief explanation of your approach, along with a short personal reflection on the task.

## Task List

| Task No. | Task Name                                                              |
|----------|-------------------------------------------------------------------------|
| 00       | [Web-Slinger Origin Story](#task-00-web-slinger-origin-story)           |
| 01       | [Spider-Sense Training – Linux Basics](#task-01-spider-sense-training--linux-basics) |
| 02       | [The Web (Wide Web) – Git & GitHub](#task-02-the-web-wide-web--git--github) |
| 03       | [Great Power, Great Responsibility – Terminal Web-Slinger](#task-03-great-power-great-responsibility--terminal-web-slinger) |
| 04       | [Spider-Sense – Debug the Villains](#task-04-spider-sense--debug-the-villains) |
| 05       | [Build Your Web-Shooter – Vanilla JS Gadget](#task-05-build-your-web-shooter--vanilla-js-gadget) |
| 06       | [Swing Through the City – CSS & Animation](#task-06-swing-through-the-city--css--animation) |

## TASK 00: Web-Slinger Origin Story

Every hero has an origin story. Before diving into code, let's get you set up and introduced to the community.

**Objectives:**

- Star and follow the relevant club repositories.
- Follow the required GitHub pages/accounts.
- Shoot a short self-introduction video (who you are, why you're here).
- Create a small dummy pull request to your own repo to get comfortable with the PR workflow.

**Recommended Duration: 1 day**

## TASK 01: Spider-Sense Training – Linux Basics

Peter didn't master his powers overnight — and neither will you master the command line. This task is your training montage: basic navigation, file permissions, and getting comfortable typing instead of clicking.

**Objectives:**

- Set up Linux (Ubuntu 24.04 LTS recommended) or macOS with Homebrew as your package manager. Windows is not allowed.
- Get comfortable with basic navigation, file operations, and permissions (`ls`, `cd`, `cp`, `mv`, `chmod`, `mkdir`, etc.).
- Attach a screenshot of your desktop (Linux or macOS) to confirm your environment.

**Recommended Duration: 2 days**

## TASK 02: The Web (Wide Web) – Git & GitHub

Peter's web isn't just for swinging — it's for connecting everything together. Git is your web-shooter for code: version control, branching, and collaboration.

**Objectives:**

- Complete [Bandit](https://overthewire.org/wargames/bandit/) up to **Level 10**.
- Complete the core challenges on [Git Exercises](https://gitexercises.fracz.com/) and upload a screenshot of the completion page.
- Use [Learn Git Branching](https://learngitbranching.js.org/) to practice branching, merging, and rebasing.
- Write a short reflection in your task README covering what you learned, common mistakes, and useful commands. (No blog post required this year — keep it brief and honest.)

**Resources:**

- [Git Documentation](https://git-scm.com/docs)
- `man git`

**Recommended Duration: 3 days**

## TASK 03: Great Power, Great Responsibility – Terminal Web-Slinger

A CLI story-game where you play as Spider-Man, working through a branching storyline entirely from the terminal. Each "chapter" is solved using a real command-line skill — think finding the Green Goblin's hideout by grepping through a log file, decoding a villain's cipher with a bit of text processing, unlocking a vault with `chmod`, or "webbing up" an enemy using piping and redirection.

**Objectives:**

- Play through the terminal game provided by the mentors (link to be shared separately).
- Complete each chapter/puzzle to progress the storyline.
- Submit a screenshot of your completion/final chapter.
- Write a short reflection noting which puzzle taught you what CLI skill, and which one you found trickiest.

**Recommended Duration: 3 days**

## TASK 04: Spider-Sense – Debug the Villains

Spider-sense doesn't write bug-free code — it catches bugs before they cause real damage. You'll be given a small, pre-built vanilla JavaScript app riddled with intentional bugs, each named after a villain.

**Objectives:**

- Clone the provided buggy app.
- Find and fix each bug (e.g., an off-by-one error nicknamed "The Vulture," an async/race-condition bug nicknamed "Mysterio," a null/undefined bug nicknamed "Venom," etc.).
- For each bug fixed, write a short note: what the bug was, how you found it, and how you fixed it.
- Ensure the app works correctly end-to-end after all fixes.

**Recommended Duration: 3 days**

## TASK 05: Build Your Web-Shooter – Vanilla JS Gadget

Time to build your own gadget. Pick **one** of the following, and build it using **plain HTML, CSS, and JavaScript only** — no frameworks, no libraries. Static or local data only.

**Problem Statements (pick one):**

1. **Daily Patrol Tracker** – Mark daily "patrols" (habits) complete, track streaks (current/longest), and show basic stats like success rate or missed days.
2. **Web-Shooter Formula Lab** – Combine a list of "chemical" ingredients to generate possible web-fluid formulas/recipes.
3. **Oscorp Files** – A searchable, filterable local dataset/list (e.g., search by name, category, or date).

**Objectives:**

- Build using real DOM manipulation, event handling, and `localStorage` for persistence — no frameworks.
- Handle empty/edge cases gracefully (e.g., no data yet, invalid input).
- Keep your code readable and reasonably organized across files (`index.html`, `style.css`, `script.js`, etc.).
- Maintain a short list of any hardcoded/sample data you used.

**Recommended Duration: 5 days**

## TASK 06: Swing Through the City – CSS & Animation

Functionality gets you through the day, but style is what makes swinging through the city feel effortless. This task is about visual polish — bringing a page to life with animation.

**Objectives:**

- Build a small interactive, animated page using pure CSS/JS — for example, a parallax scrolling section, CSS transitions/keyframe animations, or a simple canvas/SVG animation (e.g., a small "swinging between buildings" effect).
- Focus on smoothness and visual feel over complexity — a small, well-polished animation beats an ambitious, janky one.
- Include a brief note on what techniques you used (transitions, keyframes, canvas, SVG, etc.) and what you'd improve with more time.

**Recommended Duration: 3 days**

## A Note on AI Usage

You may use AI tools to explain concepts, help you debug, or clarify documentation — not to generate full solutions for you. For each task, include a short note on where (if at all) you used AI and why. Submissions that appear to be AI-generated without genuine understanding or experimentation will be rejected. We'd rather see an honest, imperfect attempt than a polished copy-paste.

## References & Acknowledgments

This task list builds on the structure and spirit of previous years' Dream Team recruitment tasks, restructured for a gentler on-ramp and themed around Spider-Man for 2026.
