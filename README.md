# Eyevinn Open Source Cloud Onboarding

The best way to get started and learn how you can build solutions based on open web services is to get your hands dirty. Here are some suggested exercises to get started.

## FAST Channels

- Level 1: channel with playlist from static textfile
- Level 2: channel with playlist from database
- Level 3: channel with playlist from database and with ad placement opportunities for SSAI ad replacement

## VOD Streaming Platform

- Level 1: ABR transcode a file when is created on a bucket and result is placed on another bucket
- Level 2: store the location of the created ABR files in a database
- Level 3: create HLS+MPD when a file is placed on a bucket 

## Generate Subtitles

- Level 1: Generate subtitles for a video file on a bucket and store the resulting subtitle file in the same bucket
- Level 2: Subtitle generation automatically triggered when a file is created on a bucket
- Level 3: Create a VOD from the video with the generated subtitle file

## Uptime Monitor

- Level 1: Monitor HLS streams and provide an open metrics endpoint 
- Level 2: Create a ping service that provides an endpoint to trigger a check on a site and stores the result in a database

## Player integration tests

- Level 1: Setup a Playwright test to verify that an error event is reported when a segment cannot be downloaded
- Level 2: GitHub workflow running Playwright tests where OSC instances are created before tests are run and removed when tests are completed
- Level 3: Verify that client side ads are played and tracking is correctly reported

## Frontend application

- Level 1: A frontend application available online for a simple todo application where the todo list is stored in a CouchDB database
- Level 2: User registration and login for access to the todo application
- Level 3: A user can attach images and videos to a task in the todo list

# Resources

- [Open Source Cloud Documentation](https://docs.osaas.io)
- [Example solutions built with Open Source Cloud](https://github.com/EyevinnOSC/solutions)
- [Javascript SDK documentation](https://js.docs.osaas.io)
- [Open Source Cloud Developer Blog](https://dev.to/oscdev)
- [Open Source Cloud Blog](https://blog.osaas.io)
- [Slack community](https://slack.osaas.io)