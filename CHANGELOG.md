# Changelog

Versions are `major.minor.patch.build`. The same notes appear inside the app
under **Settings ▸ About**, and in the card GradeCore shows the first time it
runs after an update.

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
