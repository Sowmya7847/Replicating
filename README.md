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
            background: url('IMAGE_URL_HERE') no-repeat center center;
            background-size: cover;
        }

        .login-container {
            width: 35%;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #f4f4f4;
        }

        .login-box {
            width: 80%;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            background-color: white;
            border-radius: 8px;
        }

        .login-box h2 {
            margin-bottom: 20px;
            text-align: center;
        }

        .login-box label {
            display: block;
            margin: 10px 0 5px;
            color: grey;
        }

        .login-box input[type="text"],
        .login-box input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
            background-color: #e6f7ff;
        }

        .login-box button {
            width: 100%;
            padding: 10px;
            background-color: #003366;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .login-box button:hover {
            background-color: #002244;
        }
    </style>
</head>
<body>
    <div class="image-container"></div>
    <div class="login-container">
        <div class="login-box">
            <h2>Login</h2>
            <form>
                <label for="username">Username</label>
                <input id="username" type="text" placeholder="Enter the username" required />
                <label for="password">Password</label>
                <input id="password" type="password" placeholder="Enter the password" required />
                <button type="submit">Submit</button>
            </form>
        </div>
    </div>
</body>
</html>
