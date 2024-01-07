<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SIM Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 20px;
        }
        
        form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #ffffff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input, select {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            box-sizing: border-box;
        }

        button {
            background-color: #4caf50;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <form action="#" method="post">
        <h2>SIM Registration (TNT.SMART)</h2>

        <label for="contactNumber">Contact No.</label>
        <input type="tel" id="contactNumber" name="contactNumber" required>

        <label for="validID">Valid ID</label>
        <input type="file" id="validID" name="validID" accept="image/*" required>

        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>

        <label for="age">Age</label>
        <input type="number" id="age" name="age" required>

        <label for="birthday">Birthday</label>
        <input type="date" id="birthday" name="birthday" required>

        <label for="address">Address</label>
        <textarea id="address" name="address" rows="4" required></textarea>

        <label for="userPlatform">User Platform</label>
        <select id="userPlatform" name="userPlatform" required>
            <option value="Android">Android</option>
            <option value="iOS">iOS</option>
            <option value="Windows">Windows</option>
        </select>

        <button type="submit">Submit</button>
    </form>

</body>
</html>
