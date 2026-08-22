# Changelog

Versions are `major.minor.patch.build`. The same notes appear inside the app
under **Settings ▸ About**, and in the card GradeCore shows the first time it
runs after an update.

## v1.0.0.7

**GradeCore has its own icons now.**

- Forty-eight icons drawn for GradeCore replace the stock symbols across the
  app — the sidebar, the tabs inside a class, every report card, the settings
  pages, the dashboard and every empty page.
- A class now shows how it meets with an icon of its own: a classroom door for
  face-to-face, a camera for online, and both together for blended. They are
  clearest in the **Class Schedule** dialog, where the three sit side by side.
- Exports carry their own marks — a PDF file, an Excel sheet, a printer — and
  the exam paper's answer key has one too.
- The smallest places keep the plain symbols on purpose. A drawing at twelve
  pixels is a smudge, so timetable corners, chevrons and tick boxes are left as
  they were.

## v1.0.0.6

**Grades now answer to the college's own E-Class Record.**

- Every transmutation and every point grade was checked against the E-Class
  Record workbook — all 1070 of its cells and all 26 rows of its point table.
  The formula was already right: a grade is **(score ÷ total) × 50 + 50**, so
  35 out of 50 is 85.
- A point grade now reads the percentage as it is shown. A grade printed as
  92.00 used to be given the point for 91.
- **75 is a hard floor**, as the record has it: there is no point grade beneath
  it, so nothing can be marked passing with a 5.00 beside it. A class may still
  set a stricter mark of its own.
- The Gradebook reads the pass mark and the transmutation base from the class
  instead of assuming 75 and 50 — the passing tally, the class average and the
  row colours all follow the setup.
- The Gradebook sheet now fills the window instead of stopping short and leaving
  a slab of empty card beside it, and the class-average row sits under the
  columns it belongs to.
- Encoding a score reaches the **Assessments** list straight away. It used to
  keep showing "0/84" and no average until you left the page and came back.
- **New paper** inside the exam papers folder opens the form again.
- The grade distribution chart no longer stacks one label per student down its
  side.

## v1.0.0.5

**Write your midterm and final in GradeCore, then print the paper and its
answer key.**

- **Reports ▸ Exam Paper ▸ New** starts a paper from a Table of Specifications.
  Every number arrives knowing what it is for — the cognitive level, the content
  area and the competency you placed there — shown above the question as you
  write it, so the paper cannot drift from the blueprint it was approved
  against. A paper can also be written free-hand, with no blueprint.
- Multiple choice, true or false and fill in the blank, with a picture on a
  question or on any option.
- Paste a whole question from your Word file — the stem and its options together
  — and GradeCore offers to split it into the fields. An asterisk on an option
  marks it as the correct answer. Pasting a list into one option fills the
  options from there down.
- The keyboard does everything: **Enter** runs down the options and on to the
  next question, **Ctrl** and a number ticks the answer, **Ctrl+D** duplicates
  an item, **Backspace** on an empty option removes it. Every keystroke saves
  itself, and the header says so.
- The printed paper builds its own parts from the types you chose —
  **I. MULTIPLE CHOICE**, **II. TRUE OR FALSE**, **III. FILL IN THE BLANK** —
  each with directions of its own and a blank before every number for the
  student to write on. Rename any heading or rewrite its directions on the
  question that opens the part; leave them and the standard wording prints.
  Item numbers always stay where the blueprint placed them.
- The answer key is a separate PDF, laid out in the same parts, with a coverage
  summary of what the paper actually tested against what the blueprint planned.
- The paper and the key always print A4 portrait, whatever the printer was last
  set to.

## v1.0.0.4

**Your timetable now says where each class actually meets.**

- Every class on the weekly schedule is marked **Face-to-Face** or **Online** —
  an icon on the timetable block, the room or "Online" underneath it, and a full
  label in the list view, on class cards and in the workspace header. Classes
  recorded before this show as Face-to-Face until you edit the slot.
- Grade sheets can now be generated for one grading period on its own.
  **Reports ▸ Grade Sheet** has a Combined / Midterm / Final switch: a period
  sheet shows every component with its weight, the raw score and the total
  midterm or final grade to submit. Print, PDF and Excel all follow the switch.
- **Settings ▸ Help & Support**: report a bug, suggest an improvement or ask a
  question. GradeCore composes the mail — with your version and Windows build
  attached — and hands it to your own mail app. A copy goes to your clipboard
  every time, so nothing is lost if no mail app answers.
- **Buy me a coffee** — GCash, Maya, PayPal and MariBank, each with a copy
  button. Nothing in GradeCore is behind a payment and nothing ever will be.
- Adding a subject or opening a class with no semester set now offers to set up
  the school year and semester there and then, instead of letting you fill in a
  form that could not be saved.
- Two schedules that overlap are refused, whatever their mode — you cannot be in
  a room and online at the same hour. The clash is named, so you can see what
  you are colliding with.
- **Settings ▸ Security** can lock GradeCore after a stretch of inactivity —
  2 minutes to 2 hours — once a PIN or password is set.
- A section's name is now assembled from its programme, year and block rather
  than typed, so the same section can never be spelled two ways.
- Picking a section from the "+ Section" list works without typing first.
- In Academic Management, a programme's "Full Name" is now called
  **Description**.

## v1.0.0.3

**Groups now change on screen the moment you change them.**

- Deleting, adding or renaming a group updates the board straight away. The
  delete was always saving — the board simply kept showing the old groups until
  you left the page and came back.
- Swap two students between groups: press **⇄** on a student card and pick who
  they trade places with. Both groups keep their size.
- Deleting a group that still has members now asks first.
- The student count in the class header updates as soon as you enrol somebody.
- Attendance tallies in the meeting list update as soon as you take attendance.

## v1.0.0.2

**Your letterhead prints exactly what you type.**

- The school name and governing agency are no longer forced into capitals. Type
  "Baao Community College" and that is what prints; type it in capitals if that
  is what your forms use.
- The fix applies everywhere the letterhead appears — the six class reports, the
  grade slip, the Table of Specifications, and the live preview in
  **Settings ▸ School**.

## v1.0.0.1

**Grade slips for students, and updates from inside the app.**

- Print a one-page grade slip for any student — open a class, then
  **Students ▸ ⋮ ▸ Print grade slip**, or the receipt button in the performance
  panel.
- Three slip templates (Plain, Bordered, Formal) with an optional school seal
  watermark, chosen from a live preview.
- Every slip carries a control number and is filed in a register, so a printout
  a student brings back later can be traced.
- Slips include a "Received by" line for the student to sign, and state plainly
  that they are not an official Registrar record.
- **Settings ▸ About** can now check GitHub for a new version and install it for
  you.

## v1.0.0.0

**First release.**

- Classes, students, attendance, assessments, grades and groupings.
- Six printable reports plus Excel export, on your school letterhead.
- Table of Specifications generator with Bloom's Taxonomy allocation.
- Everything offline, in one local SQLite file.
