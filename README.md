<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login with Name and Account Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex; /* Corrected from "flag" */
            justify-content: center;
            align-items: center;
            height: 100vh; /* Corrected from "wh" */
            margin: 0;
        }
        .login-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form id="loginForm">
            <input type="text" id="name" placeholder="Your Name" required>
            <input type="text" id="accountName" placeholder="Account Name" required>
            <button type="submit">Login</button>
        </form>
        <div id="errorMessage" class="error-message"></div>
    </div>
</body>
</html># Perf-Check
