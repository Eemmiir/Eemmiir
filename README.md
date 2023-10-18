<!DOCTYPE html>
<html lang="en">
<head>
  <title>Google</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>

  <nav>
    <a href="#">Gmail</a>
    <a href="#">Images</a>
    <i class="fa-solid fa-ellipsis-vertical"></i>
    <i class="fa-solid fa-user"></i>
  </nav>

  <main>
    <img src="https://logos-world.net/wp-content/uploads/2020/09/Google-Logo.png" alt="Logo">
    <input type="text" name="" id="">

    <button type="button">Google Search</button>
    <button type="button">I'm Feeling Lucky</button>
    <p>Google offered in:
      <a href="#">кыргызча</a> 
      <a href="#">русский</a>
    </p>
  </main>

  <footer>
    <div class="footer-left">
      <a href="#">About</a>
      <a href="#">Advertising</a>
      <a href="#">Business</a>
    </div>
    <div class="footer-right">
    <a href="#">Privacy</a>
    <a href="#">Terms</a>
    <a href="#">Settings</a>
    </div>
    <div>

    </div>
  </footer>

</body>
</html>


*{
    box-sizing: border-box;
  }
  
  nav {
    float: right;
  }
  
  nav a {
    color: black;
    text-decoration: none;
  }
  
  nav * {
    margin: 10px 5px;
  }
  
  nav i {
    font-size: 25px;
  }
  
  main img {
    display: block;
    width: 300px;
    margin: auto;
  }
   

  input[type="text"] {
    display: block;
    margin: auto;
    width: 600px;
    height: 5px 20px;
    height: 50px;
    border-radius: 25px;
    border: 1px solid #909090;
    padding: 20px 20px;
    margin-bottom: 30px;
  }

  main {
    text-align: center;
    padding-top: 10%;
  }

  main div button {
    border: non;
    font-size: 18px;
    padding: 10px;
  }


  .footer-right {
    position: absolute;
    right: 5px;
    bottom:5px;
  }

  .footer-left {
    position: absolute;
    left: 5px;
    bottom:5px;
  }

  footer a {
    text-decoration: none;
    color:black;
  }
  
