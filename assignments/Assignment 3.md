# Know your user's screen size (view port resolution)

## Assignment 3a: Find which custom dimension you need to use
Before you can send custom data to Google Analytics, you need to find the right index to put the data in.

**Tip**: *If you are using the same Google Analytics property on multiple applications, make sure when using custom dimensions,
that they **always have to** align. If not, they can create data discrepancy*   

## Assignment 3b: Save the user's view port resolution
The training page has some code already prepared to check the user's viewport size on page load.
Send this data to the correct custom dimension. 

**Tip**: *A custom dimensions **always** needs to be followed up a `hit`. A `hit` is considered to be a page view or an event.
In most cases, it is preferable to set them **before** a page view. This way, when a user may go away, the last data is always submitted.* 

## Assignment 3c: See in the console if your data is being sent to the right custom dimension
Open your development console and see if your data is being sent.

**Tip**: *We learned that events and page views can be viewed in real-time. Unfortunately, with custom dimensions it is not possible. 
They affect all data and usually takes up to 24 hours to fully be available to report on. The time is based on the size of the amount measurements and visitors.*

## Class assignment 3d: Let's create a report
Since we cannot work directly with the data, let's use existing data together and explore the possibilities. 

## Why do we need this?
Custom dimensions can define a user's choices over time. Think of the screen size example, but also
language of choice, preferred filters when searching. You can use the data from custom dimensions to create a dimension
in reports.

**Documentation**: https://developers.google.com/analytics/devguides/collection/analyticsjs/custom-dims-mets

## What you will learn 
- How to set a custom dimension
- How to create a report with this

## Extra tips
You can use also custrom metrics. They fulfill the same purpose as custom dimensions, but you can store more value specific use
cases here. Like stored preference of the amount of products shown in a search result.
