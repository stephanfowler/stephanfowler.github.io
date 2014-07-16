---
title: 'New Guardian navigation'
author: stephanfowleradmin
layout: post
permalink: /2014/07/guardian-navigation/
thumbnail: /assets/2014/07/nav.png
categories:
  - Uncategorized
---

I prototyped the navigation bar for the Guardian responsive beta site, which has now gone production. See the [very raw prototype](http://stephanfowler.com/nav-hack/index4.html?section=culture&sub=music) and the [final product](http://theguardian.com/uk). There's a writeup of the complete development process on the [Guardian Developer blog](http://www.theguardian.com/help/insideguardian/2014/jul/11/-sp-navigating-the-guardian).

This idea is this. The "all" link expands a full list of main sections, each with their subsections.  The default state of the nav is just the contextual row from the full list, moved up to the top of the (closed) list. The contextual subsection is moved in to the left; it also pulls its siblings leftwards, so you can click through all these subsections on a small screen without needing to expand the nav. On below-desktop viewports, the other main sections append to the current subsections and are reachable through a horizontal swipe.

