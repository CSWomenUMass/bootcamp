## Challenge Solutions

The goal of these snippets is to count the number of usernames in the participants file. There are a lot of ways to do this, but we have collected a few here. Please submit pull requests if you have a neat or interesting solution you'd like to add.

### break the problem into steps

    cat participants.md | grep " -" | wc -l

1. ``cat`` spits the data from ``participants.md`` onto ``stdout``
1. ``grep "- "`` selects only those lines with a markdown list element
1. ``wc -l`` counts the lines in the result

### I guess grep can do it by itself:

    grep " -" participants.md -c
    
``grep -c`` counts the lines of the result, and it accepts a list of files to search through.
