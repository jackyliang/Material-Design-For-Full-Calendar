# Material-Design-For-Full-Calendar

<img src="http://imgur.com/HkrkAaY.png">

### What Is This

This is a Material Design theme for FullCalendar Weekly Agenda view. 
While FullCalendar is pretty awesome, it looks pretty terrible without
any styling. I was inspired by Google's Material Design, while
coincidentally I needed a fitting theme for my Drexel
[Schedulizer](http://loop.tf/schedulizer) service. Doing some basic
research, it didn't seem like there were any Material Design calendar
plugins or themes that were as flexible as FullCalendar's
functionality, so I took matters to my own hands and put this
together.

This is what default FullCalendar looks like. Ew!

<img src="http://imgur.com/vKTKUTx.png">

### Tested Using the Following FC Settings:

FullCalendar 2.4.0

And the following FullCalendar settings:

    editable: false, // Don't allow editing of events
    handleWindowResize: true,
    weekends: false, // Hide weekends
    defaultView: 'agendaWeek', // Only show week view
    header: false, // Hide buttons/titles
    minTime: '07:30:00', // Start time for the calendar
    maxTime: '22:00:00', // End time for the calendar
    columnFormat: {
        week: 'ddd' // Only show day of the week names
    },
    displayEventTime: true, // Display event time

This has NOT been tested on Monthly or Daily views.

### Material Colors: 

To use Material palette, use the Google [Design](https://www.google.com/design/spec/style/color.html#color-color-palette] palette at the 700 level. An opacity of 
0.65 is automatically applied to the 700 level colors to generate a 
soft and pleasing look.

Color were applied to each event using the following code:

    events.push({
        title: 'This is a Material Design event!',
        start: 'someStartDate',
        end: 'someEndDate',
        color: '#C2185B'
    });

### How to Use:

Compile using your favorite SASS compiler, or simply change the file
extension to `.css`. There's little to no actual SASS elements in
here. The `!important` should override any default CSS of
FullCalendar. This was the only way I actually could get it to work

### Please Note

This theme is in no way complete. I did not test it in the monthly or
daily views, since for my purposes, I only needed it to be used in an
`agendaWeek`. It might also be buggy when used in other contexts. Feel
free to contribute using the instructions below.

### How to Contribute:

1. Pull/Fork

2. Issue pull requests

3. Make issues

### License:

MIT. Just credit me.


