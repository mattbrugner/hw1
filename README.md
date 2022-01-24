# ENTR-451 Homework Assignment #1

In this assignment, you'll be building the domain model, database structure, and data for "KMDB" (the Kellogg Movie Database). The end product will be a report that prints the movies and the top-billed cast for each movie in the database.

### Getting Started

- Use this template to create a new GitHub repository (click *Use this template* at the top of this page); be sure that the new repository in your account is named `hw1`
- Open the new repository (the one in your GitHub account – it should be called `_Your GitHub Username_/hw1`) in Gitpod. 
- Create a new SQLite database by typing `sqlite3 kmdb.sqlite3`
- Complete the assignment per the detailed instructions found in the comments of `kmdb.sql`, executing the script by using the `.read kmdb.sql` command.
- Commit and sync often! When complete, ensure that your most up-to-date, finished work lives in your GitHub repository, then, submit the URL to your GitHub repository page – i.e. `https://github.com/_Your GitHub Username_/hw1`

INSERT INTO movies (title, year, mpaa_rating, director) 
VALUES ("Batman Begins", "2005", "PG-13", "Christopher Nolan"),
("The Dark Knight", "2008", "PG-13", "Christopher Nolan"),
("The Dark Knight Rises", "2012", "PG-13", "Christopher Nolan");

INSERT INTO casts (id_movies, name, role) 
VALUES ("1","Christian Bale","Bruce Wayne"),
VALUES ("1","Michael Caine","Alfred"),
VALUES ("1","Liam Neeson","Ra's Al Ghul"),
VALUES ("1","Katie Holmes","Rachel Dawes"),
VALUES ("1","Gary Oldman","Commissioner Gordon"),
VALUES ("2","Christian Bale","Bruce Wayne"),
VALUES ("2","Heath Ledger","Joker"),
VALUES ("2","Aaron Eckhart","Harvey Dent"),
VALUES ("2","Michael Caine","Alfred"),
VALUES ("2","Maggie Gyllenhaal","Rachel Dawes"),
VALUES ("3","Christian Bale","Bruce Wayne"),
VALUES ("3","Gary Oldman","Commissioner Gordon"),
VALUES ("3","Tom Hardy","Bane"),
VALUES ("3","Joseph Gordon-Levitt","John Blake"),
VALUES ("3","Anne Hathaway","Selina Kyle");