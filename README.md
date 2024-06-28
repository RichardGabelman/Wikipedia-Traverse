# Wikipedia-Traverse
This is a project I made for the Algorithms class I took in college.
This program attempts to find a path between two Wikipedia articles
utilizing only links found on the current page. 

Usage:
startURL: https://en.wikipedia.org/wiki/XXXXX
targetURL: https://en.wikipedia.org/wiki/YYYYY
limit: optional int var that limits how many pages the program will search
Returns 1 if a path is found, 0 if not
wikiTraverse(startURL, targetURL, limit)