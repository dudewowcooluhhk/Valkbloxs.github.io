<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ValkBlox</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #0d0d0d;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      display: flex;
      background-color: #111;
      border-radius: 12px;
      box-shadow: 0 0 40px rgba(0, 0, 0, 0.6);
      overflow: hidden;
    }

    .login-box {
      width: 400px;
      background-color: #0f0f0f;
      padding: 50px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      box-shadow: inset 0 0 30px rgba(0, 0, 0, 0.5);
    }

    .login-box h1 {
      font-size: 34px;
      font-weight: 700;
      color: white;
      text-align: center;
      text-shadow: 0 2px 8px rgba(0,0,0,0.5);
    }

    .login-box p {
      text-align: center;
      color: #bfbfbf;
      margin-bottom: 30px;
      font-size: 14px;
    }

    .discord-btn {
      background-color: #5865F2;
      color: white;
      border: none;
      width: 100%;
      padding: 12px;
      border-radius: 6px;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
    }

    .discord-btn:hover {
      background-color: #4752c4;
    }

    input {
      width: 100%;
      padding: 12px;
      margin-top: 15px;
      border: none;
      border-radius: 6px;
      background-color: #1a1a1a;
      color: white;
      font-size: 14px;
    }

    input:focus {
      outline: 2px solid #5865F2;
    }

    .tos {
      display: flex;
      align-items: center;
      gap: 8px;
      margin-top: 15px;
      font-size: 12px;
      color: #bfbfbf;
    }

    .tos a {
      color: #5865F2;
      text-decoration: none;
    }

    .signup-btn {
      margin-top: 25px;
      width: 100%;
      background-color: #6e59f2;
      color: white;
      padding: 12px;
      font-weight: 600;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.3s;
    }

    .signup-btn:hover {
      background-color: #5b46d9;
    }

    .bottom-text {
      text-align: center;
      color: #a1a1a1;
      margin-top: 20px;
      font-size: 13px;
    }

    .bottom-text a {
      color: #5865F2;
      text-decoration: none;
      margin-left: 4px;
    }

    .image-box {
      width: 600px;
      background: url('LoginImage2.png') center center / cover no-repeat;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="login-box">
      <h1>ValkBlox</h1>
      <p>Experience of freedom 2017L Revival!</p>

      <button class="discord-btn">Verify with Discord</button>

      <input type="text" placeholder="Username">
      <input type="password" placeholder="Password">

      <div class="tos">
        <input type="checkbox" id="tos">
        <label for="tos">I agree to the <a href="#">Terms of Service</a> and <a href="#">Privacy Policy</a></label>
      </div>

      <button class="signup-btn">Sign Up</button>

      <div class="bottom-text">
        Already have an account?
        <a href="#">Login</a> • <a href="#">Discord</a>
      </div>
    </div>
    <div class="image-box"></div>
  </div>
</body>
</html>
