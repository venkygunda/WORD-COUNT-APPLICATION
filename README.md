# WORD-COUNT-APPLICATION
This code is a simple word count application written in HTML and JavaScript. The code consists of an HTML page with a form and a table, and a JavaScript script that provides the functionality for the application.

Here is an explanation of the code:

1.The HTML page has a heading "Word Count Application" and an input field with the id "file-input", which is used to select a text file.

2.There is also a table with the id "word-count-table", which is used to display the word count results. The table has a header with two columns "Word" and "Count" and a body with the id "word-count-table-body".

3.The JavaScript script starts by selecting the elements from the HTML page using their id's, i.e. the file input field, the word count table, and the table body.

4.A change event listener is attached to the file input field, which is triggered when the user selects a file. The listener function first checks if a file is selected or not.

5.If a file is selected, a new FileReader object is created and its onload event listener is set to a function that will process the contents of the file.

6.The contents of the file are read as text and converted to lowercase, and then all non-alphanumeric characters are removed. The contents are then split into an array of words.

7.The script then creates an object called "wordCounts" and adds each word as a key with the number of occurrences as its value.

8.The top ten most frequent words are then sorted by their count and stored in an array called "topWords".

9.The table body is cleared and a new table row is created for each of the top ten words. The word and its count are inserted into the table as separate cells.

10.Finally, the word count table is displayed.

The code is simple but it provides a good example of how to work with files in JavaScript and how to manipulate the DOM.
