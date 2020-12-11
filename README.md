# my-notion

My independent implementation of my three most used templates on Notion; like on a minimalist scale. Built to best accomodate my preferences for Notion.

# Calendar

All three templates are contained within a calendar.

# Todo

Timeblocking/boxing. Uses Gridstack. Drag and resize blocks with a task + a checkbox over timeslots (24 hours), and edit the blocks in a popover. Uses a Richtext editor to allow for checkboxes.

# Habits

Edit & delete habits, + switch em on upon completion. Re-order the habits too, and add new ones. A completion bar is rendered atop.

# Journal

Very simple: title & textarea.

# DATA

Uses LocalStorage. Four different "stores":
- calendar store
  - date -> what pages (todo, habit, and/or journal) exist on this date
  
- todo store: date ->
  - location & size of the blocks
  - checked or not checked?
  - tags, names & notes
 
- habits store: date ->
  - order of habits
  - switch on/off for each
  - names
 
 - journal store: date ->
  - title
  - entry
  
