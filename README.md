<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Show Password Button</title>
  <style>
*{
  background-color: #c9b3b3;
  font-family: "FrankRuehl";
}
form.login{
  border: 2px solid whitesmoke;
  border-radius: 15px;
  width: 400px;
  height: 550px;
  background: linear-gradient(
  to bottom,
  cyan,
  skyblue,
  deepskyblue,
  blueviolet);
  position: relative;
  left: 450px;
  top: 50px;
  box-shadow: 0px 5px 10px;
}
input[type="email"] {
  position: relative;
  left:45px ;
  top: 80px;
  height: 35px;
  width: 300px;
  border-top-left-radius: 20px;
  border-bottom-right-radius: 20px;
  text-align: center;
  font-family: "FrankRuehl";
  font-size: 20px;
  border: 2px solid rgb(255, 9, 0);
  background-color: #d3d3d3;
  transition: all 1s ease-in-out;
}
input[type="email"]:hover{
  border-top-left-radius: 0px;
  border-bottom-right-radius: 0px;
  border-bottom-left-radius: 20px;
  border-top-right-radius: 20px;
}
input[type="password"] {
  position: relative;
  left:45px ;
  top: 80px;
  height: 35px;
  width: 300px;
  border-bottom-left-radius: 20px;
  border-top-right-radius: 20px;
  text-align: center;
  font-family: "FrankRuehl";
  font-size: 20px;
  border: 2px solid rgb(0, 255, 4);
  background-color: #d3d3d3;
  transition: all 1s ease-in-out;
}
input[type="password"]:hover{
   border-bottom-left-radius: 0px;
  border-top-right-radius: 0px;
  border-top-left-radius: 20px;
  border-bottom-right-radius: 20px;
}
input[type="submit"]{
   position: relative;
  left:125px ;
  top: 170px;
  height: 35px;
  width: 130px;
  border-radius: 20px;
  border: none;
  text-align: center;
  font-family: "FrankRuehl";
  font-size: 20px;
  background: linear-gradient(to right,red,orangered,darkorange,orange,gold,yellow);
  transition: all 1s ease-in-out;
}
input[type="submit"]:hover {
  animation: hello 2s infinite forwards;
}
@keyframes hello {
0%{
  background: linear-gradient(to right,cyan,skyblue);
}
  10%{
    background: linear-gradient(to right,cyan,skyblue,deepskyblue);
  }
  20%{
    background: linear-gradient(to right,cyan,skyblue,deepskyblue,blue);
  }
  30%{
  background: linear-gradient(to right,skyblue,cyan);
}
  40%{
    background: linear-gradient(to right,deepskyblue,skyblue,cyan);
  }
  50%{
    background: linear-gradient(to right,blue,cyan,skyblue,deepskyblue);
  }
  60%{
  background: linear-gradient(to right,skyblue,cyan);
}
  70%{
    background: linear-gradient(to right,deepskyblue,cyan,skyblue);
  }
  80%{
    background: linear-gradient(to right,blue,cyan,skyblue,deepskyblue);
  }
  90%{
  background: linear-gradient(to right,skyblue,cyan);
}
  100%{
    background: linear-gradient(to right,deepskyblue,cyan,skyblue);
  }
}
h1{
  background-color: transparent;
  text-align: center;
}
h3{
  background-color: transparent;
  position: relative;
  top: 95px;
  left: 130px;
}
  </style>
</head>
<body>
<form class="login">
  <h1>Login form</h1>
  <h3>Email or Phone:</h3>
  <input type="email" placeholder="Enter your email address">
  <h3 style="background-color: transparent;
  position: relative;
  top: 95px;
  left: 130px;">Password:</h3>
  <input type="password" placeholder="Enter password">
  <input type="submit" value="Login">
</form>
</body>
</html>
