---
layout: page
title: "DuckDNS"
description: "Automatically update your Duck DNS IP address."
date: 2017-04-30 13:28
sidebar: true
comments: false
sharing: true
footer: true
featured: true
---

[Duck DNS](https://duckdns.org/) is a free dynamic DNS service. Using this service you can have a custom domainname under duckdns.org point at your home computer.

```json
{
  "token": "sdfj-2131023-dslfjsd-12321",
  "domains": ["my-first-account.duckdns.org", "my-second-account.duckdns.org"]
}
```

Configuration variables:

- **token** (*Required*): Your Duck DNS API key.
- **domains** (*Required*): A list of domains to update DNS.
- **seconds** (*Optional*): Seconds between updates to Duck DNS.
