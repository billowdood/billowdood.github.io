---
layout: post
title: gitignore files in atom
---
A few days ago something weird happened to my text editor (atom): files in the gitignore
of my projects were not in the tree view. After some googling i found that there
is a checkbox in atom's core settings that hide these files so i checked the box
and voilà...nothing happened.

![vcs core settings]({{ site.url }}/assets/images/2015_03_15/vcs_core.png)

I was busy so i left it that way until today. I went on google and after
finding the same 'check the Exclude VCS Ignored Paths' solution i found that
there is another checkbox in the tree view package.

![vcs tree view settings]({{ site.url }}/assets/images/2015_03_15/vcs_tree_view.png)

After unchecking that box the files were shown once again. If you want more
information about this please read [this](https://github.com/atom/atom/issues/4203).
