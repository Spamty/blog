---
layout: post
title:  "YOURLS' API for 3q3.de"
date:   2016-07-17 17:11:00 +0000
category: developer
# Spamty Blog (https://blog.spamty.eu/)
# Copyright (C) 2016 by Philipp & Spamty.eu
---
The API for our [URL shortener 3q3.de](http://3q3.de/) has changed. 
You can now access directly the API from YOURLS (the software we are running for the URL shortener).

The API URL has changed to:
```
https://3q3.de/yourls-api.php
````

Furthermore you have to authorize with signature token and timestamp that can be [requested via email](https://dev.spamty.eu/apikeys/). See [YOURLS passwordless API](https://github.com/YOURLS/YOURLS/wiki/PasswordlessAPI#usage-of-a-time-limited-signature-token).

Refer to [our docs](https://dev.spamty.eu/shorturlcreate/) and the official [YOURLS documentation](http://yourls.org/#API). We have changed a few things with the API so you should stick to our docs whenever possible.
