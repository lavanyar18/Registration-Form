# Registration-Form<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Registration Form</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: linear-gradient(135deg, #4e73df, #1cc88a);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    background: #fff;
    padding: 40px;
    width: 400px;
    border-radius: 10px;
    box-shadow: 0 15px 30px rgba(0,0,0,0.2);
}

.container h2 {
    text-align: center;
    margin-bottom: 25px;
    color: #333;
}

.input-group {
    margin-bottom: 20px;
}

.input-group label {
    display: block;
    margin-bottom: 6px;
    font-weight: bold;
    color: #555;
}

.input-group input {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 6px;
    font-size: 14px;
    transition: 0.3s;
}

.input-group input:focus {
    border-color: #4e73df;
    outline: none;
    box-shadow: 0 0 5px rgba(78,115,223,0.4);
}

button {
    width: 100%;
    padding: 12px;
    background: #4e73df;
    border: none;
    color: #fff;
    font-size: 16px;
    border-radius: 6px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    background: #2e59d9;
}

.login-link {
    text-align: center;
    margin-top: 15px;
    font-size: 14px;
}

.login-link a {
    color: #4e73df;
    text-decoration: none;
    font-weight: bold;
}

.login-link a:hover {
    text-decoration: underline;
}
</style>
</head>

<body>

<div class="container">
    <h2>Create Account</h2>

    <form>
        <div class="input-group">
            <label>Full Name</label>
            <input type="text" placeholder="Enter your full name" required>
        </div>

        <div class="input-group">
            <label>Email</label>
            <input type="email" placeholder="Enter your email" required>
        </div>

        <div class="input-group">
            <label>Password</label>
            <input type="password" placeholder="Create a password" required>
        </div>

        <div class="input-group">
            <label>Confirm Password</label>
            <input type="password" placeholder="Confirm your password" required>
        </div>

        <button type="submit">Register</button>

        <div class="login-link">
            Already have an account? <a href="#">Login</a>
        </div>
    </form>
</div>

</body>
</html>
