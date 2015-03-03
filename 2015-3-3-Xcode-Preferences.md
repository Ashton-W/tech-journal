---
layout: post
title: Xcode Preferences
---

The go-to fix for random build issues and bugs in **Xcode** is to delete the *DerivedData* directory.

The venerable *DerivedData* directory is the **Xcode** equivalent of the *build* directory from your *Makefile* days. Except, by default it is not relative to your project source. Instead, it is in a unique (as in UUID) location under `~/Library/Developer/`.

~~why build is better~~

So let's change that default and take our *build* back.


!(Xcode Preferences Window Locations)[{{ site.url }}/assets/xcode-preferences-locations.png]

!(Xcode Preferences Window Locations Advanced)[{{ site.url }}/assets/xcode-preferences-locations-advanced.png]

:thumps-up:
