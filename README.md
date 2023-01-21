# RRG website

This site is built using Jekyll with the minimalmistakes theme.

#### Posts

To create a post, add a new file to the ```_posts``` directory with the following filename format:

YEAR-MONTH-DAY-title.md

Where YEAR is a four-digit number, MONTH and DAY are both two-digit numbers, for example the following filenames are valid.::

   2022-12-31-new-years-eve-is-awesome.md
   2023-01-21-GB3TD-Echolink.md

All blog post files must begin with a basic header in a block between two ```---``` delimeters::

```
   ---
   layout: post
   title:  "RRG Test Post Title"
   ---

   # Welcome to this post

   **This is bold**, and this is my first Jekyll blog post.

   I hope you like it!
```

#### Newsletters

These should be saved as PDF format with the naming correct naming scheme (example): ```2022_q4_newsletter.pdf```

Add PDF file to ```assets/pdf``` directory and edit the ```_pages/newsletter.md``` file to reference based on the existing formatting.  

#### Updating membership

Add/remove from the list contained in ```_pages/membership.md``` 
