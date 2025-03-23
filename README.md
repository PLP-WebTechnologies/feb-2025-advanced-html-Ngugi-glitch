<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements</title>
</head>
<body>

    <h1>HTML5 Elements Example</h1>

    <h2>Ordered List</h2>
    <ol type="i">
        <li>Brian</li>
        <li>Tamika</li>
        <li>Travis</li>
        <li>Lucky</li>
        <li>Renoh</li>
    </ol>

    <h2>A good cat</h2>
    <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="A beautiful cat" width="500">

    <h2>Contacts Table</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>John Kamau</td>
                <td>123 Main St</td>
                <td>074567098</td>
                <td>johnkamau@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Njeri</td>
                <td>456 Oak Ave</td>
                <td>0796384356</td>
                <td>jane.smith@gmail.com</td>
            </tr>
            <tr>
                <td>David Lee</td>
                <td>789 Pine Ln</td>
                <td>0725345678</td>
                <td>david.lee@gmail.com</td>
            </tr>
            <tr>
                <td>Sarah Jones</td>
                <td>101 Elm Rd</td>
                <td>0767890456</td>
                <td>sarah.jones@gmail.com</td>
            </tr>
            <tr>
              <td>Michael Brown</td>
              <td>202 Maple Dr</td>
              <td>444-555-6666</td>
              <td>michael.brown@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <h2>Registration Form</h2>
    <form action="submit" method="post">
        <fieldset>
            <legend>User Registration</legend>

            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="8"><br><br>

            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>

            <label for="country">Country:</label><br>
            <select id="country" name="country">
                <option value="usa">USA</option>
                <option value="canada">Canada</option>
                <option value="uk">UK</option>
                <option value="australia">Australia</option>
            </select><br><br>

            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label><br>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br>
            <input type="radio" id="other" name="gender" value="other">
            <label for="other">Other</label><br><br>

            <p>Interests:</p>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label><br>
            <input type="checkbox" id="reading" name="interests" value="reading">
            <label for="reading">Reading</label><br><br>

            <input type="submit" value="Register">
        </fieldset>
    </form>

    <h2>Audio Example</h2>
    <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <h2>Video Example</h2>
    <video width="320" height="240" controls>
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</body>
</html>
