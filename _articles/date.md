---
layout: article
title: Date
permalink: /date/
---

In Dynalist, you can manage due dates and events with dates.

![](http://i.imgur.com/cZ5Wbgv.gif)

#### Adding a date

Add a date by typing "!" after a space. A date picker will pop up, allowing you to choose a date and time. After choosing them, click on the "Done" button to enter the date. You can also use the `Enter` shortcut.

#### Choosing a time

We provided a list of predefined times with half hour increments. You can also enter your own time.

> Note: the format of the time your entered has to be consistent with the provided times. You can change this setting in though.

#### Editing a date

To editing an existing date, simply click on it to trigger the date picker. The rest of the same as adding a date, except the date is replaced rather than inserted when you click on "Done".

#### Searching for dates

To search for dates, use the `within:`, `since:`, and `until:` search operators. Follow the operator with time range shorthands such as `24h`, `-2d`, `4w`, or `-3m`. `h`, `d`, `w`, and `m` stand for hour, day, week, and month, respectively. Positive numbers stand for the future whereas negative numbers stand for the past.

> Note: `24h` is not equivalent to `1d`. `d`, `w`, and `m` time ranges always end at end of the last day rather than the current time, whereas `24h` means preciously 24 hours from now.

Two special values: for date results between now and end of today, use `within:0d`. For date results between start of today to end of today, use `within:today`.

You can combine these operators with other keywords to further filter the results.

#### Bookmarking date searches

Bookmarking date searches allow you to get the results instantly without re-entering the search terms. You can also give them more sensible names (e.g. "School work due this week" to the search results of `within:1w @school`).

For how to bookmark searches, see the "[Bookmarking search results](../bookmarks/#bookmarking-search-results)" section.

#### Options

For date-related settings like the time format, see the "[Date preference](../preferences/#date)" section.