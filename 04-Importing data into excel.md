# Importing data into excel

Processing and cleaning the data is the third (I guess) step in the data analysis process and most commonly data analysts use a spread sheet tool like Microsoft Excel or Google Sheets to process and clean the data.

To start working with data in excel you'll need to import all of your data into it. If its a small amount then you just can type the data into excel manually and start working on it but if you are working with larger datasets then excel provides you the option to import all of your files at once and then start working.

Both Microsoft excel and Google sheets allow you to import data using the following methods:

- Excel files

- text files

- CSV files

- copying & pasting data

- dragging & dropping data

## Delimiters

In older versions of Microsoft Excel it was required that you had to go through a number of steps to load data and it was because it wanted to give you spreadsheet that had the correct data in the correct columns and rows.

You'd have to specify special characters, such as commas, tabs, or spaces to separate individual values. We call these special characters that act as separators *delimiters*. And even though modern spreadsheet programs have improved the process of loading data, they aren't always perfect.

Most of the data in excel is imported using comma-separated-values or CSV for short and the commas act as delimiters in this case and the commas are not part of the data they are just acting as delimiters.

> CSV files are the most common file type when it comes to external data that can be imported in an spreadsheet program.

Watch for numerical data that uses commas to separate thousands (like 25,000), or text data, such as customer comments. In these cases, use commas and other punctuation in a way that doesn't distort your data.

## Importing text files

When working with plain text files excel gives you two options either you can open the `.txt` file or you can import it.

By default all `.txt` files open in the preferred text editor on your operating system and not in excel. You can use excel to open the `.txt` file and select it which opens the

text import wizard.

The text import wizard will then show you a prompt asking if your data has delimiters and headers or not. In this context headers are the labels of each column that your data has.

Clicking on the next button will open a prompt that asks you which type of delimiter your data has. Commas are the most common ones but semicolons, tabs, and spaces are also used sometimes.

The final prompt shows you how your data will appear if anything isn't right go back and change it or click next and your data will be imported.

> Excel has blurred the lines between **Open** and **Import** to make it a seamless experience for the user.

You can also copy the `.txt` file and change the extension to `.csv` and excel will import it automatically without the import wizard.

# Other ways to import data

You can also just copy paste the data in the  `.txt` file in a single column and use the text-to-columns feature and a similar wizard like import wizard will open. Follow the prompts and your data will be in separate columns.

The *most* simplest method is just to open excel and dragging the `.xlsx` or `.xls` files into the open excel window. If there is more than one file excel will open each of them in their own workbook.