---
title: "PhoenixC2 - A C2 Framework for Red Teams - First Release"
date: 2023-04-06T17:35:14+02:00
draft: false
---
<!-- this is a blog post -->

# PhoenixC2 - A C2 Framework for Red Teams

## Introduction
![Preview](/images/phoenixc2/web-interface.png)
PhoenixC2 is a free & open source C2 framework for Red Teams. It is written in Python3 
and uses for it's REST API. It is designed to be easy to use and easy to extend.
This is the **first** release of PhoenixC2, so there are still many features missing.

## Features
- [x] Modern Web-Interface
- [x] Built for Teams and Organizations (Multi-User)
- [x] Customizable (Plugins, Modules, Kits)
- [x] Easy to use
- [x] Easy to extend
- [x] Supports different languages (Python, Go, ...)

## Inspiration
When I started to learn about penetration testing and red teaming, I did not know, what Command&Control Frameworks were.
My Idea was to create a tool, which would allow me to control exploited servers, using a simple tcp connection and one main listener.

After about a week, I stumbled upon [Empire](https://github.com/BC-Security/Empire), while learning on Tryhackme and I was amazed by it. 
The Empire Framework was a big inspiration for PhoenixC2, it's architecture and it's features.

I started working on this project, because it combined my two passions: Backend Development and Penetration Testing and I could learn a lot about both.


## Comparison to other C2 Frameworks
PhoenixC2 is not a replacement for other C2 Frameworks, it is just another tool for Red Teams.
I tried to make PhoenixC2 as easy to use as possible, but it is still in development and there are still many features and bug fixes missing.

## Development
When I started working on PhoenixC2, it was just a small tcp server and client, which would be able to send and receive commands. But after time and lots of rewriting, PhoenixC2 has grown into a full featured C2 Framework.
The process was not easy, but I learned a lot about backend development and I am very happy with the result.

I decided to open source PhoenixC2, because I think it is a good idea to share my work with the community and build a community around it.

## Future
I plan to implement several new features and improvements to PhoenixC2, with the ultimate goal of making it a valuable tool for professional Red Teams and hobbyists alike. 

## Usage
Using [Insomnia REST Client](https://insomnia.rest/) is the only way to use PhoenixC2 properly at the moment, because the Web-Interface is not finished yet. There is a [Collection](https://github.com/screamz2k/PhoenixC2/blob/main/insomnia.json) with all the requests in the root directory of the project.

## Contributing
Any type of contribution would mean a lot to me. You can contribute by reporting bugs, suggesting new features,creating pull requests, or improving the documentation. But please follow the [Contribution Guidelines](https://github.com/screamz2k/PhoenixC2/blob/main/.github/CONTRIBUTING.md).

As this is my first serious open source project, I am very happy to receive any kind of feedback.

## Links
- [Github](https://github.com/screamz2k/PhoenixC2)
- [Documentation](https://screamz2k.gitbook.io/phoenixc2/)

