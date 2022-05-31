---
layout: post
title: "SSL Certificates, More SSL Certificates, and Javascript in Rails 7"
date: 2022-06-02 09:30
categories: upcoming
---

## Meta:

- Location: [Zoom](https://z.umn.edu/cpmstream)
- Day: Thursday, June 2
- Time: 9:30

## Agenda:

- 9:30 - 9:35 Introductions
- 9:35 - 9:55 Using Certbot on All The Hosts!
- 9:55 - 10:30 Certificate Management at the U with InCommon
- 10:30 - 10:50 Rails 7: Import Maps vs JS Bundling
- Lightning Talks
  -   - _Bring Your Own!_

## Talk Descriptions:

### Using Certbot on All The Hosts! - Matt Zaske

A 100-200 level sort of overview of using Certbot to automate SSL cert management. The basics of how to get/install Certbot, how to use it (generally speaking) to request/renew/manage/delete/revoke certs, using it with the LetsEncrypt CA, using it with the UMN Sectigo/InCommon CA, using it across platforms (Linux/Windows) and in some fun "third-party" configs, and where it doesn't fit well.

### Certificate Management at the U with InCommon - Peter Bajurny

Overview of our "reimagining" of certificate services at the U:
* Learn about delegating certificate services to local IT
* See a quick demo of the Certificate Manager UI
* See the community repository of certificate automations, and see how to contribute

### Rails 7: Import Maps vs JS Bundling - Joe Thor

A primer on new options in Rails 7 for handling the JavaScript ecosystem. Specifically, looking into Import Maps + Hotwire and JS Bundling

