# User Guide — My Checklist

> **Note:** The app's interface is in Persian (Farsi) and is built around the Jalali (Iranian solar) calendar. This guide explains what each part of the interface does, referencing the Persian labels you'll see on screen so you can match them up.

## Install

1. Download `Setup.X.X.X.exe` from the [Releases](https://github.com/adnank68/checklist-app-download/releases/latest) page.
2. Run it and follow the installer (you can choose the install location).
3. After installation, the app starts automatically every time you log into Windows — but only as a small floating bubble, so it won't get in your way.

## Core structure: Month → Week → Day

The app's logic is hierarchical:

1. In the **Monthly** tab (ماهانه), set an overall goal for the month — e.g. "Write articles" with a target of "4" and unit "article".
2. Click the **+** button on that row to break the goal into one or more weekly tasks (the app lists the weeks of that month to choose from).
3. Click **+** on a weekly task to break it into specific days of that week (e.g. "Wednesday").
4. When you check off a daily task, the weekly and monthly levels update automatically in real time (e.g. "1 of 4 articles done, 3 remaining"). Completed rows turn light green.

The **Weekly** (هفتگی) and **Daily** (روزانه) tabs show the same data directly for the current week/day, and also let you add standalone tasks not tied to a monthly goal.

## Two checkboxes on every row

- **The checkbox (تیک):** marks the task as done.
- **The bookmark icon** next to each row: controls whether, if this task isn't finished by the end of its period (day/week/month), it should be surfaced in the "unfinished tasks from last period" banner.

## Carried-over unfinished tasks

Every time you open the app on a Saturday (start of the Iranian week) or the 1st of a new month, if any tasks from the previous week/month with the "carry over" bookmark enabled are still unfinished, they appear in a yellow banner at the top — you can check them off right there.

## Desktop widget

- By default, a small **bubble** floats on your screen showing how many tasks are left for today.
- **Click** the bubble to open the full panel with today's tasks; you can check them off directly, without opening the main app.
- The **−** button in the panel shrinks it back to the bubble.
- Another button opens the full app window.
- Drag the panel by its header to reposition it; the position is remembered.

## Alarms

If you set an alarm time on a daily task (when adding or editing it), a small window with a sound pops up at that time, with options: "Done ✓", "Snooze (10 min)", or "Dismiss".

## Edit and delete

Every row has a pencil icon to **edit** it (title, numeric target, alarm time, carry-over checkbox) and a trash icon to **delete** it.

## History

The **History** tab (تاریخچه) lets you pick any Jalali date and browse that day's, week's, or month's checklist — all data is stored permanently.

## Occasions calendar

The **Occasions Calendar** tab (تقویم مناسبت‌ها) shows Iranian national and religious occasions (Nowruz, Ashura, Eids, Tree Planting Day, Yalda, etc.) month by month, and flags official public holidays.
> Religious/lunar occasion dates depend on moon-sighting and may shift by ±1 day.

## Recurring monthly reminders (installments)

The **Recurring Reminders** tab (یادآوری‌های ثابت) lets you set up a repeating payment (e.g. "Loan installment, 10,000,000 Toman, due on the 11th of each month, for 6 months"). The app shows a notification a configurable number of days before each due date.

## Excel report export

In the **Monthly** tab, the "Download Report" button generates an Excel file with a management summary (total tasks, % completed, % completed late) and full details for that month.

## System tray icon

Right-click the tray icon to open the main window, show/hide the widget, or fully quit the app.
> Note: closing the main window with × just hides it — the app keeps running in the background for alarms and the widget. To fully quit, use "Exit" (خروج از برنامه) from the tray menu.
