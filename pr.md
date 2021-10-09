
1. What did you like about this website?
    - The first things I noticed were that the color scheme was consistent and nice
    to look at. Additionally, the formatting between the different pages was
    consistent and easy to understand. The dropshadow on the boxes made them easy to
    to distinguish from the background.
    - for all reasonable viewport sizes the page adjusted well and was still perfectly
    readable. 
2. Describe one significant difference between your own P1 site and this person's. E.g.
    - This site seems to be focused for a business whereas my site is focused on an
    individual.
    a. Which has a better user experience (and why)?
        - I would say this site has a better user experience because its made for
        the general person. Everyone would be able to understand what is going on.
    b. Which codebase do you think would be more maintainable (and why)?
        - This site's codebase is well organized and looks to be easily expandable.
        This is good for maintainability. If you needed to add or remove information
        the site would remain formatted and styled well.
3. Is the code well-structured within files, and well-organized between files and directories?
    a. if not, suggest some specific improvements
        - The code is well organized, naming is consistent, files are in proper folders. I
        don't think anything needs to be changed. If you wanted to add something, I would
        suggest a readme for other developers to understand how your site is structured.
        Otherwise, flawless site.
4. Did you find any other issues? If so, briefly enumerate them.
    - When the site gets to about 525 width the images and text start to bleed out of their 
    boxes. Otherwise, no issues found.
    a. were semantically appropriate elements selected
        - Yes, as far as I can tell.
    b. is the CSS refactored to limit duplication?
        - Yes-ish, they appear to have used a seperate CSS file for each html page. I don't
        think this was entirely necessary as there isn't a lot of overlap of things
        being modified in different css files. (such as two different pages having different
        style for their h1 tags). I would advise putting all the CSS into one file and if
        a page needs different CSS for some specific tags, then you can make a seperate
        css file for that one. Alternatively, if its a small change a style tag in the html
        file might be sufficient if its only a small change.
5. Do you have any other constructive comments for the author?
    - This site is very clean and polished and the file structure is well done. I like it a
    lot. There is a small, what I would call a, bug. between a width of 1100 and 1000 pixels
    the nav-bar and page title shrink smaller than the width of the viewport. I assume this
    was done for mobile or small viewport viewers, and its definetly a good thing to have,
    I think the math is just off and it needs to be adjusted slightly so the nav bar always
    takes up the full viewport.
