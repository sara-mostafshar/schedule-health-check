# Schedule Health Check – DCMA 14-Point

**▶ Use it free:** https://sara-mostafshar.github.io/schedule-health-check/ · **🎥 Video (3 min):** https://youtu.be/55a_eWYZm0c

A free tool that runs the DCMA 14-point schedule assessment in seconds. Upload an Excel export of your schedule and see:

- Which checks pass or fail
- The activities behind each check (click any check)
- A plain-English summary for management

## How to use
1. Open the link and click **Try the sample project**, or download the sample Excel template.
2. Prepare an Excel file with the sheets `Activities` and `Relationships`.
3. Drop the file on the page.

Thresholds follow the DCMA 14-Point Schedule Assessment. Durations and float are in working days (Mon–Fri).

🔒 Your file is read in your browser only. The sample project is fictional.

## What's new
**Version 1.1 – 20 Nov 2026**
- Data date: the date box now gives the same day in every time zone (before, users in the Americas got one day earlier).
- Text dates such as `28.8.2026` or `28/08/2026` are read day-first (European style). Before, `1.9.2026` was read as 9 January.
- The message under the upload box shows which data date is used and where it comes from (file or date box).
- Logic loops now fail the Critical Path Test and list the activities involved, and the verdict is capped at "Needs attention".
- Invalid Dates now counts only non-Level-of-Effort activities (sample: 2 of 45 instead of 2 of 46).
- CPLI description explains which float is used; the health score explains its own rule of thumb.
- Sample Excel template: colour legend, notes on every column header, frozen header rows.

## Use the online version
Please use the online version for the latest tested release: https://sara-mostafshar.github.io/schedule-health-check/ – downloaded copies do not receive fixes and updates.

## License
Free to use, share and adapt under the [MIT License](LICENSE). Please keep the credit to Sara Mostafshar.

Built by [Sara Mostafshar](https://sara-mostafshar.github.io) · AI agents and free tools for project controllers and project managers
