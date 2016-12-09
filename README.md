# CourseraDataCleaning

This repository show the steps taken for cleaning the Coursera's video event data for courses offered by the University of Illinois. 

Video events are recorded as users interact with lecture videos through the browser. Videos watched on both iOS and Android apps will not be reflected in the exports.

Every video event consists of metadata, a key, and a value. The metadata contains information about the client sending the event. The key identifies the type of user action being recorded, and the value is a JSON object consisting of data specific to that event. 

While the specifications of every variable and metadata can be found at https://wiki.illinois.edu/wiki/display/coursera/video, the document will briefly explain each of the variables when they were in use. 

This data is cleaned in such way that every user intereaction is recorded at some specific point in time.

