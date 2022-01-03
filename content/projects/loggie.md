---
title: "Loggie"
info:
icon: "loggie.svg"
website: "https://loggie.io"
launched: true
status: "Sold"
PublishDate: 2020-04-12
dol: 2020-04-12
description: "When system fails, log it and get notified" 
date: 2021-12-31T16:54:14+05:30
draft: false
---

Loggie.io was designed to log errors/messages remotely and easily. It contained all the minimal features which makes it cheaper than other logging platforms and good enough to do the job.

![Loggie Homepage](/img/screenshots/landing-page.jpeg)

It consisted of 5 severiety levels:

- Info (Low)
- Debug
- Warning
- Error
- Fatal (High)

You can send logs to the loggie server by using a library written for your choice langugae. For instance, if you are using javascript in your project, you can use javascript library to send the logs:

```js
loggie.info({
	message: "this is a log"
})
```

it is that simple 😁. Now all the logs sent to loggie server will be shown in the minimal dashboard just like shown below

![loggie dashboard](/img/screenshots/dashboard.jpeg)

You can search the logs by their severity level, text, and channels

## Acquisition

After launching it on Producthunt, loggie got a good traction and various acquisiton offers. I decided to move onto another project and sold loggie.

After acquisition, loggie has been renamed to Crashdeck.io