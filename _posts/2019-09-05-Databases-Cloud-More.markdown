---
layout: post
title: "Databases, OIT - Cloud Enablement,  "
date: 2019-09-05 09:30
categories: upcoming
---

## Meta:

- Location: [Walter Library](http://campusmaps.umn.edu/walter-library), Room 402 and on [Zoom](https://z.umn.edu/cpmstream)
- Day: Thursday, Sept 5
- Time: 9:30 - 11:00

## Agenda:

- 9:30 - Introductions
- 9:35 - 9:50 [Database Performance Series](#database-performance-series), Andy Wattenhofer
- 9:50 - 10:00 [Background Async Tasks in Ansible](#background-async-tasks-in-ansible), Michael Berkowski
- 10:00 - 10:10 Break
- 10:10 - 10:30 [OIT - Cloud enablement](#oit-cloud-enablement), Kyle Weeks
- 10:30 - 11:00 Lightning talks
  - Harmful software installations
  - Campus Codefest projects
  - _Bring your own_

As always, join us after the meeting for lunch!

## Talk Descriptions:

### OIT - Cloud enablement
Kyle Weeks - OIT

> There is a new group of staff within OIT that is working to stand up new services around cloud enablement, and will be engaging this group to discuss what this might look like. Will be providing a brief overview of the envisioned services, and talk through how this may impact the University.

### Database Performance Series
Andy Wattenhofer - OIT

> Database table column order: performance considerations

### Background Async Tasks in Ansible
Michael Berkowski - University Libraries

> Ansible's typical behavior is to run all deployment tasks sequentially, only beginning a task when the prior task has completed successfully. Long running jobs such as invoking a compiler will hold everything else up until they've finished, even if future tasks don't require depend on their results. Ansible can push long running tasks to the background and poll them for their completion, drastically reducing running times.
