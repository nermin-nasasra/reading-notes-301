## Getting Started on Heroku with Node.js
###S Introduction
This tutorial will have you deploying a Node.js app to Heroku in minutes.

Hang on for a few more minutes to learn how to get the most out of the Heroku platform.

The tutorial assumes that you have a free Heroku account, and that you have Node.js and npm installed locally.

### View logs
Heroku treats logs as streams of time-ordered events aggregated from the output streams of all your app and Heroku components, providing a single channel for all of the events.

### Types of logs
* App logs - Logging output from the application itself. This includes logs generated by your app’s code and dependencies. (Filter: --source app)
* System logs - Messages about actions taken by the Heroku platform infrastructure on behalf of your app, such as: restarting a crashed process, sleeping or waking a web dyno, or serving an error page due to a problem in your app. (Filter: --source heroku)
* API logs - Messages about administrative actions taken by you and other developers working on your app, such as: deploying new code, scaling the process formation, or toggling maintenance mode. (Filter: --source app --dyno api)
* Add-on logs - Messages from add-on services. See the add-on’s Dev Center article for details. (Filter varies by add-on)

### Log format
* Timestamp - The date and time recorded at the time the log line was produced by the dyno or component. The timestamp is in the format specified by RFC5424, and includes microsecond precision.
* Source - All of your app’s dynos (web dynos, background workers, cron) have the source, app. All of Heroku’s system components (HTTP router, dyno manager) have the source, heroku.
* Dyno - The name of the dyno or component that wrote the log line. For example, worker #3 appears as worker.3, and the Heroku HTTP router appears as router.
* Message - The content of the log line. Lines generated by dynos that exceed 10000 bytes are split into 10000 byte chunks without extra trailing newlines. Each chunk is submitted as a separate log line.