# mydev-login-page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <img src="ll.jpeg" alt="Logo" class="logo">
        <h1 class="heading">Welcome to MyDev. Group</h1>
        <h2 class="subtitle">Santali Coding Community</h2>
        <form class="login-form">
            <div class="form-group">
                <label for="username">Username</label>
                <input type="text" id="username" name="username" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <button type="submit">Login</button>
        </form>
    </div>
</body>
</html>


body, h1, h2, p, label {
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Poppins', sans-serif; 
    background-color: #f9f9f9;
}

.login-container {
    max-width: 400px;
    margin: 0 auto;
    padding: 2rem;
    border: 1px solid #ccc;
    border-radius: 8px;
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center; 
}

.logo {
    max-width: 100px;
    margin-bottom: 1rem;
}

.heading {
    font-size: 2rem;
    font-weight: bold;
    margin-bottom: 0.5rem;
}

.subtitle {
    font-size: 1.2rem;
    color: #888;
    margin-bottom: 1.5rem;
}

.login-form {
    display: flex;
    flex-direction: column;
}

.form-group {
    margin-bottom: 1rem;
}

label {
    font-size: 1rem;
    font-weight: bold;
    display: block;
    margin-bottom: 0.5rem;
}

input {
    padding: 0.5rem;
    font-size: 1rem;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    padding: 0.5rem 1rem;
    font-size: 1rem;
    background-color: #142850;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #1a3250;
}
