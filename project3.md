[Back to Portfolio](./)

The Magic Number
===============

-   **Class:** CSCI 301 - Survey of Scripting Languages
-   **Grade:** A
-   **Language(s):** Perl
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The HTML Parser & Web Crawler program, as its name would indicate, parses webpages in order to determine if the HTML contained within each file is proper and balanced, i.e., each tag is valid markup and begins and ends at the same depth. If so, the page is crawled, identifying the number of unique, valid links that can be visited, which likewise, are then parsed and crawled in a recursive manner. This program was designed to be light-weight, taking advantage of the stack and queue data structures’ efficiency.

## How to run the program

```bash
cd ./MagicNumber
chmod u+x magic.pl 
./magic.pl
```

## UI Design

This program accepts either a single HTML page or multiple files as its parameter(s). The directory ‘pages’ contains sample webpages that will be used for demonstration, though any file could be analyzed. Note that parsing and crawling live webpages/websites is out of scope and therefore untested. Let’s begin with one local input; I’ve listed the contents of the ‘pages’ directory and run the program solely specifying the file ‘pages/index.html’ (Fig. 1). The result is that the page is in fact balanced, but cannot visit any other pages. This can be confirmed by viewing the HTML of this simple file directly (Fig. 2). 

![screenshot](images/p2f1.jpg)  
*Figure 1. A listing of sample HTML pages; program output with 'pages/index.html' as a parameter.*

## Additional Considerations

Minimum requirements: Perl 5 (v5.30.0)
```bash
sudo apt update
sudo apt-get install perl
```

[Back to Portfolio](./)
