# Join-Us

[Website Link](https://node-and-mysql2-sherry8838.c9users.io/) (Will lead to an error page when Cloud9 is not running)

Simple website that collects emails for a listserve. Uses SQL, Node, CSS, and HTML. 

On home page, user is shown "Enter your email to join __ others on our waitlist." The __ is a number that updates itself (increments by 1) each time a user signs up because it is added to the a table called "users" using SQL. The "users" table contains two columns: "emails", which records a new user's email, and "created_at", which is a default timestamp of when a new user joins. After signing up, a user is redirected to the home page. This was part of Colt Steele's Udemy course on SQL. 

app.js also contains two more page paths that a user can go to. One page generates a random number between 1 and 10, and the other page shows a joke.
