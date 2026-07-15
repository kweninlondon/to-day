# Release Notes

## v1.3

- 🗂️ Groups:
    - Brought back chevron on groups.
    - New icon for Completed groups.
    - Task title looks better when removing a group
    - You can now move a whole group to any timeframe with long press

- ⚙️ Settings:
    - Added "What's new" sheet.
    - Tip icon is now 50% bigger.
    - Start of day, week and month are now synced with iCloud (optional)

- 🐛 Bug fixes:
    - Fixed moving a task from a previous timeframe to current frame
    - Permanently deleting a task now removes its todo events (Saving data space)

## v1.2

- 🗂️ Groups:
    - Smarter group suggestions above the keyboard.
    - Type `[`, `{` or `:` to quickly create a group tag.
    - Group suggestions now focus on the current view, so they should feel more relevant.
    - Moving a task into a group now shows a message you can tap to jump straight to it.
    - New remove group button.
    - Group tag symbol complete suggestion.

- 🔃 Recurring:
    - Recurring tasks are now sorted by repeat frequency.
    - Recurring groups better inherit the state of the tasks inside them.
    - Deleting a recurring task now supports Undo.
    - Recurring tasks now keep a clearer history of changes.
    - Permanently deleted generated tasks should no longer reappear.

- 📊 Statistics:
    - Improved the look of the Statistics tab.
    - Added "Hide statistics" toggle to help people stressed by data.

- ⚙️ Settings:
    - You can now force Dark Mode or Bright Mode on.

- ☁️ iCloud and ⚡️ performance:
    - Fixed a slowdown when typing in task titles with groups.
    - Improved keyboard responsiveness when adding tasks.
    - Protected task from impatient taps while changing tabs.
    - Improved how the app handles remote iCloud changes.
    - Added iCloud status banner.

- 🐛 Bug fixes:
    - Fixed missing weekly and monthly recurring tasks.
    - Fixed archived Someday recurring tasks being recreated incorrectly.
    - Fixed incorrect metadata on archived Someday recurring tasks.
    - Fixed several recurring task cleanup and repair issues.
    - Fixed tips not displaying on iPad.
    - Fixed a group icon display bug where fully completed group shows the wrong icon.
    - Fixed a bug were moving older active task into a shorter time frame didn't display the task properly.

---

## v1.1

- 🗂️ Groups:
    - Type `[`, `{` or `:` to get group suggestions. Requires at least one group.
    - You can now swipe on a group to batch edit group tasks.
    - Long press to rename a group.
    - Groups now show progress and better status colours.

- ℹ️ Task info:
    - Long press now opens the task info sheet.
    - Task info now includes move, copy, status, schedule, and list controls.
    - Task info now shows the device the task was created on.
    - Recurring tasks and generated tasks now show streak progress.
    - Task history is now 15 events long.

- 📊 Statistics:
    - Added a Tasks completed per day section.
    - Added recurring task statistics, including streak count.

- ⚙️ Settings:
    - Added Documentation.
    - Added support to-day / tip jar.
    - Added Tips to help discover app features organically.
    - “Month starts at” now has a collapsible calendar.

- 🔃 Recurring:
    - Added recurring task creation.
    - Added recurring task info.
    - Added Someday recurring presets.
    - Generated tasks now link back to their recurring task.
    - Recurring tasks should now remember pause periods, so the app no longer creates or deletes generated tasks during paused periods.

- 🗺️ Navigation:
    - Added Last Week and Last Month views.
    - Tapping some messages can now take you straight to the related task.

- ☁️ iCloud:
    - General stability improvements.

- 🐛 Bug fixes:
    - Fixed a bug where recurring tasks did not show in past views.
    - Fixed missing generated tasks when more than five needed to be created.
    - Fixed several recurring task streak and success-rate calculations.
    - Fixed task info crashes, keyboard issues, and display bugs.

---

## v0.1 / Initial build

- First working version of to-day.
- Added the main task views for planning tasks.
- Added task creation, editing, completion, archiving, and deletion.
- Added the foundations for iCloud sync, settings, task history, recurring tasks, groups, and statistics.
