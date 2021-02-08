---
description: FAQ about local hosting
---

# Local hosting FAQ

## Why are my resources used a lot when the app is running?

The app has to run a server on your computer, which typically uses a lot of resources. This is why it is strongly recommended that you go back to your terminal and press Ctrl+C as this stops the server and therefore your resources stop being used.

## Does the local app run forever?

No. When you shut down your computer, the server is automatically stopped.

## Can I access the local app on other devices?

Yes. Services like [ngrok](https://ngrok.com) give you a URL that directly mirrors your `localhost` URL content. This URL can be accessed on other devices.

{% hint style="warning" %}
#### Important:

The URL will only work when the `localhost` server is running.
{% endhint %}

## What is the `localhost` URL?

The `localhost` URL is typically `localhost:50000`. If you already have something running on the `50000` port, stop it and then run SimpleEdit.

