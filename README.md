<div align="center">

# GradeCore

**Personal Instructor Management System & Digital Class Record**

A Windows desktop workspace for one instructor's classes — attendance, scores,
grades and printable school forms, all offline in a single local file.

[**Download the latest release →**](https://github.com/iannaz1228/gradecore/releases/latest)

</div>

---

## What it is

GradeCore replaces the paper class record, the attendance sheet, the grade book
and the pile of spreadsheets with one program. It is built for a single
instructor and their own classes.

**It is not an LMS.** There is no student login, no student portal, no student
app, and nothing is uploaded anywhere. Your records live in one SQLite file on
your own machine.

## What it does

- **Classes** — subjects, sections, schedules and semesters
- **Attendance** — per meeting, with late and excused credit that feeds the grade
- **Assessments and scores** — quizzes, activities, projects, exams
- **Grades** — weighted components, per-period computation, transmutation and
  point grades
- **Groupings** — teams and group work
- **Reports** — six printable class forms plus Excel export, on your school
  letterhead with both seals
- **Table of Specifications** — a Bloom's Taxonomy exam blueprint with automatic
  item allocation
- **Grade slips** — a one-page record for a student who asks for a copy, with a
  control number and an issue register

## Install

1. Download **`GradeCore-<version>-Setup.exe`** from the
   [latest release](https://github.com/iannaz1228/gradecore/releases/latest).
2. Run it. It installs per-user, so Windows will not ask for an administrator
   password.
3. Windows SmartScreen may warn that the publisher is unrecognised — the
   installer is not code-signed. Choose **More info ▸ Run anyway**.

There is also a **portable ZIP** if you would rather run it from a flash drive
without installing. The portable build does not update itself.

**Requirements:** Windows 10 or later, 64-bit.

## Updating

Open **Settings ▸ About ▸ Updates** and press **Check for updates**. GradeCore
never checks on its own and never downloads anything unless you ask it to.

When an update is found you will see what changed before deciding. GradeCore
downloads the installer, verifies it against the `SHA256SUMS.txt` published with
the release, then closes so the installer can replace it. **Your class records,
students and settings are kept** — the installer only replaces the program.

## Verifying a download by hand

Every release publishes `SHA256SUMS.txt`. To check a file yourself:

```powershell
Get-FileHash .\GradeCore-1.0.0.1-Setup.exe -Algorithm SHA256
```

Compare the result against the matching line in `SHA256SUMS.txt`.

## About this repository

This repository exists to **distribute releases and publish the changelog**. The
application source is not hosted here.

See [CHANGELOG.md](CHANGELOG.md) for the full version history.

---

<div align="center">

Designed and built by **Ian Magistrado Naz**

</div>
