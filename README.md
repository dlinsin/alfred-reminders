alfred-reminders
================

Alfred Extension to create iOS Reminders

## Setup:

1. download [Reminders.alfredextension](https://github.com/dlinsin/alfred-reminders/blob/master/Reminders.alfredextension)
1. add to Alfred
1. download [alfred_reminders.script](https://github.com/dlinsin/alfred-reminders/blob/master/alfred_reminders.scpt)
1. edit the name of your default Reminders calendar in [alfred_reminders.script](https://github.com/dlinsin/alfred-reminders/blob/master/alfred_reminders.scpt) (at the top of the file)
1. change the path to `alfred_reminders.script` in the extension 

### Sample Setup

Assume you have downloaded `alfred_reminders.script` to `/Users/dlinsin/Downloads` then 
you need to change the path in the extension dialog as follows:

```
osascript /Users/dlinsin/Downloads/alfred_reminders.scpt '{query}'
```

## Usage

Assume today is _May, 17th 5pm_ and the default calendar is called _Private_

* rem get milk -Mon -3am -work
  * titel: get milk
  * due date: May, 21st 3am
  * calendar: Work
* rem get milk -Wednesday -4am"
  * titel: get milk
  * due date: May, 23rd 4am
  * calendar: Private
* rem get milk -tom -8:15am"
  * titel: get milk
  * due date: May, 18th 8:15am
  * calendar: Private
* rem get milk -tom -3:15pm"
  * titel: get milk
  * due date: May, 18th 3:15pm
  * calendar: Private
* rem get milk -6pm"
  * titel: get milk
  * due date: May, 17th 6pm
  * calendar: Private
* rem get milk 
  * titel: get milk
  * due date: May, 17th 6pm
  * calendar: Private
  
## TODOs

See [issues](https://github.com/dlinsin/alfred-reminders/issues)
