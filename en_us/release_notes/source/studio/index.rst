####################################
edX Studio
####################################

******************
January 28, 2015
******************

* If you include cohorts in your course, you can now assign different course
  content to different cohorts. See `Cohorted Courseware Overview`_ for more
  details. 

* All courses created after January 14, 2015 now use the `key introspection
  API`_ format for internal course identifiers and the course URL. An example
  of the new URL format is:
  ``http://www.edx.org/courses/course-v1:edX+DemoX+Demo_2014/info``.

* MathJax, which Studio and the LMS use to render text as "beautiful math", is
  now upgraded to version 2.4 from version 2.2. For more information, see the
  descriptions of `MathJax 2.4`_ and `MathJax 2.3`_. (OSPR-21)

* When you create a new course in Studio, edit checks now identify special
  characters in the **Organization**, **Course Number**, or **Course Run**
  fields. An error message appears to prevent entry of spaces or characters
  such as !, ', (, or ). (SOL-233)

* For LTI components, you can now set the new **Accept grade past deadline**
  setting to True or False. Previously, grading always included learner
  submissions that were submitted after the subsection due date. (TNL-805)

================
Coming Soon
================

Course teams will soon have the ability to apply a Creative Commons license to
their course videos. Creative Commons licenses grant others the right to share
and use content. When learners view a video, they will be able to see the type
of license that it has.

*****************
January 14, 2015
*****************

When you made multiple attempts to log in to edX Studio with the wrong
password, the error message was not refreshed and there was no indication of
the problem on subsequent attempts. This problem is resolved. (TNL-140)

***************
January 8, 2015
***************

* When a component with multiple parents had a draft version, you received an
  error when trying to export the course. This problem is resolved. (PLAT-332)

* You can now use a new advanced setting, ``always_cohort_inline_discussions``,
  to control whether content-specific discussion topics are unified or
  cohorted.  See `Make All Content-Specific Discussion Topics Unified by
  Default`_ for more information.

* The inline help for the **Discussion Topic Mapping** advanced setting is
  updated to note that discussion IDs must be unique. (TNL-752)

.. include:: ../links.rst