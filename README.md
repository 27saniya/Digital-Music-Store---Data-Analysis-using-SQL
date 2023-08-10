# Data Analysis using SQL for Digital Music Store

The aim of this project is to analyze the Chinook Database, which encapsulates information about a music store's media, customers, employees, and invoices.
Using SQL queries, various facets of the store's operationswill be interpreted, extracting key insights from sales patterns, customer preferences, and employee performance.
This detailed analysis will provide a comprehensive understanding of the store's dynamics and potential areas of growth or improvement.

The schema of the Chinook Database is as shown below:


<img width="652" alt="001" src="https://github.com/27saniya/Digital-Music-Store---Data-Analysis-using-SQL/assets/101293878/f12663ae-ed03-4a7c-996f-6a8c12ad9f4a">
<br>

There are 11 tables in the chinook sample database.

- employees table stores employees data such as employee id, last name, first name, etc. It also has a field named ReportsTo to specify who reports to whom.
- customers table stores customers data.
- invoices & invoice_items tables: these two tables store invoice data. The invoices table stores invoice header data and the invoice_items table stores the invoice line items data.
- artists table stores artists data. It is a simple table that contains only the artist id and name.
- albums table stores data about a list of tracks. Each album belongs to one artist. However, one artist may have multiple albums.
- media_types table stores media types such as MPEG audio and AAC audio files.
- genres table stores music types such as rock, jazz, metal, etc.
- tracks table stores the data of songs. Each track belongs to one album.
- playlists & playlist_track tables: playlists table store data about playlists. Each playlist contains a list of tracks. Each - track may belong to multiple playlists. The relationship between the playlists table and tracks table is many-to-many. The playlist_track table is used to reflect this relationship.


Setting up the Database:

- Firstly, the database file is downloaded from: https://www.sqlitetutorial.net/wp-content/uploads/2018/03/chinook.zip
- The database file is unzipped and stored in the folder
- A connection is established to the Chinook SQLite database file, allowing subsequent SQL queries to be executed on it using the Jupyter notebook.

