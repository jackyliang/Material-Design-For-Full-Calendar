# Material Design for jQuery Full Calendar

A Material Design theme for the jQuery Full Calendar plugin

<img src="http://i.imgur.com/TH3VsJU.gif">

What the actual Android Material Design calendar looks like:
<img src="http://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2014/09/1410153384GIF2.gif">

This is what default FullCalendar looks like. Ew!

<img src="http://imgur.com/vKTKUTx.png">

While FullCalendar is pretty awesome, it looks pretty terrible without
any styling. I was inspired by Google's Material Design, while
coincidentally I needed a fitting theme for my Drexel
[Schedulizer](http://loop.tf/schedulizer) service. Doing some basic
research, it didn't seem like there were any Material Design calendar
plugins or themes that were as flexible as FullCalendar's
functionality, so I took matters to my own hands and put this
together.

### Setup Full Calendar

Initialize your FullCalendar object using the following settings

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

Compile `_materialFullCalendar.scss` using your favorite SASS compiler, or simply change the file
extension to `.css`. There's little to no actual SASS elements in
here.

Pushing and adding new events is still the same, although you apply a `color` attribute.

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


