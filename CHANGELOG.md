# Changelog

Versions are `major.minor.patch.build`. The same notes appear inside the app
under **Settings ▸ About**, and in the card GradeCore shows the first time it
runs after an update.

## v1.0.0.19

**A Table of Specifications can use all six Bloom's levels.**

- **Evaluating** and **Creating** are available now, and each paper chooses
  which levels it is built on — the **levels** button beside Presets. Papers
  already written keep the four they were written with, so nothing finalized
  changes.
- The matrix grows with the choice: the wizard, the totals, and the printed
  page, where the columns narrow so six still fit.
- The per-topic grid has column headings at last. Four identical number boxes
  with nothing above them gave no way of telling which one was Remembering.

## v1.0.0.18

**Report a bug without leaving GradeCore.**

- **Help & Support** can now send your message straight out, instead of handing
  it to a mail app and hoping one answers. It goes from your own account — the
  one set up under **Settings ▸ Email** — so a reply comes back to you rather
  than disappearing into a mailbox you cannot see.
- Opening your mail app and copying to the clipboard both still work, so
  nothing is lost if you have not set up email.

## v1.0.0.17

**Grade slips can be emailed, and the class can see who is top of it.**

- Email a student their grade slip from the slip itself, or send a whole class
  from **Reports**. Each student receives only their own, attached as a PDF,
  and nothing goes out until you say so.
- Set it up under **Settings ▸ Email** — Gmail, Brevo, or your own mail server.
  Each keeps its own sign-in, so setting one up never disturbs another, and
  **Test connection** signs in without sending anything, so a wrong App
  Password is found there rather than halfway through a class.
- A student with no address, an unusable one, or one shared with somebody else
  is never quietly skipped: the Students page counts them, and a bulk send
  names every one before it starts.
- Every attempt is kept, successes and failures alike, with the address it
  actually went to.
- New **Top Performers** tab inside a class: everyone whose grade lands between
  **1.00 and 1.90**, however many that is, with the three highest marks on a
  podium and the list downloadable as a PDF on your letterhead. Early in a
  term, when only a handful of scores are in, it says so and holds the medals
  back rather than crowning whoever was marked first.
- **Backups now carry your letterhead.** The school seal, the department seal
  and your photo travel with the file and are put back pointing at the right
  place, even on a different computer. Older backups still restore.

## v1.0.0.16

**Searching during attendance no longer marks anyone.**

- Looking for "Alvin" while taking attendance used to mark somebody **Absent**
  on the A and **Late** on the L, walking down the roster as you typed. The P,
  L, A and E shortcuts now stand aside while you are typing in the search box.
- Press **Enter** in that search box to hand the keyboard back to the list, so
  marking carries on without reaching for the mouse.
- Worth a look: if you searched during an earlier meeting, a student may be
  sitting on a status you never chose.

## v1.0.0.15

**The New Programme form shows a programme.**

- It suggested "CC 101" and "Introduction to Computing" — a subject, and the
  opposite of what the same dialog says one line above. It now suggests
  **BSIS** and **Bachelor of Science in Information Systems**.
- A subject's description no longer calls itself a course description; a course
  is a degree programme everywhere else in GradeCore.

## v1.0.0.14

**Finding one student in a class of eighty-seven.**

- Search the score sheet by name or student number, and narrow it to the
  students still missing a score, the highest, the lowest, or everyone below
  the passing mark. The **Highest** and **Lowest** tallies are the quickest way
  in — tap the number to see exactly who is on it, tap it again to come back.
- The row you are typing in now stands out from the rest and follows you down
  as you press Enter, so glancing at the paper and back no longer costs you
  your place.
- Narrowing the list never narrows what is saved: **Save** still writes every
  student, filtered or not, and the row you are editing stays put even when it
  no longer matches the filter.
- **Needs Attention** on a class Overview lists everyone it has flagged, worst
  first, and each name opens that student. The card used to show six and simply
  count the rest.
- The Overview reads tighter, with **Scores To Encode** moved across to fill the
  empty half, and the quick actions have lost the boxes around their icons.
- **Add period**, **Add category** and **Save** in the grading panel answer the
  pointer now instead of sitting still.
- Fixed: opening a score sheet before its class list had loaded left a sheet of
  blank rows that could not be typed into.

## v1.0.0.13

**Closing is instant, and the week starts on Sunday.**

- GradeCore took about ten seconds to disappear after you confirmed you wanted
  it closed. It was ending its own message loop without letting the window shut
  down properly, so the app sat there with nothing left to show. It now closes
  the ordinary way and is gone in under half a second.
- The weekly timetable was drawn Monday to Saturday, which left **Sunday** off
  the grid — a Sunday class could be saved and then never seen again. The week
  now reads Sunday through Saturday everywhere it is shown.
- Removing a meeting time from the schedule asks first. It sits next to Edit
  and took the time off the timetable the instant it was clicked.

## v1.0.0.12

**GradeCore has a way out of its own.**

- **Exit GradeCore** sits at the foot of the sidebar and in the profile menu,
  with its own icon.
- Closing now asks first — and the window's own **X** asks the same question,
  so a stray click on the corner of the screen no longer shuts the app down
  mid-encoding.
- **Your profile** and the lock entry in the profile menu carry drawn icons
  like the rest of the app.

## v1.0.0.11

**A score cannot be higher than the paper is worth.**

- Type 455 into a quiz marked out of 50 and the cell turns red, the percentage
  reads in red beside it, and **Save** will not run until it is corrected. A
  mark above the perfect score used to be quietly halved into the record, where
  it inflated the class standing all the way to the final grade.
- The record itself now holds every score between zero and the perfect score,
  whichever way it arrives.
- **Add period**, **Add category** and **Save** in the grading panel look like
  buttons now instead of plain words.
- Bigger icons in the sidebar, on the class tabs and across the dashboard,
  where the tinted plates behind them are gone so the drawings themselves can
  be seen.

## v1.0.0.10

**Meeting topics stay put.**

- A meeting you had given a topic went back to reading **Meeting 3** the moment
  you recorded its attendance. The topic was being saved and then written over
  a breath later by the switch that counts the meeting towards grades. It is
  not any more.
- The same erasing hit a meeting the moment it was created with a topic, and it
  took the meeting length with it.
- Topics that were already lost cannot be recovered — they were overwritten
  rather than hidden — so they will need typing once more. They will stay this
  time.

## v1.0.0.9

**The Attendance Sheet report has its icon back.**

- The **Attendance Sheet** card in Reports was still drawing a plain symbol
  while every card around it had its own. It now shows the attendance icon —
  the clipboard with ticks.
- Underneath, an icon name that did not match anything used to fall back to a
  plain symbol without saying so, which is how one card went unnoticed.
  GradeCore now refuses to build against a name that does not exist, so it
  cannot happen quietly again.

## v1.0.0.8

**You can see at a glance which classes are online.**

- The weekly timetable marks every block with the icon for how that class meets
  — a classroom door, a camera, or both for a blended class — and the mark
  grows with the block, so a three-hour class carries a big one and a half-hour
  class still fits.
- The same mark, at a readable size, on class cards, in the workspace header, on
  the dashboard's next class and in the **Online** / **Face-to-Face** pills.
- **Assessments**, **Gradebook** and **Groupings** show their icon on every
  class card. All three are built from one grid, which is why they were the
  last to change.

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
