# StudyTrack — Student Planner

StudyTrack is a single-page study planner for students. It keeps assignments, lab reports, exams and projects in one place, groups them by course, and shows what to do first. It runs entirely in the browser: there is no server, no account and no login, and all data is saved in the browser's `localStorage`.

**Purpose:** help students stay on top of deadlines across several courses, decide what to prioritise, and track how much time they actually spend studying.

## Features

- **Dashboard:** stat cards (total, pending, completed, due soon, overdue), overall progress bar, a due-today/overdue banner, and a "What to prioritise" list (overdue first, then high priority, then the closest deadline).
- **Calendar:** a 7-day week view and a full month view. Click any day to add a task for that date.
- **Tasks:** add, edit, delete (with Undo), and complete tasks. Each task has a title, course, deadline, priority, type and optional estimated hours. Search and filter by course and priority.
- **Courses:** add, rename and remove courses, give each one a color, and see its next task and total focus time.
- **Focus timer:** 25 minute focus / 5 minute break timer. Time is logged per course when you pause, reset, skip or finish, and the card shows time focused today and in the last 7 days.
- **Extras:** streak of completed tasks, hours of work due this week, keyboard shortcuts (`N` new task, `/` search), dark mode that follows the system setting, responsive layout for phones.
