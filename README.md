# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Elements Demo</title>
</head>
<body>
    <header>
        <h1>HTML5 Elements Implementation</h1>
    </header>
    
    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>External Image</h2>
        <img src="https://www.pexels.com/photo/example-image.jpg" alt="Beautiful scenery from Pexels" width="600">
    </section>

    <!-- Contacts Table -->
    <section>
        <h2>Contacts Table</h2>
        <table border="1">
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
                    <td>John Doe</td>
                    <td>123 Main St, NY</td>
                    <td>+1234567890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Oak Ave, CA</td>
                    <td>+0987654321</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Michael Brown</td>
                    <td>789 Pine Rd, TX</td>
                    <td>+1122334455</td>
                    <td>michael@example.com</td>
                </tr>
                <tr>
                    <td>Emily White</td>
                    <td>101 Maple Ln, FL</td>
                    <td>+5566778899</td>
                    <td>emily@example.com</td>
                </tr>
                <tr>
                    <td>Chris Green</td>
                    <td>202 Elm St, WA</td>
                    <td>+6677889900</td>
                    <td>chris@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            <br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            <br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">
            <br><br>
            
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required>
            <br><br>
            
            <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required> Male
            <input type="radio" id="female" name="gender" value="female" required> Female
            <input type="radio" id="other" name="gender" value="other" required> Other
            <br><br>
            
            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select a country</option>
                <option value="us">United States</option>
                <option value="uk">United Kingdom</option>
                <option value="ca">Canada</option>
                <option value="au">Australia</option>
            </select>
            <br><br>
            
            <label>Interests:</label>
            <input type="checkbox" name="interests" value="coding"> Coding
            <input type="checkbox" name="interests" value="music"> Music
            <input type="checkbox" name="interests" value="sports"> Sports
            <br><br>
            
            <input type="submit" value="Register">
        </form>
    </section>

    <!-- Multimedia Elements -->
    <section>
        <h2>Multimedia</h2>
        
        <h3>Audio</h3>
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
        
        <h3>Video</h3>
        <video width="600" controls>
            <source src="video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>
</body>
</html>
