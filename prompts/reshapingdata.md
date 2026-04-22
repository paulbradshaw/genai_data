# Reshaping data prompt

A common cleaning task in data analysis is reshaping from wide (e.g. pivot table) to long (with a column for each measure, e.g. year).

This is an example of a prompt for doing that:

```
Reshape this data from wide to long so that it fits into the following columns:

[SPECIFY THE COLUMNS, SEPARATED BY TAB OR PIPE OR COMMA ETC]
```

An example of specifying the columns might look like this:

```
Force /	Crime category /	Crime code /	Crime sub-category /	Outcome code	/ Outcome description /	Total /	Year from /	Year to	
```
