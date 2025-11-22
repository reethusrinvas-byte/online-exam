# NeonExam

NeonExam is a single-page web app (HTML + CSS + JS) that lets you **create, take, and review exams** in the browser – no backend required.

---

## Features

- **Admin Panel**
  - Create an exam: title, subject, duration (minutes), passing %
  - Add questions:
    - MCQ (4 options + correct answer)
    - True / False
  - Custom points per question
  - Live question count and preview

- **Student Panel**
  - See exam title, subject, total questions, duration
  - Start exam only when questions exist
  - Question navigation: **Previous / Next**
  - **Mark for review** toggle
  - **Question palette** with states:
    - Current
    - Answered
    - Marked for review

- **Timer & Auto Submit**
  - Countdown based on exam duration
  - Auto-submits when time is over

- **Results & Review**
  - Score, total points, percentage, pass/fail
  - Uses array methods (`map`, `filter`, `reduce`) for scoring
  - Detailed review: your answer vs correct answer
  - **Retake exam** resets answers, marks, and timer

---

## Project Structure

```text
index.html
style.css
script.js   // the NeonExam logic (IIFE)
