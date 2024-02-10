# Lab-5

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form 1</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

 h2 {
            color: red;
            text-align: center;
            margin-bottom: 30px;
        }
        
 form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #fff;
            border: 2px solid blue;
            border-radius: 10px;
            padding: 30px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
            color: blue;
        }

 input[type="text"],
        input[type="email"],
        input[type="password"],
        input[type="number"],
        input[type="tel"],
        select,
        textarea {
            width: calc(100% - 12px);
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

select {
            width: 100%;
        }

textarea {
            height: 100px;
        }

input[type="file"],
        input[type="submit"],
        input[type="reset"] {
            background-color: blue;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }

input[type="file"] {
            width: auto;
        }

input[type="submit"]:hover,
        input[type="reset"]:hover {
            background-color: #003366;
        }

  /* Style checkboxes */
        input[type="checkbox"] {
            margin-right: 5px;
        }

 .checkbox-label {
            font-weight: normal;
        }
    </style>
</head>
<body>
    <h2>STUDENT REGISTRATION FORM</h2>
    <form action="#">
        <label for="firstName">First Name:</label>
        <input type="text" id="firstName" name="firstName">
        
<label for="lastName">Last Name:</label>
        <input type="text" id="lastName" name="lastName">
        
<label for="gender">Gender:</label>
        <select id="gender" name="gender">
            <option value="male">Male</option>
            <option value="female">Female</option>
        </select>
        
 <label for="age">Age:</label>
        <input type="number" id="age" name="age">
        
 <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob">
        
 <label for="email">Email Address:</label>
        <input type="email" id="email" name="email">
        
 <label for="password">Password:</label>
        <input type="password" id="password" name="password" minlength="8">
        
<label for="confirmPassword">Confirm Password:</label>
        <input type="password" id="confirmPassword" name="confirmPassword">
        
<label for="phoneNumber">Phone Number:</label>
        <input type="tel" id="phoneNumber" name="phoneNumber" pattern="[0-9]{10}">
        
<label for="address">Address:</label>
        <textarea id="address" name="address"></textarea>
        
<label for="state">State:</label>
        <select id="state" name="state">
            <option value="" disabled selected>-Select your state..-</option>
            <option value="state1">State 1</option>
            <option value="state2">State 2</option>
        </select>
        
<label for="pinCode">Pin Code:</label>
        <input type="text" id="pinCode" name="pinCode">
        
<label for="hobbies">Hobbies:</label><br>
        <input type="checkbox" id="music" name="hobbies" value="music">
        <label class="checkbox-label" for="music">Music</label><br>
        <input type="checkbox" id="movies" name="hobbies" value="movies">
        <label class="checkbox-label" for="movies">Movies</label><br>
        <input type="checkbox" id="sports" name="hobbies" value="sports">
        <label class="checkbox-label" for="sports">Sports</label><br>
        <input type="checkbox" id="travel" name="hobbies" value="travel">
        <label class="checkbox-label" for="travel">Travel</label><br>
        
<label for="photo">Upload Photo:</label>
        <input type="file" id="photo" name="photo" accept="image/*">
        
<label for="declaration">I hereby declare that the above information provided is true and correct.</label>
        <input type="checkbox" id="declaration" name="declaration">
        
<label for="robot">I'm not a robot:</label>
        <input type="checkbox" id="robot" name="robot">
        
 <input type="submit" value="Register">
        <input type="reset" value="Reset">
    </form>
</body>
</html>


#Payment
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form 2</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

h2 {
            text-align: center;
            margin-top: 30px;
            margin-bottom: 30px;
        }
        
 form {
            max-width: 400px;
            margin: 0 auto;
            padding: 30px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }

 input[type="text"],
        input[type="password"],
        input[type="number"],
        input[type="tel"],
        select {
            width: calc(100% - 12px);
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        input[type="submit"],
        input[type="reset"] {
            background-color: #003366;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }

 input[type="submit"]:hover,
        input[type="reset"]:hover {
            background-color: #001a33;
        }
    </style>
</head>
<body>
    <h2>Payment</h2>
    <form action="#">
        <label for="cardHolder">Card Holder's Name:</label>
        <input type="text" id="cardHolder" name="cardHolder">
        
<label for="cardNumber">Card Number:</label>
        <input type="text" id="cardNumber" name="cardNumber">
        
 <label for="expiryDate">Card Expiry Date:</label>
        <input type="month" id="expiryDate" name="expiryDate">
        
<label for="cvv">Card CVV:</label>
        <input type="password" id="cvv" name="cvv" minlength="3" maxlength="4">
        <input type="submit" value="Pay Now">
    </form>
</body>
</html>
