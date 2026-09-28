# Release Notes

## v1.4

- 📝 Notes:
    - Add checklists to task notes and tick off items directly from the task list or Task Info.
    - Task notes now support Markdown, including bullet lists, numbered lists and links.
    - Reorder checklist items using the drag handles in Task Info.
    - Added bullet list, numbered list, checklist and link shortcuts to the inline and full-screen note editors.
    - Added named links. Selecting text or a web address prefills the link editor, and existing links can be edited from the cursor.
    - Added a full-screen note editor.

- 📊 Statistics:
    - Added Week, Month, Year to Date and Year ranges to the Statistics Overview. Year ranges appear when they show different results.
    - Recurring task statistics now include historical data.
    - Improved Statistics insight wording and planning advice.

- ℹ️ Task Info:
    - Group and task titles are now displayed separately.
    - Added group suggestions when editing tasks, including adding a group to an ungrouped task.
    - Improved grouped task title editing and confirmation controls.

- 🗂️ Groups:
    - Reorder tasks inside a group using the new order button in the top-right corner, or from the group's long-press sheet.
    - Group moves can now ask whether to include completed tasks.
    - Improved group status colours and completion progress, including tasks completed early or late.
    - Task groups now stay together when using the Bottom layout.

- ⚙️ Settings:
    - Added an animated checklist tip, also linked from What's New.

- 💄 Interface improvements:
    - Improved note, checklist and recurring section chevron placement.
    - Improved expanded note spacing, checklist layout and reordering feedback.

- 🐛 Bug fixes:
    - Fixed the group Back button not always responding.
    - Fixed task cards briefly flashing with the wrong appearance and sheets not consistently following the saved theme.
    - Fixed note editing not always opening or focusing correctly.
    - Fixed list insertion and continuation at the cursor, including when Return accepts keyboard autocorrection.
    - Fixed checklist taps not reliably updating items, and grouped task checklists collapsing after a tap.
    - Fixed completed recurring tasks not following the same completion-date order as regular tasks.
    - Fixed completed and incomplete task ordering inside open groups, including after completing a task.
    - Fixed the Coloured Status Circles setting not applying correctly to groups.
    - Fixed untouched groups appearing faint green instead of grey, and completed group progress in One Day.
    - Fixed moving tasks and groups from previous weeks or months into the current period, including confirmation and navigation from the move message.
    - Fixed the completed-tasks chart for the year view.

---

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
