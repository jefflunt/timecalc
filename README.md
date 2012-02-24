
**timecalc** is the simplest possible way to calculate the difference between two times. I threw this together for a friend who needed to easily verify times entered on employee time sheets. 

Try it out at [karmanebula.com/timecalc](http://karmanebula.com/timecalc).

Usage
-----

You enter a **start time**, an **end time**, and the page updates with the number of hours between them.

- Because this is for time sheet verification, it rounds the result to two decimal places.
- It also does overnight calculations. So, if someone is working a graveyard shift from 9p-5a the calculator is smart enough to realize that it should still consider that 8 hours over two days, instead of -16 hours within the same day.
- The time result output also color coded: green for "same day" results, and dark blue for "overnight/graveyard shift" results.

**timecalc** only supports 12-hour times (with AM/PM indicators). If you enter 24-hour times (e.g. 14:23 - 2:23pm), or any other invalid time value (such as "0000"), the invalid time value will turn red.

Controls
--------

**timecalc's** controls are intended to be completely keyboard-based.

- When the page loads, it will automatically send keyboard focus to the "start" time field
- Press "Enter" to toggle between the start and end time fields.
- Press up/down arrow while in a time field to toggle the AM/PM indicator for that field.

**timecalc** also automatically formats time for you, for easy display. So, if you enter the digits "115", it will automatically format and display that time as "01:15".

If you really want to use your mouse, you can click on the AM/PM indicators to toggle them.