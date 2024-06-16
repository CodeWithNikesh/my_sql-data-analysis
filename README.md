# my_sql-data-analysis

/* .Q1 List all albums along with their artists. */
<span style="color: blue;">This is blue text</span>

SELECT album.title, artist.name
FROM album
INNER JOIN
artist ON album.artist_id = artist.artist_id;

