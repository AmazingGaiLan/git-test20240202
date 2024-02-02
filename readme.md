How to use it?
Using the Table menu set the desired size of the table.
Enter the table data into the table:
select and copy (Ctrl+C) a table from the spreadsheet (e.g. Google Docs, LibreOffice Calc, webpage) and paste it into our editor -- click a cell and press Ctrl+V
or just double click any cell to start editing it's contents -- Tab and Arrow keys can be used to navigate table cells
Adjust text alignment and table borders using the options from the menu and using the toolbar buttons -- formatting is applied to all the selected cells.
Click "Generate" button to see the generated table -- select it and copy to your document.
Markdown tables support
As the official Markdown documentation states, Markdown does not provide any special syntax for tables. Instead it uses HTML <table> syntax. But there exist Markdown syntax extensions which provide additional syntax for creating simple tables.

One of the most popular is Markdown Here — an extension for popular browsers which allows you to easily prepare good-looking e-mails using Markdown syntax.

Similar table syntax is used in the Github Flavored Markdown, in short GFM tables.

Example
GFM Markdown table syntax is quite simple. It does not allow row or cell spanning as well as putting multi-line text in a cell. The first row is always the header followed by an extra line with dashes "-" and optional colons ":" for forcing column alignment.

| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |
    