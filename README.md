# Material Design for jQuery Full Calendar

A way to apply Material Design to the jQuery Full Calendar plugin

<img src="http://i.imgur.com/TH3VsJU.gif">

What the actual Android Material Design calendar looks like:
<img src="http://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2014/09/1410153384GIF2.gif">

This is what default FullCalendar looks like. Ew!

<img src="http://imgur.com/vKTKUTx.png">

### Setup

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
    
### Usage

Compile using your favorite SASS compiler, or simply change the file
extension to `.css`. There's little to no actual SASS elements in
here. The `!important` should override any default CSS of
FullCalendar. This was the only way I actually could get it to work

Then

    events.push({
        title: 'This is a Material Design event!',
        start: 'someStartDate',
        end: 'someEndDate',
        color: '#C2185B'
    });

### Applying Material Design Colors 

<img src="http://i.imgur.com/HCeR1PB.png"></img>

Color palette was pulled from the Google Material Design [documentation](https://www.google.com/design/spec/style/color.html#color-color-palette). 

Highly recommend the 700 level palette to achieve the same color effect as I do.

An opacity of `0.65` is automatically applied to each event to achieve a softer look. 



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


