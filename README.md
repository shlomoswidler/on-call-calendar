# on-call-calendar
Create on-call assignments in a calendar interface

## What

A tool to record on call assignments. The period of time is chosen by the user. Holidays can be marked and assigned in advance.

## Why

You have a pool of people who need to be on call, and you want to assign one person to cover each day. You also want to dole out assignments remotely but share the view of this calendar among all participants - perhaps via screen sharing or via a shared office.com file - so everyone can see the assignments as they are created.

## Details

This Excel file contains rudimentary formatting, with the expectation that you will customize the formatting to your liking.

The date range shown on the calendar is customizable, up to 12 weeks in length. Just enter the start date and the end date at the top and the calendar will be generated in the grid below.

The top area of the spreadsheet shows helpful statistics about the date range, such as number of weekdays and weekend/holiday days, so you can more easily figure out how to distribute assignments fairly.

A table of holidays shows the holiday schedule, and allows holiday assignments to be made far in advance of the actual holiday dates. Special formatting is applied to warn the user if an assignment is entered into the calendar that differs from the assignment set in the holiday table.

Several Conditional Formatting rules are present. The formatting for these can be customized. The Conditional Formatting rules refer to "date cells," which are the cells that contain the date, and "assignment cells," which are cells that contain the name of the person assigned for that day.