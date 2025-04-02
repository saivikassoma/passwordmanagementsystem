<html lang="en">
<head>
    <!-- Font Awesome script commented out; uncomment if needed -->
    <!-- <script src="https://kit.fontawesome.com/689bbb916f.js" crossorigin="anonymous"></script> -->
    <link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Manager</title>
</head>
<body>
    <div id="info">
        <h2>Password Manager</h2>
        <p>
            In this website, you can store your personal websites, passwords, usernames, and their names,and access them easily.
        </p>
    </div>
    
    <div class="tab">
        <table>
            <thead>
                <tr>
                    <th>Website</th>
                    <th>Username</th>
                    <th>Password</th>
                    <th>Reset</th>
                    <th>Change</th>
                </tr>
            </thead>
            <tbody>
                <!-- Rows will be dynamically added here via JavaScript -->
            </tbody>
        </table>
    </div>

    <div class="con">
        <label for="websitename" id="web">Website Name: </label>
        <input type="text" id="websitename"><br/><br/>
        <label for="username" id="user">Username: </label>
        <input type="text" id="username"><br/><br/>
        <label for="password" id="pass">Password: </label>
        <input type="text" id="password"><br/><br/>
    </div>
    
    <button id="create">
        Set Things
    </button>

    <script src="index.js"></script>
</body>
</html>