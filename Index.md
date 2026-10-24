
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Registration Form</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Student Registration Portal</h1>
        <p>Please fill out the form below to register for the upcoming semester.</p>
    </header>

    <main>
        <!-- Student Registration Form -->
        <form action="#" method="POST">
            
            <!-- Full Name Field -->
            <div>
                <label for="fullname">Full Name:</label><br>
                <input type="text" id="fullname" name="fullname" placeholder="e.g., Alex Johnson" required>
            </div>

            <br>

            <!-- Email Field -->
            <div>
                <label for="email">Email Address:</label><br>
                <input type="email" id="email" name="email" placeholder="e.g., alex.johnson@example.com" required>
            </div>

            <br>

            <!-- Password Field -->
            <div>
                <label for="password">Password:</label><br>
                <input type="password" id="password" name="password" placeholder="Enter a secure password" required>
            </div>

            <br>

            <!-- Phone Number Field -->
            <div>
                <label for="phone">Phone Number:</label><br>
                <input type="tel" id="phone" name="phone" placeholder="e.g., 555-0199" required>
            </div>

            <br>

            <!-- Age Field -->
            <div>
                <label for="age">Age:</label><br>
                <input type="number" id="age" name="age" min="16" max="100" required>
            </div>

            <br>

            <!-- Submit Button -->
            <div>
                <button type="submit">Register Student</button>
            </div>

        </form>
    </main>

</body>
</html>
