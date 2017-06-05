# IMDB-TO-MySQL

This is a script made in **Python** that allows you to download the The Plain Text Data Files from IMDB and import them into a MySQL database.

It is a interactive script (CLI) that runs from anywhere!


### What does it do?

  - It allows the user to choose between: Actors and actresses data files from IMDB.
  - Then downloads the file for the user.
  - Then uses [IMDB PARSER](https://github.com/sionide21/imdb-parser) by @sionide21 to get the Actors/Actresses names and writes it in a TXT file line by line.
  - It allows the user to connect to a remote/local MySQL database and a choose a table where to insert the rows.
  - Permits the selection of how many threads can the app use to insert the rows into the table, by default the script takes the maximum threads detected.
  - Starts the process (it takes a long time)


# Acknowledgements

  - Thanks to @sionide21 for his Ruby Script!
  - **A very big thank you to the person who has helped me in the process of doing this and always had a good word for me and my work!**
