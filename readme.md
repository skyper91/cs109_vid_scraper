A main page has links to viewer pages, which nests either one video of the instructor or two videos, one of the instructor and one of the slides.


1. html of main site saved in "h1_main.txt"
2. extracts all viewer links as a list of tuples (name, date, link) to "list_add.txt"
3. manually parse to delete unwanted links, modify names.
4. go to every viewer and save html in "Vid HTMLS/xx.html"
5. Extract video link(s) and save in a dict with earlier tuple as key.
6. Finally, begin to save videos.

Modify prefix at point indicated to change save location.