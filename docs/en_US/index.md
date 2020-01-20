---
layout: default
title: Index
lang: en_US
---

# Description

Plugin allowing Jeedom to act as a Gotify application that can send messages (notifications) to a Gotify server. You will find more details in <a href="https://gotify.net/docs/" target="_blank">Gotify's documentation</a> .

The advantage of this system is that it can be self-hosted (a docker container is enough), your data remains in your possession.

# Installation

In order to use the plugin, you must download, install and activate it like any Jeedom plugin.

It is needed to already have a Gotify server setup, the installation will not be detailed here because it is very clearly explained on the site.

# Plugin configuration

In the configuration of the plugin it will be necessary to setup the URL of the Gotify server in the format:

```HTTP
http://yourdomain.com:32768
```

You can optionally configure a client token, this will allow Jeedom to view and delete messages on the server (otherwise it can only send).

# Device configuration

After creating new device, the usual options are available.
It will also be needed to setup the token of the application which you will have previously created in Gotify (do not mix with the client token).
So one Jeedom device matches one Gotify application.

# Changelog

[See the changelog](./changelog)

# Support

If despite this documentation and after having read the topics related to the plugin on [community]({{site.forum}}) you do not find an answer to your question, do not hesitate to create a new topic with the tag of the plugin ({{site.tagPlugin}}).
