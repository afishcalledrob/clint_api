# Clint API
Clint is an API that provides programmatic access to content, specifically related to events and activities around the UK.  The return format for all endpoints is JSON and currently there is no front-end for this site.

You can view the content of the API in the console (https://stark-brook-82296.herokuapp.com/events)

### What is it for?

Clint API allows websites to access specific details of venues around the UK.  Content for each activity includes the venue, location, available dates, price-range, category for the type of activity it is, allowing the website to decide how and what to filter on depending on what they wish to be displayed.

The API was created using the Ruby on Rails framework.  The content is seeded into a Postgres database, with links to images for each event, which are stored on AWS3.

Collaborators: Sam Worrall, Salome Lambermont, Robert Fishwick and Zoe Kavanagh
