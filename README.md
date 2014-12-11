rr-automation
=============

Resources for automation tutorials

## Functionalize/Modularize functions

Go through exercise of transforming scripts into functions

Take the code out of the Rmarkdown file into several files:
- knitr file: manuscript + chunks that run functions
- all R functions in the `code/` folder



## Let's build R scripts that simulate the make process

`make_clean_data()` removes all the data files generated by the data analysis
process.

`make_clean_manuscript()` removes `.pdf`, `.html`,  and `.md` files.

`make_clean_figures()` removes all the figures.

`make_clean()` does the 3 above.

Activity: give them a script that does the cleaning of the data for instance
(the `make_clean_data()`), and have them use it as a template to create the
other functions.

## Intro to make

Motivates by only rebuilding based on the files that have changed. Only based on
timestamp (when the file was modified, not on content)

Works best if you have good file/data organization, so the change in the raw
files only propagates to the relevant targets.

Only a demonstration, provide participants with ready to use Makefile

Make sure that participants with Windows will be able to run them.


## Resources

- Karl's Broman [introduction to GNU Make](http://kbroman.org/minimal_make/).
- Software Carpentry [Make lesson](http://software-carpentry.org/v4/make/index.html)
