---
description: We have APIs!
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
---

# API

We have APIs! The front end of the platform has absolutely no real logic, and indeed, drives everything from authenticated API's.&#x20;

Once you are authenticated, your authentication token is used by the API layer seamlessly to ensure you only get your data back; this same approach can be used to call into the API layer by your own code if you so wished, using exactly the same APIs we are using to drive the frontend.

We have two APIs - one for general management of your account, connectors, etc and one for creating your posts; you will find them detailed on these pages.

{% hint style="warning" %}
These APIs are currently under heavy development, and are referencing our dev site! As such, take EVERYTHING here with a pinch of salt!
{% endhint %}
