# Rearrange Names

This is a simple web page that takes a list of names from the query string and displays them in a list. The names can be rearranged in a random order either by clicking a button or by reloading the page.

## How to Use

1. **Provide the names**: Add your list of names to the query string of the URL. For example, if your names are "Alice", "Bob", and "Charlie", your URL might look like this: `http://yourwebsite.com?names=Alice,Bob,Charlie`.

2. **View the names**: When you load the page, the names you provided will be displayed in a list. The order of the names is randomized each time the page is loaded.

3. **Rearrange the names**: If you want to rearrange the names again, you can click the "Rearrange the names" button. This will randomly rearrange the names and update the list.

## How It Works

The code uses the `URLSearchParams` interface to parse the query string of the URL and get the list of names. It then creates an HTML list and adds each name as a list item.

A function called `rearrangeNames` is defined to rearrange the names in a random order and update the HTML list. This function is called when the "Rearrange the names" button is clicked and also when the page is loaded.

## Note

This code uses the `Math.random()` function to rearrange the names, which means the order is not truly random, but it should be sufficient for most purposes. If you need a more truly random order, you may want to consider using a different method to shuffle the array of names.
