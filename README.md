# thebutton-data
The csv file contains the press history for [/r/thebutton](https://www.reddit.com/r/thebutton).

The csv has four columns:

`press time` the date and time at which the press happened

`flair` the timer value the user got as flair

`css` the flair class given to the user

`outage press` whether the press was an automatic press during a site outage to keep the button alive

Outage presses were relatively few and never occurred at a time when the button was truly at risk of expiring, but if you're doing real scientific analysis on this data, you may choose to discount these presses or otherwise make a note of them.

Source code for the button is at https://github.com/reddit/reddit-plugin-thebutton.
