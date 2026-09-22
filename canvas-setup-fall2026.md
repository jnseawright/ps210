# PS 210 Canvas Setup — Fall 2026

Built from syllabus.Rmd and a scan of the repo's Homework/ files. Two items need a decision from you before I (or anyone) can finish the mechanical work — flagged below.

## 🔴 Needs your decision first

### HW2 due date conflict
`Homework/hw2.Rmd` states the due date as **Friday, November 7, 2026** (in the YAML header, the top banner, and the footer — consistent within the file itself). `syllabus.Rmd` states **Tuesday, November 10, 2026** in both the Key Dates list and the course schedule table. These are two different dates, not a rounding issue. Whichever is correct needs to be fixed in the other document, and then set as the due date on the Canvas assignment.

### Research-participation opt-out deadline
`syllabus.Rmd` still has a literal placeholder: "To select the paper option, email the instructor by **[date]**." Students can't act on this as written — it needs a real date before the syllabus goes out, and that date is also worth setting as a Canvas Announcement/reminder.

## 🟡 Canvas shell setup (once the Fall 2026 course shell exists)

- **Fix hardcoded Canvas links.** `course-audit-fall2026.md` already flagged this: several files link directly to last year's course (ID `235934`):
  - `Homework/Midterm.Rmd` / `Midterm.html` — line ~45, points to `.../courses/235934/assignments/1660082`
  - `Homework/Final.Rmd` / `Final.html` — line ~45, points to `.../courses/235934/assignments/1678450`
  - `Homework/hw1 rubric.Rmd` / `hw1-rubric.html`, `Homework/hw2old.Rmd` — same pattern
  - Per your note, `Midterm.Rmd`/`Final.Rmd` are the old take-home versions being retired in favor of in-class exams + a study guide, so these two specifically may just need archiving rather than a link fix — your call once the study guides exist.
  - `hw1.Rmd`, `hw2.Rmd`, `hw3.Rmd` (the current ones) don't hardcode a link — they just say "submit on Canvas" — so no fix needed there, just make sure the Fall 2026 assignment shells exist for students to find.

- **Gradebook assignment groups**, matching the syllabus's grading breakdown:
  - Participation — 10% total
    - Reading Check-Ins — 4% (in-class quizzes; syllabus says drop the two lowest — set this as a "drop lowest 2" rule if the check-ins are entered as individual Canvas quiz grades)
    - Muddiest Point Posts — 3% (weekly, due Wednesdays 9:00 PM — see below)
    - Engagement — 3% (manually graded; a simple gradebook column, no separate Canvas activity needed)
  - Homework — 30% total across 3 assignments (the syllabus doesn't say whether they're weighted equally within that 30% — worth deciding explicitly rather than leaving Canvas's default)
  - Midterm — 30%
  - Final — 30%
  - Late-work rule: 5% per day. Canvas assignments can apply this automatically per-assignment, or you can track it manually — worth deciding once, since it applies to all three homeworks.

- **Weekly "Muddiest Point" Posts.** The syllabus says "post one sentence on Canvas" but doesn't specify the mechanism. Two common setups:
  - A single recurring Discussion where each student posts weekly (easy to grade in one place, but 10 weeks of threads pile up)
  - A weekly-recurring low-point Assignment (cleaner gradebook column per week, more setup up front)
  Either works; you'll want to pick one and build the first one as a template to duplicate.

- **Reading Check-In quizzes.** Since these happen "at the start of several classes," they need to exist and be time-windowed (e.g., available only during the first 5–10 minutes of class) — worth deciding which specific class days get one, since the syllabus says "several" rather than listing them explicitly.

- **In-class Midterm and Final.** Both are now in-class (open notes, closed devices for the final) rather than the old online take-home format. If you don't need a Canvas component for them at all (e.g., paper exams), the main Canvas task is just posting the study guide as an Announcement or Page when the time comes, and entering grades manually. If you *do* want a Canvas quiz taken in-class on laptops, that's a different setup (timed quiz, lockdown considerations) — worth deciding given "closed devices" is the final's policy.

## 🟢 Lower priority

- Course-audit's other open items (learning objectives on lecture decks, image alt-text on `ethics.Rmd`) aren't Canvas-specific, but worth keeping on your radar before the term starts — see `course-audit-fall2026.md`.
