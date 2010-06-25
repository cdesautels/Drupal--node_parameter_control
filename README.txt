README.txt
==========

This module disables the various core paramemters on node add/edit pages. It started out as a way of removing the "publishing options" from the node admin screen. I've always thought that the lack of a separate permission for "publishing" to be one of Drupal's blind spots. So I divised this approach for clients who want to have an editor role who can create and edit content but not publish them and didn't want or need some complicated workflow process. So I set the default state for new nodes as "unpublished" and disable the "publishing controls" for all but select roles. A last step is to provide a view of unpublished nodes, so editors can easily locate them.

I've also used this module to disable the "log message" and "authoring information" parameters as well. I have found that most non-developer users of Drupal are overwhelmed by the admin interface and typically use only a small percentage of it. So I do everything I can to simplify it for them. If there's no demonstrated need for something, I prefer to simply remove it.

This module is by no means meant as an alternative to Access Control. You should first try to accomplish your needs there and only resort to this module for special cases.

In the interest of thoroughness, I've made this module capable of disabling all the parameters except the title. Admittedly, I can't think of a circumstance where someone would want to remove one of the other parameters with this module instead of with access control, but I've always found that the moment you assume you're never going to need something, a need arises.



AUTHOR/MAINTAINER
======================
Chris Desautels
chris at kokikai DOT org