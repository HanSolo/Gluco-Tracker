## Gluco-Tracker

An application that visualizes the blood glucose data coming from a nightscout server.

The application is written in Swift using SwiftUI and is available for iPhone, iPad.

[App store](https://apps.apple.com/us/app/gluco-tracker/id1526976290?mt=8)


The application was created to monitor the blood glucose values of our son. It also comes
with support for the Apple Watch. 
On the Apple Watch, it is a separate application and won't show the values from the connected phone.
You can use the app even without the phone being around (in case you have an LTE enabled Apple Watch).
If you open the app on your Apple Watch, it will automatically load the latest value, otherwise you
can update it by tapping the display on your Apple Watch.
If you need to get the latest value on your watch you simply have to click on the complication
and tap the screen of the watch when the watch app opens.

Here are screenshots from the different application screens.

## Main screen (Line chart)
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_1.png)


## Main screen (Poincaré plot)
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_2.png)


## Carbs screen
In this screen you can add carbs which will be stored on your nightscout server and
will be displayed also in the main chart.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_9.png)


## Matrix chart
A chart that shows the last 30 days with it's average glucose values. The days are
colored dependent on the average. To see the average of a single day, simply tap
the day you are interested in and it will show you the value.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_3.png)


## Day comparison chart
A chart that let you compare different week days to find out patterns. You can for
example compare the values of today with Mondays of the last week, last 2 weeks or
the last 30 days. You could also compare Mondays to Tuesdays etc.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_4.png)


## Pattern screen
This screen shows the average values for the 24 hours based on the last 7 days, the
last 14 days or the last 30 days. This can help to identify patterns on specific
times of the day. It will also show you the current HbA1c value based on values from
the last 30 days.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_5.png)


## Time in range screen
The screen shows you the percentage that your glucose level has been in the different
glucose ranges. The values are based on the currently selected interval e.g. 24h
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_6.png)


## Timer settings
In the timer settings you can reset and save the reminder dates for your catheter,
sensor and pump battery. The intervals can be defined in the settings.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_7.png)


## HbA1c history chart
The Gluco-Tracker app will save the HbA1c once a day to your device. The HbA1c history
chart will show you the daily value for the last 365 days. The chart will be empty the
first time you start your app on your device because it has no values yet. Meaning to
say it will fill up over time.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_8.png)


## Settings screen
In the settings screen you can adjust all kinds of settings. If you are a Gluroo
user, you have to put the gluroo url in the nightscout url field and the gluroo api
key in the token field. to make it work.
![](https://github.com/HanSolo/Gluco-Tracker/blob/master/GlucoTrackerOverview_10.png)
