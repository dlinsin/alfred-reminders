alfred-reminders
================

Alfred Extension to create iOS Reminders

![Sample Screen Shot](https://github.com/downloads/dlinsin/alfred-reminders/reminder_screen_shot.png)

## Setup:

1. download [Reminders.alfredextension](https://github.com/downloads/dlinsin/alfred-reminders/Reminders.alfredextension)
1. drag it to Alfred
1. edit the name of your [default Reminders calendar](https://github.com/dlinsin/alfred-reminders#default-reminders-calendar) at the top of the AppleScript
1. done

### Default Reminders Calendar

If you don't know the name of your Reminders calendar:

![Default Reminders Calendar in iCal](https://github.com/downloads/dlinsin/alfred-reminders/setup_default_calendar.png)

1. go to iCal
1. make sure the Reminders panel is visible
1. click on Reminders to reveal your iCould calendars, which are also used for Remindes
1. edit the name of your default Reminders calendar in Alfred

## Usage

Assume today is _May, 17th 5pm_ and the default calendar is called _Private_

* rem get milk -Mon -3am -work
  * titel: get milk
  * due date: May, 21st 3am
  * calendar: Work
* rem get milk -Wednesday -4am
  * titel: get milk
  * due date: May, 23rd 4am
  * calendar: Private
* rem get milk -tom -8:15am
  * titel: get milk
  * due date: May, 18th 8:15am
  * calendar: Private
* rem get milk -tom -3:15pm
  * titel: get milk
  * due date: May, 18th 3:15pm
  * calendar: Private
* rem get milk -6pm
  * titel: get milk
  * due date: May, 17th 6pm
  * calendar: Private
* rem get milk 
  * titel: get milk
  * due date: May, 17th 6pm
  * calendar: Private
  
## TODOs

See [issues](https://github.com/dlinsin/alfred-reminders/issues)
