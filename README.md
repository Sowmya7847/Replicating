<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Image and Login Page</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
        }

        .image-container {
            width: 65%;
            background: url('https://president-tailors.com/wp-content/uploads/2023/07/Business-Suit.webp') no-repeat center center;
            background-size: cover;
        }

        .login-container {
            width: 35%;
            background-color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .login-container h2 {
            margin-bottom: 20px;
            text-align: center;
        }

        .login-container label {
            display: block;
            margin: 10px 0 5px;
            color: grey;
        }

        .login-container input[type="text"],
        .login-container input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            background-color: #e6f7ff;
        }

        .login-container button {
            width: 100%;
            padding: 10px;
            background-color: #003366;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .login-container button:hover {
            background-color: #002244;
        }
    </style>
</head>
<body>
    <div class="image-container"></div>
    <div class="login-container">
        <h2>Login</h2>
        <form>
            <label for="username">Username</label>
            <input id="username" type="text" placeholder="Enter the username" required />
            <label for="password">Password</label>
            <input id="password" type="password" placeholder="Enter the password" required />
            <button type="submit">Enter</button>
        </form>
    </div>
</body>
</html>
