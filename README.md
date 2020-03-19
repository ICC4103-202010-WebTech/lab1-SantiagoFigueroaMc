# HTML analysis.
###### Lab 1. www.news.ycmbinator.com
###### Santiago Figueroa Mc Intyre.

---
## How is the list of news articles structured with HTML?
The list of articles are arranged in a table, witch is in the body of 
the html document. This table is placed in the center of page.

## Briefly describe what you see in the files with names starting with hn.js and news.css.
The hn.js file has function definitions and event listeners that are called
(not exclusively) when the user interacts with the page.

In the other file, news.css, we can find color definitions, fonts and styles
to be used by the page when loaded.

## How are these files different?
The css file are "instructions" for the artist that every browser carries 
inside, and the js file is the action plan to be executed if the user does 
something.

## What is their purpose?
This files organize and shape the website stile and behavior, they are
responsible to show the info properly to the user.

## How many request has it taken for the browser to download the Hacker News main page?
It needed 7 requests for 7 different files.

## What are the HTTP request methods in each case?
| File name | Methods |
| --------: | ------: |
| news.ycombinator.com | GET |
| news.css | GET | 
| y18.gif | GET |
| s.gif | GET |
| hn.js | GET |
| grayarrow.gif | GET |
| favicon.ico | GET | 

## What kind of web server is used for this website?
The server used is nginx.