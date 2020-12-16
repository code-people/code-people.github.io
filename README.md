# Code-People website

First things first: this is a *PUBLIC* website. Don't put anything in this repo
that you don't want to share with the world. No FERPA or HIPAA violations, pretty please!

## Firing up a local server

1. Clone this repo `git clone git@github.com:code-people/code-people.github.io`
1. Inside the cloned directory, run `jekyll serve --watch` *or* `docker-compose up`
1. Point your browser to `http://localhost:4000`

The `--watch` flag tell Jekyll to watch files for changes. As you work with your content,
the generated site will stay in sync.

## Posts

To add a meeting, create a file in the `_posts` directory with the format
`YYYY-MM-DD-some-fancy-title-for-the-meeting.md`.

## YAML front matter

There are special fields at the top of the file that are used in the HTML
templates. Most of them are straight-forward.

### Presentation links

be used after a meeting/presentation to share any materials (like slides)
that the presenter wants to distribute.

### Categories

There are two categories that the templates will respond to: `upcoming` and
`meetings`. They do what you'd think; `upcoming` meetings appear in the
upcoming section and `meetings` is for stuff that has already happened.

Example front matter:

```YAML
---
layout: post
title:  "Cutting-edge PHP"
presenters: David Naughton
date:   2013-11-05 21:38:11
categories: meetings
presentation_links:
 - text: Some slides
   href: http:://www.google.com/
 - text: Cat pictures
   href: http:://www.google.com/
---
```
