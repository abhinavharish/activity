# StudyPrep — ISE Exam Study Planner

A browser-based last-minute exam preparation planner for Information Science and Engineering students. Enter your subject, days until the exam, syllabus topics, available daily study time, and materials. The planner creates the requested day-by-day outline and prioritizes previous year questions (PYQs), then targeted notes review and practice, with time reserved for revision and a mock test.

## Run in VS Code

1. Open the `study-prep` folder in VS Code.
2. Open `index.html` in a browser, or install the **Live Server** extension and choose **Go Live**.
3. Try: `I have a Python exam in 10 days. Topics: process scheduling, threads, paging, memory management, and disk scheduling. I can study 5 hours a day. I have notes and VTU past questions.`

The project needs no build tools or package installation. Plans are stored in browser local storage. Document search reads uploaded `.txt`, `.md`, and `.csv` files locally; the calculator supports basic arithmetic; the calendar marks your study window and exam day. The chatbot uses built-in browser rules, not a connected AI service, so review its suggestions against your syllabus and faculty guidance.

## Files

- `index.html` — page structure
- `css/styles.css` — layout and styling
- `js/app.js` — plan generation, document search, calculator, calendar, and chat

