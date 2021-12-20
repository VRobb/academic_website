---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "CPSC 3600 - Network Programming (taught in Fall)"
summary: "This course introduces students to the fundamental concepts of computer networks and network programming. We will cover network programming using sockets, layered network architectures, key application protocols, and how to implement reliable transfer protocols so as to ensure that network traffic arrives at its intended destination without corruption. We will also briefly look at each of the layers of the Internet protocol stack, and (time permitting) discuss some basic network security principles. Students are expected to have prior programming experience."
authors: []
tags: []
categories: []
date: 2021-10-05T10:24:33-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

weight: 20
---

This course introduces students to the fundamental concepts of computer networks and network programming. The material is structured around the five layers of the Internet's protocol stack. Each of these layers provides different services to the network:

1.  The **Application layer** supports communication between applications running on different end systems (e.g. web browsers, computer games, etc)

2.  The **Transport layer** marshals messages from the application layer and divides them up into *packets* that can be sent to other machines through *sockets*. Protocols running in the Transport layer may also provide other services, like reliable delivery guarantees.

3.  The **Network layer** accepts packets from the Transport layer and is responsible for routing them through the interconnected machines that compose the Internet until they reach their intended destination.

4.  The **Link layer** is responsible for communication over specific links connecting neighboring machines as well as machines interconnected through a Local Area Network.

5.  The **Physical layer** handles converting digital information into a form that can actually be transmitted across the links that connect machines, including copper wire, fiber optic cable, and radio waves.

We will also briefly discuss topics pertaining to network security.

### Course Projects
While much of the information covered in the class is conceptual (i.e. we won't directly be translating it to code), we will focus in on several topics that will help prepare students for developing their own networked applications. Course projects will be developed using Python, however, students are not required to have prior experience programming in Python (prior experience with other programming languages, such as C++ or Java, is expected). Examples of potential course projects include:

1. Implementing a reliable data transfer protocol 

2. Creating a packet sniffer

3. Developing a distributed P2P chat system