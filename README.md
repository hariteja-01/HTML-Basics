# HTML-Basics
This repository shows basic concepts in HTML such as Head, Title, Body tags.
<!DOCTYPE html>
<html>
<head>
    <title>Online Ticket Booking</title>
</head>
<body>
    <h1>Online Ticket Booking</h1>
    <form action="/submit_ticket" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br>
        <label for="event">Event:</label><br>
        <select id="event" name="event">
            <option value="concert">Concert</option>
            <option value="movie">Movie</option>
            <option value="play">Play</option>
        </select><br>
        <label for="tickets">Number of Tickets:</label><br>
        <input type="number" id="tickets" name="tickets"><br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
