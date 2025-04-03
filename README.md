# html-week-2

<!DOCTYPE html>
<html>
<head>
    <title>Week 2 Assignment</title>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My Multimedia Webpage</h1>
    </header>

    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#multimedia">Multimedia</a></li>
            <li><a href="#registration">Registration Form</a></li>
            <li><a href="#table">Table</a></li>
            <li><a href="#list">List</a></li>
        </ul>
    </nav>

    <!-- Multimedia Section -->
    <section id="multimedia">
        <h2>Multimedia Elements</h2>
        <p>Enjoy this video and audio sample:</p>
        
        <!-- Video Element -->
        <video width="320" height="240" controls>
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>

        <!-- Audio Element -->
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </section>

    <!-- Registration Form -->
    <section id="registration">
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required minlength="6">
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            
            <input type="submit" value="Register">
        </form>
    </section>

    <!-- Image -->
    <section>
        <h2>Embedded Image</h2>
        <img src="image.jpg" alt="Sample Image" width="300">
    </section>

    <!-- Table -->
    <section id="table">
        <h2>Sample Table</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Age</th>
                <th>Country</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>25</td>
                <td>USA</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>30</td>
                <td>UK</td>
            </tr>
        </table>
    </section>

    <!-- List -->
    <section id="list">
        <h2>My Favorite Programming Languages</h2>
        <ul>
            <li>JavaScript</li>
            <li>Python</li>
            <li>HTML & CSS</li>
            <li>Java</li>
        </ul>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 My Multimedia Page</p>
    </footer>

</body>
</html>
