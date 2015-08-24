# Material-Design-For-Full-Calendar

Material Design CSS theme for FullCalendar Weekly Agenda

### What Is This

This is the Material Design theme for FullCalendar Weekly Agenda view. 
We know the default FullCalendar looks pretty crappy. 

So I turned:

![alt tag](http://imgur.com/vKTKUTx)

To this:

![alt tag](http://imgur.com/HkrkAaY)

### Basic Info

Version: FullCalendar 2.4.0

### Tested Using the Following FC Settings:

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

Note: This has NOT been tested on Monthly or Daily views.

### Colors: 

Use the following - https://www.google.com/design/spec/style/color.html#color-color-palette at the 700 level. An opacity of 0.65 is automatically applied to the
700 level colors to generate a soft and pleasing look.

Color were applied to each event using the following code:

    events.push({
        title: 'This is a Material Design event!',
        start: 'someStartDate',
        end: 'someEndDate',
        color: '#C2185B'
    });

How to Contribute:

1. Pull/Fork

2. Issue pull requests

3. Make issues

License:

MIT. Just credit me.

