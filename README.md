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