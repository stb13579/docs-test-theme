---
title: Sōzu 1.0.6 is available and deployed, with new 4xx/5xx custom error pages
date: 2025-01-06
tags:
  - sozu
authors:
  - name: David Legrand
    link: https://github.com/davlgd
    image: https://github.com/davlgd.png?size=40
  - name: Florentin Dubois
    link: https://github.com/FlorentinDUBOIS
    image: https://github.com/FlorentinDUBOIS.png?size=40
description: Next to come, HTTP/2!
excludeSearch: true
---

[Sōzu](https://www.sozu.io) 1.0.6 is now available and deployed on all our shared and dedicated load balancers. It comes with a fix for a TLS bug we encountered with [Metabase](/developers/doc/addons/metabase) instances in some cases. We've also overhauled the custom pages for 4xx and 5xx errors. They now display a better designed and more detailed message.

* Learn more about [Sōzu new releases](https://github.com/sozu-proxy/sozu/releases) {{< icon "github" >}}