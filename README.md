
<html lang="en">
<head>
    <title>Register here</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <form onsubmit="yourfunctionname()">
        <fieldset>
            <legend><h2>Registration Form</h2></legend>
            <label for="name" id="name"><b>Full Name: </b></label>
            <input type="text" id="name" size="40" placeholder="Enter your name" required>
                <br><br>
            <label for="email" id="email"><b>Email address: </b></label>
            <input type="email" id="email" size="40" placeholder="Enter your Email" required>
            <br><br>
            <label for="phone" id="phone"><b>Phone number: </b></label>
            <input type="text" id="phone" size="40" placeholder="+234 70 0000 0000" required>
                <br><br>
               
                <label for="gender" id="gender"><b>Select Gender: </b></label>
                <label for="male" id="male"><b>Male </b></label>
                <input type="radio" id="male" name="gender" required>
               
                <label for="female" id="male"><b>Female </b></label>
                <input type="radio" id="female" name="gender" required>
                <br><br>

                <label for="password" id="password"><b>Enter password: </b></label>
            <input type="password" id="password" size="40" placeholder="Enter your password" required>
                <br><br>
        
                    <input type="submit" value="submit" id="submit" name="submit">
        </fieldset>
    </form>

    <script>
        alert("You are welcome to my first task,");

        function yourfunctionname() {
            alert ("submitted successfully")
        }

    </script>
    <br>
    
</body>
</html>
