---
title: "Projects"
slug: "projects"
date: 2019-07-07T19:35:21+10:00
---

These are some projects that I've been working-on on my spare time, all of them are open source because we're all love open source software don't we?. For a complete list please check [my GitHub account](https://github.com/ekaputra07). 

##### _Gatra Bali_, a news reader app built using Flutter
[Gatra Bali](https://github.com/apps4bali/gatrabali-app) is a news reader app (for Balinese news only) built using [Flutter](https://flutter.dev), initially this app was just a test project to see how is it feel developing mobile app using Flutter and my conclusion is I like it so much :) so I turned it into a production app that can be downloaded [here](https://play.google.com/store/apps/details?id=com.gatrabali.android) (currently only available on Android).

I also designed the whole backend infrastructure which is using some services from _Google Cloud Platform_ such as Compute Engine, Appengine, Firestore, Pub/Sub, Cloud Messaging service and Cloud Function. The backend codes are all written on Golang.

If you're interested about this app backend, I've written a short documentation on how it works alongside its source code [here](https://github.com/apps4bali/gatrabali-backend#how-it-works).
<hr/>

##### _RQMetric_, a log parser CLI built using Golang
[RQMetric](https://github.com/ekaputra07/rqmetric) a.k.a Request Metric is a CLI program that can read web application log file and the result are some metrics about the request itself such as the request count, request code, etc.

This is my first project that using Go programming language and I think Go is my favorite/prefrered language right now even though the company that I work for currently not using it. But for personal project Go is definitely my go-to language.
<hr/>

##### _Quick SMS_, an Android app to create and send predefined SMS
[Quick SMS](https://github.com/ekaputra07/quick-sms) is a simple Android app that allow you to create predefined sms messages and send them easily.

It was born out of my need to send the same message again and again to my girlfriend :) at that time I'm pretty sure there are similar apps out there that can do the same thing but I decided to built it myself with the feature list that I wanted.

It was lived for a couple of years and has many happy users but early this year (2019) Google announced that they will ban all apps that are able to send sms message directly without using the default sms manager app, unfortunately for this app being able to send sms directly from the app is the main feature so its become useless without it, then I decided to shut it down.

Having this app lived and maintained it for a couple of years and received many feedbacks from users has taught me invaluable lessons about how deal with our app users eg. feature requests, complains and compliments.
<hr/>