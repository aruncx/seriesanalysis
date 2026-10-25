<div align="center">

<img src="assets/vast-logo.png" alt="Vidya Academy of Science and Technology" width="220">

# VAST Series Examination Analytics

**Turn a series-test result sheet into class analysis, series-to-series comparison, student support lists, remedial plans, and print-ready PDF and Excel reports. In your browser, in minutes.**

[Open the tool](https://aruncx.github.io/) · [About](about.html) · Developed by **Arun Xavier**, Asst. Prof., Dept. of EEE, Vidya Academy of Science & Technology, Thrissur

</div>

---

## Why use it

| | Advantage | What it means for you |
|---|---|---|
| 🔒 | **Private by design** | Everything runs in your browser. Result files are never uploaded to any server. |
| ⚡ | **Loads the college report directly** | The "Series Test Analysis Report" `.xls` is read as it is: subjects, faculty, maximum marks, attendance, batch, semester and date are picked up automatically. |
| 🔁 | **Series I vs II vs III** | See who improved, declined, cleared a failure or failed something new, subject by subject and student by student. |
| 🎯 | **Finds students who need support** | Configurable rules (failed in the latest series, repeated failure, falling marks, marks near the pass mark, low attendance), with a written reason for every student. |
| 🧭 | **Priority labels, not judgements** | High priority, Priority and Monitor are follow-up priorities for faculty, not statements about ability. |
| 🛠️ | **Editable remedial plans** | Intervention, mentor, review date, status and faculty remarks stay in your hands and flow into the PDF and Excel exports. |
| 👩‍🏫 | **Mentor allocation** | Enter a mentor and roll numbers such as `2-20, 55, 58`. Mentors appear on support lists, progress cards and a mentor-wise report. |
| 🧩 | **Electives handled** | Mark a subject as an elective: blank marks mean "not enrolled", not "missing". |
| 📉 | **Absent counts as a fail** | One consistent rule everywhere, matching the college report. |
| 🏆 | **Top 5 and Last 5** | One page per report with the leading and trailing students of every series. |
| 📄 | **Designed PDF report (A4 landscape)** | Cover with department and logo, executive summary, charts, colour-coded tables, progress cards (one per page) and a page preview. You choose the sections and their order. |
| 📊 | **Styled Excel workbook** | Coloured sheets with headers, filters, frozen panes and status colours, including Subjects & Faculty and Mentor Allocation. |
| 🌗 | **Light, Medium and Dark themes** | Comfortable on any screen, and the choice is remembered. |
| 💸 | **Nothing to install, nothing to pay** | A single web page you can host free on GitHub Pages. |

## How it works

1. **Load** the Series Test I and II result files (`.xls`, `.xlsx` or `.csv`). Series III is optional.
2. **Check settings.** Confirm department, subjects, core or elective type, maximum and pass marks. Add mentors if you wish.
3. **Review** the analysis, comparison, support list and remedial plan. Edit anything that needs a faculty decision.
4. **Export** the PDF report and the Excel workbook from the Export to PDF/Excel.

## Rules used (all configurable where noted)

- **Absent = fail.** An absent subject counts as a failed subject in every figure.
- **Pass mark** defaults to 40% of the maximum and can be changed per subject.
- **Pass %** = passed ÷ enrolled students in the subject.
- **Blank marks are never treated as zero.** In a core subject they are flagged as missing; in an elective they mean not enrolled.
- **Improvement** is only called "Improved" when no new failure appears; a student who still has failures is labelled "failures remain".
- **Support criteria** can be switched on or off and their thresholds changed.

## Input format

The college export loads as it is. For other files, use one row per student with these columns:

`Roll No` · `Student ID` · `Univ Reg No` · `Name` · one column per subject (e.g. `EET305 Control Systems`)

Use `AB` for absent. An optional `Failures` column is cross-checked against the computed failures. A CSV template can be downloaded from the tool.

## Privacy and responsibility

- No data leaves your device. Closing the tab clears the loaded results.
- The tool analyses the files you give it. Verify important decisions against the official records; results depend on the layout and accuracy of the uploaded file.

## Run it

- **Online:** open the GitHub Pages link above.
- **Offline:** download `index.html` and open it in a modern browser (Chrome, Edge, Firefox or Safari). An internet connection is needed the first time for the spreadsheet, PDF and font libraries.

## Publish your own copy on GitHub Pages

1. Create a repository named `aruncx.github.io`.
2. Upload `index.html`, `about.html`, `robots.txt`, `LICENSE` and the `assets` folder to the repository root.
3. In **Settings → Pages**, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Open `https://aruncx.github.io/`.

## Project files

| File | Purpose |
|---|---|
| `index.html` | The application (single file) |
| `about.html` | About page |
| `robots.txt` | Asks AI and data-mining crawlers not to crawl the site |
| `LICENSE` | All rights reserved |
| `assets/` | Logo and campus image |

## Protection notes

Right-click, common DevTools shortcuts and view-source are blocked, and `robots.txt` asks AI crawlers to stay away. These measures deter casual copying and only well-behaved crawlers obey `robots.txt`. They cannot hide code from a determined person, and a public repository shows its source on GitHub itself.

## Credits and licence

Developed by **Arun Xavier**, Asst. Prof., Dept. of EEE, Vidya Academy of Science & Technology, Thrissur · [github.com/aruncx](https://github.com/aruncx)

© 2026 Arun Xavier. All rights reserved. See `LICENSE`.
