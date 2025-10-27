---
content_type: page
description: The study materials section contains supplementary notes for course text
  and additional topical notes.
learning_resource_types: []
ocw_type: CourseSection
title: Study Materials
uid: cdaac6d9-fa8d-0985-f397-e3cc20d29c21
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Python® Tutorial
----------------

Given the programming content of 20.180's [assignments](/courses/20-180-biological-engineering-programming-spring-2006/pages/assignments) and the [superb tutorials](/courses/20-180-biological-engineering-programming-spring-2006/pages/study-materials) composed by its TAs, the class is assumed to have some experience with Python®. So, rather than offer a purely introductory tutorial to programming + Python®, the 20.181 TAs offered a short refresher course during office hours after the first lecture session.

Python®+Emacs+Shell cheat sheet ({{% resource_link 3d539035-66ea-cbeb-484d-a95e3518af7d "PDF" %}})

If you still crave more Python® tutorials here is a {{% resource_link "60290e48-ffbd-4577-b942-d187508d9e36" "list of 300 Python® Tutorials" %}}. You may also find {{% resource_link "c8a019d5-3c0c-47aa-9a5f-5ff72e428993" "the official Python® documentation" %}} to be handy.

Refresher Course on Python®/Emacs/Shell: Five Different Ways to do The Fibonacci Sequence
-----------------------------------------------------------------------------------------

Code for 20.181 Refresher Course ({{% resource_link 2e4e198a-63c5-e65d-1096-8b7319fd7203 "ZIP" %}}) (The ZIP file contains: fib.txt, fib\_module.py, and fibonacci\_tutorial.py.)

Start with file fib\_module.py. This file defines a function called calc\_fib that we will use in method 1.

(In this class we will often start with a big code base that someone else has developed, and we will write some small part which utilizes this pre-existing code. When you are supposed to hijack others' code, you will be told to do so explicitly and the code will be provided to you. In all other cases, using code you found on the internets is not acceptable. So please don't.)

For this tutorial we'll be working on emacs. Emacs is like pico (which you used last term in 20.180), the text editor on MIT server, except with more functionality. But you can use whichever you're comfortable with. A few additional emacs tips:

*   cntl-Z to step out of emacs without killing it, then type "fg" (stands for foreground) to step back in.  
    your changes won't be lost when you do this, but if you want to run the new version of your file, cntl-x cntl-s to save the chances before stepping out.
*   emacs find and replace function
    *   M-% (alt-shift-5)
    *   you have to have your cursor at the top of the file
    *   space bar to accept change and keep finding
    *   more info on {{% resource_link "e2990110-971a-45e3-80ca-765e96fdf017" "find and replace" %}}

Python® code written during the refresher course, with some associated comments: OH1\_commentedcode.txt ({{% resource_link daa38fbe-1e77-0398-b32a-fc9a94d4aaa6 "TXT" %}})