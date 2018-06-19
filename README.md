# Visited_Countries
Updated version of my old project which consisted basically of an HTML that used an SVG map to show which countries you had visited. I've added database support with an Sqlite3 to simplify things and two inputs to add/remove. Now there is no need to edit the source code, it can be done just by typing in the names of the countries (both inputs have JQuery's autocomplete).

The database gets updated with asynchronous AJAX requests, GET to list countries and POST to add/remove, so that there's no need to reload the page. Then, the php passes the countries data as JSON to javascript, which finally renders the page dynamically.

There could be infinitely possible improvements (especially concerning the UI) to the project, so I invite you to fork the repository!

## Usage

You just need to save both ```index.php``` and ```data.db``` in the same directory. Then, if you're using the app locally, run ```php -S localhost:port``` (replace port with any port available) in order to get it up and running. Finally, access the app in a browser typing ```localhost:port```.

## Screenshots

![Image](https://github.com/diego95root/Visited_Countries/blob/master/Images/screen0.png "First screenshot")

![Image](https://github.com/diego95root/Visited_Countries/blob/master/Images/screen1.png "Second screenshot")
