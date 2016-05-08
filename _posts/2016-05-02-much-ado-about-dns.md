---
layout: post
title:  Much Ado About DNS
categories: dns, domains
---
Ever since I downgraded my [HostGator][hostgator] account, things have changed. With a basic package, I had access to changing DNS information. However, when I became a student last summer, I decided to build my personal site on [Github Pages][github-pages] to get rid of an extra expense. Since I purchased my domain through them, I just continued paying for it instead of transferring it somewhere else. I never considered the possibility of transferring the domain until I ran into a DNS issue.

When I decided to point my domain to my github.io page, there was no way for me to do this through HostGator's customer portal. It turns out that a downgrade only allowed me basic controls such as managing more than one domain, enabling privacy settings, and transferring domains. For all other issues, I needed to contact customer support. So in the case of pointing my domain, I asked someone from HostGator to do it but they directed it to the wrong IP. This was frustrating since it takes 24-48 hours for DNS changes to propogate which meant the issue remained unresolved during the weekend.

When I contacted GitHub's customer service about the issue, they spoke to me about how to set up the domain. They said that because I had an apex domain, I needed my DNS provider to point two IP addresses instead of one. When I contacted HostGator again explaining the situation, the person through live chat seemed more interested in debating semantics than in the information I forwarded to them from GitHub. However, in the case of this issue no live chat was able to replace the reassuring phone call that someone corrected the error.

After this occurrence, I talked to my developer friends who offered me domain host transferring options. I suppose in the long run it would be best for me to find an alternative that is less expensive and also provides me access to the HostGator domain features I lost.

[hostgator]: http://www.hostgator.com/
[github-pages]: https://pages.github.com/