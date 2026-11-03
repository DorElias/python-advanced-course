# Python Advanced Course - Status

Updated 2026-10-31, before the first live run. The notebooks are under review and fixes are still in progress, so this file lists contents, not a guarantee of quality. See `TEACHER_GUIDE.md` for the schedule, risks and fallbacks.

## Contents (30 notebooks in 8 days: 27 lesson notebooks + 3 day 4 offline variants; one lesson notebook, day 6 Git, is optional)

| Day | Topic | Notebooks |
|-----|-------|-----------|
| 1 | Review and functions | `1_Review`, `2_Functions_and_Modules`, `Summary` |
| 2 | Advanced OOP | `1_Classes_Review`, `2_Advanced_OOP`, `Summary` |
| 3 | CSV, JSON, Excel | `1_CSV_Files`, `2_JSON_Files`, `3_Excel_Files`, `Summary` |
| 4 | Requests and APIs (needs internet) | `1_Requests_Basics`, `2_Working_with_APIs`, `Summary` + offline variants `1_Requests_Basics_Offline`, `2_Working_with_APIs_Offline`, `Summary_Offline` |
| 5 | SQLite | `1_SQLite_Basics`, `2_SQL_Advanced`, `3_SQL_with_Python_and_CSV`, `Summary` |
| 6 | Pandas (+ optional Git) | `1_Pandas_Basics`, `2_Pandas_Analysis`, `3_Git_Basics_Optional` (optional), `Summary` |
| 7 | Email, Threading, Asyncio (optional) | `1_Email_Automation`, `2_Threading_Basics`, `3_Asyncio_Basics`, `Summary` |
| 8 | Final project | `Final_Project`, `Summary` |

## Known limitations

- Days 4 and 7 use the internet; fallbacks are described in `TEACHER_GUIDE.md`.
- Day 4 has two versions of each notebook. The normal notebooks assume the network works (they only use `timeout=10`, `try/except` and status checks). The `*_Offline` notebooks are for when the classroom network blocks the APIs: if a request fails they load a saved response from `resources/*_sample.json`. That fallback is only a classroom workaround and is explained as such in the notebooks.
- In the normal day 4 notebooks, `resources/quotes_sample.json` and `resources/weather_sample.json` are only examples of what a response looks like (students open and read them); the code never loads them.
- Day 5 `2_SQL_Advanced` and the day 5 `Summary` are short compared to the other days.
- Email sending (day 7) is intentionally not executed in class.
- Day 6 `3_Git_Basics_Optional` is optional and needs `git` installed (no internet or GitHub account). It creates and wipes the sandbox folders `git_playground`, `git_playground_remote`, `git_playground_clone` and `git_exercise` next to the notebook; they are listed in `.gitignore` because they contain their own `.git` folders. Only tested on Linux so far, not yet on Windows.
- Web scraping and AI/LLM APIs are not covered (listed as next steps).
- Teacher solutions are kept separately by the instructor, not in this repository.

## Repository files

- `README.md` - student-facing overview and installation
- `TEACHER_GUIDE.md` - schedule, pre-class checklist, risks
- `PYCHARM_SETUP.md` - optional PyCharm guide
- `requirements.txt` - libraries (Python 3.10+)
- `.gitignore` - ignores files created by running the notebooks
