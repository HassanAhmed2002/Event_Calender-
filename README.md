# Event_Calender-

The code creates a function called "loadCalendar" that loads the calendar for the current month. It starts by creating a new Date object, which represents the current date and time. It then checks the value of the "navigation" variable to determine if the user has clicked on the previous or next month button. If the user has clicked on either button, the code adjusts the month accordingly.

The code then creates a banner that displays the name of the current month and year using the toLocaleDateString method. The code then creates a loop that iterates over the days of the current month and creates a div element for each day.

The loop also checks to see if the current day is a holiday or an event day. It does this by comparing the date of the current day to the dates of the holidays and events in the "holidays" array and the "events" array, respectively. If the current day is a holiday or event day, the code creates a div element to display the name of the holiday or event.

Finally, the code adds the div elements to the calendar using the appendChild method. The code also sets the id of the div element that represents the current day to "currentDay" so that it can be styled differently using CSS.
