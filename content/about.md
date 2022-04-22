---
title: "About"
date: 2020-09-15T11:30:03+00:00
# weight: 1
# aliases: ["/first"]
#tags: ["about"]
author: "Daniel Gorbe"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: true
comments: false
#description: "Desc Text."
canonicalURL: "https://elmasy.com/about"
disableHLJS: false # to disable highlightjs
disableShare: true
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
#cover:
#    image: "<image path/url>" # image path/url
#    alt: "<alt text>" # alt text
#    caption: "<text>" # display caption under cover
#    relative: false # when using page bundles set this to true
#    hidden: true # only hide on current single page
#editPost:
#    URL: "https://github.com/<path_to_repo>/content"
#    Text: "Suggest Changes" # edit text
#    appendFilePath: true # to append file path to Edit link
---

# Intro 

Elmasy is an attack surface management tool.
Discover and assess as many as possible publicly accessible assets from a domain name.

This project has 3 goals:

1. To provide a website for non-professionals/professionals to check the attack surfaces of publicly accessible assets.
2. To provide an API for professionals to work with easily.
    - The website will use the same API as your service.
3. To provide a wide range of libraries for professionals to work with without relying on external services.
    - The API will use the same library as you.

As we grow, we will know more protocols, more services and assess/evaluate as fast as the programming language allows.
The project is starts from lower layers (like TCP and UDP), basic services (like web servers) and gathering basic information about the servers (like TLS ciphers).

Firstly, our target audiences are the SMBs (small and medium sized businesses).

---

# The problem

SMBs have a serious IT security problems. That's a fact.

If you are care about the security, you are still depend on SMBs that don't.

---

# The process

After you give a domain, Elmasy starts to discovery servers, assess the service, evaluate the result and give a score to the domain.

The score is publicly accessible to anyone, without registration. The main goal in this is to allow to check not just your own domain, but your supply chain's.

The details will be available to registered users *after some time*.

---

# Security

There are two important term: **blacklist** and **responsible disclosure**.

## Blacklist

Anyone can ask to include a domain on the blacklist. Just need to prove the domain ownership.

## Responsible disclosure

As we said, any registered user can view the details after some time. The time will be negotiable. There will be a default time, but one can ask for more.

---

# Use cases

- Assess your IT infrastructure
- Assess your subcontractor's infrastructure

## Other, non trivial

- Investing: the numbers are awesome, but a rotting IT system can be a sign of internal problems.