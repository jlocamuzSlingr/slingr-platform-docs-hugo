---
title: "Getting started"
description: "Welcome to Slingr - the ultimate platform to create cloud apps that integrate with other SaaS solutions seamlessly! If you're wondering what Slingr is, then look no further. "
lead: "Welcome to Slingr - the ultimate platform to create cloud apps that integrate with other SaaS solutions seamlessly! If you're wondering what Slingr is, then look no further. "
date: 2020-10-06T08:48:57+00:00
lastmod: 2020-10-06T08:48:57+00:00
draft: false
images: []
menu:
  docs:
    parent: "prologue"
weight: 100
toc: true
---

The best way to learn how to use Slingr is to build something. Luckily for you,
we have made some tutorials to help you get started. In these tutorials, we won’t
go through all the features of the platform. The goal is that you get a general
idea of how it works and then you can start building something great by yourself.



{{< callout type="default" contend="" >}}
The best way to learn how to use Slingr is to build something.
{{< /callout >}}


{{< callout type="warning" >}}
The best way to learn how to use Slingr is to build something.
{{< /callout >}}


{{< callout type="danger" >}}
The best way to learn how to use Slingr is to build something.
{{< /callout >}}


{{< callout type="success" >}}
The best way to learn how to use Slingr is to build something.
{{< /callout >}}


In this example, the type parameter is set to "warning", which will be used in the bs-callout class to add styling to the callout. The content inside the callout tags will be inserted into the {{ .Inner }} variable in the callout.html shortcode template file, and then the entire result will be inserted into the final output HTML file.


{{< alert context="success" icon="✅">}}
This is a success message.
{{< /alert >}}

{{< alert context="info" icon="ℹ️">}}
This is a success message.
{{< /alert >}}


### Available tutorials

- `Working with Event Planner`: In this tutorial we are going to make some improvements to the Event Planner App. The estimated time of completion is 15 minutes. Go to the [tutorial]({{site.baseurl}}/working-with-event-planner-section-1.html).

- `Task Manager App`: In this app, users will be able to create tasks, assign them to other users, move them through different columns and send notifications to Slack channels. The estimated time of completion is 40 minutes. Go to the [tutorial]({{site.baseurl}}/task-manager-section-1.html).

If you just want to see the resulting apps, we have made them available as templates. So you only need to create an app [here](https://developer-portal.slingrs.io/#apps/create) and select the app that you want as a template. Keep in mind, that if you start the Task Manager App from a template, you will need to configure the Slack integration as explained in the section [Integration with Slack]({{site.baseurl}}/task-manager-section-10.html) of the Task Manager tutorial.
{{< details "Why Node.js?" >}}
