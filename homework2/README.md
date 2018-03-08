TSPDT dataset<br>
=======
Data source<br>
-------
This dataset contains TSPDT's LIST OF THE 1,000 GREATEST FILMS OF ALL TIME 2018 VERSION.<br>

Starting page: http://www.theyshootpictures.com/gf1000.htm <br>

Data fields <br>
-------
* Movies - String. e.g. Vertigo
* Directors - String. e.g. Alfred Hitchcock
* ranking - Int. e.g. 1000

Data Volume<br>
-------
1000 rows (movies)<br>

License<br>
-------
CC 4.0

Notes<br>
-------
* Use if to remove the Nonetype data so that you can use the text function.
* Use if to find the data when there is some error in the webpage.<br>
like in my case, all directors should be in 'span',attrs={'style':'font-size:24px; '}), but there are two from attrs={'style':'font-size:22px; '})
