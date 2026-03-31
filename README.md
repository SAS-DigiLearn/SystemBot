# PTS Registration Exercise Viewer

1. What this tool is:
This webpage is a training tool used to display PTS Registration practice exercises.
It reads an Excel file, shows exercises one at a time, and keeps everything organised.

2. What the user sees:
- Header with title and logo.
- A dropdown to select a worksheet.
- A progress bar.
- Collapsible sections showing details for each exercise.
- Next/Previous buttons.

3. How it works (simple explanation):
1) The page loads.
2) It downloads the Excel file from GitHub.
3) It reads the spreadsheet.
4) It fills the dropdown with sheet names.
5) When the user picks a sheet, the page converts each row into a structured exercise.
6) Times, dates, and checkbox values are cleaned up.
7) Each exercise is displayed as sections the user can expand.
8) Accessibility features are applied (keyboard and screen readers).
9) The tool remembers which exercise you last viewed.

4. What the tool does NOT do:
- It does not edit or change the Excel file.
- It does not save user input.
- It does not send data to a server.
- It only displays information.

5. Why it is designed this way:
- Easy for trainers to manage.
- Clear for learners.
- No installation or server required.
- Works directly with Excel data.
- Fully accessible.
