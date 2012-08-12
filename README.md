alfred-reminders
================

An extension for [Alfred](http://www.alfredapp.com/) to create iOS Reminders. You'll need Alfred's 
[Powerpack](http://www.alfredapp.com/powerpack/) to use this. 

Reminders.app must to be running, since the extension needs to access it.

![Sample Screen Shot](https://github.com/downloads/dlinsin/alfred-reminders/reminder_screen_shot.png)

## Setup:

1. download [Reminders.alfredextension](https://github.com/downloads/dlinsin/alfred-reminders/Reminders-2.0-beta2.alfredextension)
1. drag it to Alfred
1. done

### Default Reminders list

If no list is specified (see [Usage](https://github.com/dlinsin/alfred-reminders#usage)), the extension adds the new Reminder to your default list. 
The list can be changed by dragging it to the top position:

![Default Reminders List](https://github.com/downloads/dlinsin/alfred-reminders/setup_default_list.png)

## Usage

The extension expands abbreviations of days like _tom_ or _tue_ so you could write:

__rem get milk tom at 3pm #private__

You can specify a list the reminder is adde to, by adding a pound/number sign followed by 
the list name at the end of the input. _Note: list names are case sensitive._

Here are a couple of examples assuming it's _Sunday - July, 29th 9:30am and your default list is called "private"_

* rem get milk tom at 3pm
  * title: get milk
  * remind me: Monday - July, 30th 3pm
  * list: private
* rem get milk monday at 3pm #work
  * title: get milk
  * remind me: Monday - July, 30th 3pm
  * list: work
* rem get milk tomorrow at 3pm
  * title: get milk
  * remind me: Monday - July, 30th 3pm
  * list private
* rem get milk sunday at 3pm
  * title: get milk
  * remind me: Sunday - July, 29th 3pm
  * list: private
* rem get milk today at 3pm #work
  * title: get milk
  * remind me: Sunday - July, 29th 3pm
  * list: work 
* rem get milk sunday at 7am
  * title: get milk
  * remind me: Sunday - July, 29th 7am
  * already due

## TODOs

Report through [issues](https://github.com/dlinsin/alfred-reminders/issues)

## Extension Updater

The extension supports David Ferguson's awesome [Extension Updater](http://jdfwarrior.tumblr.com/updater), 
so no need to check on updates here manually. 
